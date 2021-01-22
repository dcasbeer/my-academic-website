<img align="left" width="75" height="75" src="https://avatars3.githubusercontent.com/u/29385237?s=280&v=4"> 

#  Building Hugo from source code 

<br/>

## Install Hugo
Because of permissions on my machine, I don't have access to brew, and I cannot run the tarball of the executable for Hugo. So I have to build this myself.

I'm adapting the instructions from the [Hugo Install Website](https://gohugo.io/getting-started/installing/#build-from-source-on-mac). 

* __Create a directory for go and hugo files__
    * Mine was called `Setup_Hugo`

* __Install Go:__ 
    * [Download Go](https://golang.org/dl/)
    * I downloaded the Go archive for Darwin `go1.15.6.darwin-amd64.tar.gz`
    * Unzip archive into my local Applications folder
        * Apparently Hugo will require the go installation to run, not just for installations
    * Add Go executable to the path. For me, I added the following to my `.zshrc` file

            export PATH=$PATH:"/Users/<username>/Code/Website/go/bin"

    * If you can't run Go because of Mac's security, see [this website](https://golang.org/doc/install/source) for building Go from source

* __Compile Hugo__
    * While in the `Setup_Hugo` folder
    * Create directory for the source code

            mkdir -p src/

    * Download the source code for the latest hugo
        * Version 0.80.0 at the time I'm writing this
        * [Source code.tar.gz](https://github.com/gohugoio/hugo/releases)
    * Copy the source code into the folder `src/github.com/gohugoio`
        * For me this resulted in the following: `src/github.com/gohugoio/hugo-0.80.0`
    * Navigate to the hugo folder and fetch the hugo dependencies

            cd src/hugo-0.80.0
            go get

    * Compile the ___extended___ version of Hugo

            go install -tags extended

    * The hugo executable is now located in the `$GOPATH/bin`. For me this is located at `~/go/bin`.
    *  🎇 For importing academic import *you must install* hugo - meaning it must be in your path
        * Bad form: but I copied the hugo executable to the `~/Code/Website/go/bin/` folder, which was added to my path when installing Go.
        * This allows hugo to be called as `hugo` rather than `./hugo` and academic-cli now imports appropriately