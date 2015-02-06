# Overview

This guide is the official Opencast user's manual for the open-source video capture system.

# Setup

### Git Repository
The source documentation is hosted on this git repository: https://bitbucket.org/entwinemedia/opencast-usersguide.git

### Branches
There are 3 branches that are used for the documentation:
* **master**: This is used for production documentation that is published
* **staging**: This is used for staging the documentation before releasing it
* **draft**: This is the working copy of the documentation

### Hosting

The documentation is being built and published using [ReadTheDocs](http://readthedocs.org/). The Entwine account is available in passpack.

Each branch is published on ReadTheDocs:

* **master**: http://opencast-users-guide.readthedocs.org/
* **staging**: http://opencast-users-guide.readthedocs.org/en/staging/
* **draft**: http://opencast-users-guide.readthedocs.org/en/draft/

> Note: The branches are currently published as "protected" which means they are publicly available but not listed on the Builds list on ReadTheDocs

### Building Locally
The documentation is written in standard markdown. The tool that is used to build the documentation is [mkdocs.org](http://www.mkdocs.org/)

In order to build the documentation locally, you will need to [install mkdocs](http://www.mkdocs.org/#installation). Check out the documentation or use the following command

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
