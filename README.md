# Overview

This guide is the official Opencast user's manual for the open-source video capture system.

# Setup

### Git Repository
The source documentation is hosted on this Git repository: https://bitbucket.org/opencast-community/matterhorn

### Building Locally
The documentation is written in standard markdown. The tool that is used to build the documentation is [mkdocs.org](http://www.mkdocs.org/)

In order to build the documentation locally, you will need to [install MkDocs](http://www.mkdocs.org/#installation). Check out the documentation or use the following command

```
$ pip install mkdocs
```

From there, download the source of the documentation, go to the repo and use the following command to start a simple http server and build the doc:

```
$ mkdocs serve
```

# Dependencies and Requirements

* Python
* mkdocs

# Editing on dillinger.io
In order to edit from Dillinger.io, you will need to connect your github account to dillinger. See the left nav to do that. Once you have connected your github account, use Import From link on the top nav to import the file you want to edit (you can't import all files at the same time, but might be a good feature request). 

Once you are done editing your file, just