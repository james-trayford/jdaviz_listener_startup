# jdaviz_listener_startup
Getting Started with the JDAViz + STRAUSS listener functionality 

You can clone this repository locally. If you have SSH keys set up you can run:

`git clone git@github.com:james-trayford/jdaviz_listener_startup.git /path/to/your/directory`

Or just clone from the HTTP link as:

`git clone https://github.com/james-trayford/jdaviz_listener_startup.git /path/to/your/directory`

and then change directory:

`cd /path/to/your/directory`

### Python and setting up an environment:

This should work with python versions `3.8` to `3.11`.

We can set up an environment for this hacke inside the repository, using:

`python3 -m venv venv`
`source venv/bin/activate`

and install all the relevant modules using:

`pip install -r requirements.txt`

This may take a while first time. After that, you may want to override things like `jdaviz` with local copies, say if we want to edit the library on the fly. 

### Notebooks

We have a notebook as a starting point in the `./notebook/` directory:

`notebook/GettingStarted.ipynb`
