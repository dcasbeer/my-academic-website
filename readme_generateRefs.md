# How to generate references

We will use the [academic python package](https://pypi.org/project/academic/) to import references from zotero. 

To install academic, [follow the instructions on the website](https://pypi.org/project/academic/). Make sure that `go` and `hugo` are installed correct and can be called from a command line. (See [readme_SetupHugo.md](readme_SetupHugo.md) for setting up these prerequisites.)

I am still working on a streamlined process to keep 3 things up-to-date: Zotero, CV, and website. Perhaps I could look into automating the process using zotero and a bib file, but it is probably more work than I want to do. 


<img align="left" width="32" height="35" src="https://www.zotero.org/static/images/icons/zotero-icon-64-70%402x.png"> 

## &nbsp; Zotero management of my publications




I have put my publications in Zotero into separate folders with the structure as

    My Publications
    -- arXiv
    -- Conference Papers
    -- Journal Articles
    -- Report/Book/BkChapters/Thesis

This allows me to find each type easily. This is a little clunky though. So I have also tagged each item with "my publication," and a second tag indicating what type/class of publication it is. These classes are in the list:
* Journal
* Conference
* arXiv 
    * If this is a preprint of a published article, I would also include the type Journal, Conference etc. and
    * Connect the published article using the "related" link
*  Report
* Book
* Book Chapter
* Thesis

You might ask why I'm doing this, if each article has an item type" classification. I have found that when importing from online, sometimes conference papers are cited as book sections or conference papers as journals. This helps keep it straight as I'm doing setting up the organization. If I find that this is not needed, then I will stop with these tags. 

## Import the article into the website

There are two ways to do this: [import a bib file](https://wowchemy.com/docs/content/publications/#import-from-bibtex) or [create a new publication](https://wowchemy.com/docs/content/publications/#command-line)

### Importing a bib file
* Select the desired publication(s) in zotero and export as a bib file. 
    * There is no need to export the file as this is not automatically imported
* From the website main directory run
        
        academic import --bibtex <bib_filename>.bib

* Check the details of the imported file to make sure everything is correct

### Create a new publication listing
* From the website main directory run

        hugo new --kind publication publication/<key-for-new-publication>

    * The key here is the name of the folder keeping in line with the automatic import this would be author-wordFromTitle-year

### Publication type
* I have added two different type of publications from the standard that are built in, including the standard ones these are

    * 0 = Uncategorized
    * 1 = Conference paper
    * 2 = Journal article
    * 3 = Preprint / Working Paper
    * 4 = Report
    * 5 = Book
    * 6 = Book section
    * 7 = Thesis (v4.2+ required)
    * 8 = Patent (v4.2+ required)
    * 9 = Published Online (_Personal Custom Publication Type_)
    * 10 = Accepted (_Personal Custom Publication Type_)

These last two help me to quickly know which publications are still in need of update and should be monitored for final publication information.