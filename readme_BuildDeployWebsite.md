<!--
<img align="left" width="75" height="75" src="https://p7.hiclipart.com/preview/31/119/666/github-logo-repository-computer-icons-github.jpg">
-->

# Building and Deploy Website on Github

It is **much** simpler to use Netlify and host the website there. 

It looks like you have to have two respositories on Github

* One for the content
* One for the Hugo generated website

## Building and Deploying
* [Step by step](https://gohugo.io/hosting-and-deployment/hosting-on-github/#github-user-or-organization-pages)
* [Automate with a script](https://gohugo.io/hosting-and-deployment/hosting-on-github/#put-it-into-a-script)
* These instructions aline with that on [wowchemy](https://wowchemy.com/docs/guide/deployment/)
    * From what I understand the key for me with wowchemy is its ability to import bibtex files and create a publication page: [academic-cli](https://github.com/wowchemy/hugo-academic-cli)

## Broad steps
1. Copy (fork) a Hugo theme website
2. Create a website repository
3. Make this repsitory a submodule under the website
4. Run Hugo
5. Push public folder to the website repository

## How I did it
* __Create `<username>.github.io`__ repository
    * This repository hosts the static html website that is published on the web
    * Create this repo on the github website
    * Name the repo `<username>.github.io` (replacing '<username>' with your github username)
* __Create a repository__ from an existing Hugo theme. I used the [academic-starter theme](https://github.com/wowchemy/starter-academic) from wowchemy. From this website select the "Use this template" button to make a copy of the repository.

* __Clone the repository__ locally to the machine (I'm not sure the last submodule command is needed here - wowchemy instructions have it.)

``` 
git clone https://github.com/<github-username>/my-academic-website.git my_website
cd my_website
git submodule update --init --recursive
```
* __Set the `baseurl` in the `config.toml` file__ 
    * This tells hugo where the website will be hosted
    * Make the baseurl = "https://\<github-username\>.github.io/" in the `config/_default/config.toml` file
    * If you are hosting this elsewhere, change this to the appropriate link.

* __Create submodule__ for the static html website

        git submodule add -f -b master https://github.com/dcasbeer/dcasbeer.github.io.git public

* __Push everything up__ to the repository

        git add .
        git commit -m "Initial commit"
        git push -u origin master

* ___Before trying to build & deploy the website, kill the hugo server if it is running___
* Next, regenerate your website’s HTML code by running Hugo and uploading the public submodule to GitHub:

        ./hugo
        cd public
        git add .
        git commit -m "Build website"
        git push origin master
        cd ..

### [Automate build and deploy with a script](https://gohugo.io/hosting-and-deployment/hosting-on-github/#put-it-into-a-script)






