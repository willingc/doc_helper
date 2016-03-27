# Documentation

## Current status
Thanks to dev team for your support and responsiveness. It's critical and much appreciated when managing this many repos.
### Tips going forward
- Loop me in early in the release process
- Feel free to experiment with new doc technologies but plug me in early to avoid duplication of efforts, unsustainable builds, and processes that do not scale well.
- Love docstrings to save developer time and improve docs
- Keep doc content near the source code for accuracy and timeliness as well as flexibility to change doc build and deployment technologies
### Visual overview
Documentation helper tool http://willingc.github.io/doc_helper/
### Late Dec 2015 - now
- Implemented tracking so the documentation builds cleanly and changes are deployed
- Implemented consistent sidebar theme and doc outline structure
- Added badges, README resources/links, and link to docs in repo descriptions
- Improved markdown support and notebook support
- Updated docs, as possible, to minimize repeat questions by tracking mailing list questions, gitter comments, and project issues

## Common setup with sphinx/ReadTheDocs
- Source currently supported: rST, md, ipynb
- Sphinx to build docs (recommonmark for md support and nbsphinx for notebooks)
- Preferred build/deploy on RTD: readthedocs.yml and environment.yml
- Dev meeting goal: create a common standard for yaml files to use as a template for existing and future docs
- Conda channel for specific package builds that might rely on C

## Notebooks in docs - nbsphinx and friends
- Initial work on custom theme (jupyter_sphinx_theme) came out of ipywidget documentation with Jon
- nbsphinx
- podoc (Rossant) still lacking NB4 support
- pypandoc: recent activity
- nbconvert

## JS toolchains for docs
- Initial work by Jon for widgets to be used in docs - custom theme
- API docs - swagger
- Importance of maintainability and scaling (Sphinx/RTD)
- Balance the flexibility and visual appeal (JS doc efforts)

## Document all this in a single location
- Currently, general info is going in Jupyter/Jupyter repo docs; project specific in individual project docs with links to general info in Jupyter/jupyter repo
- Some process info in my cal poly repo which should be migrated to a Documentation Contributor Guide

## Developer guide: unified, in one location, include docstring guidelines, etc.
* Right now it's scattered:
    - https://github.com/ipython/ipython/wiki/Dev:-Index
    - https://github.com/ipython/ipython/wiki/Dev:-Coding-style
    - https://github.com/ipython/ipython/wiki/Dev%3A-Documenting-IPython
* Migrate the above to jupyter/jupyter Contributor Guide
* General information in jupyter/jupyter docs; project specific in project repo

## Goals of next 3 months
- Maintain operations improvements
- Focus on user experiences
    * Set up JupyterHub with nbgrader for teaching
    * How to extend notebooks and add widgets
- Visual presentation of information (i.e. nbgrader)
- Collection of notebooks to guide a new user
- Document JupyterLab interfaces. Pictures are worth a thousand words.

