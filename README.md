## Introduction

Project Browser (PB) makes it possible to find modules within your Drupal installation. It removes the need to leave the admin UI and visit Drupal.org to find and install modules. It is build to be a more intuitive experience than the module listing on Drupal.org. Only modules compatible with your site are displayed, and enhanced filtering capabilities provide a streamlined view of projects.

Project Browser queries the Drupal.org API in real-time to ensure that the content is easily accessible and up to date. (You may write a plugin to switch using the Drupal API for your own backend if you wish.)

Our goal is to make it easier to find and install modules for people new to Drupal and site builders. Developers will also find this valuable since it provides the composer commands to get the modules.

- For the description of the module visit: [https://www.drupal.org/project/project_browser](https://www.drupal.org/project/project_browser)
- To submit bug reports and feature suggestions or to track changes, visit: [https://www.drupal.org/project/issues/project_browser?categories=All](https://www.drupal.org/project/issues/project_browser?categories=All)


## Requirements

This module requires no modules outside of Drupal core.


## Installation 

*If you intend to contribute to Project Browser, skip this step and use the "Contributing" instructions instead*

Install with composer: `composer require drupal/project_browser` then enable the module.


## Contributing

- Follow the [Git instructions](https://www.drupal.org/project/project_browser/git-instructions
  ) to clone project browser to your site
- In the `/project_browser` directory, install PHP dependencies with `composer install`
- In the `/project_browser/sveltejs` directory:
  - install JS dependencies with `yarn install` 
  - For development, run the dev script `yarn dev` which will watch for filesystem changes
    - Note: `yarn dev` will report the app is available localhost, but it is fully available in your Drupal site at `admin/modules/browse`
  - When you are done, compile the changes with `yarn build`

_NOTE: More information is available in the contributor.md file!_

## Configuration

Navigate to Administration > Extend > Browse.

Filter by Recommended projects or All projects
Search and filter by Title, Sort By, Order and Categories
Customize results layout by List or Grid Format


## Maintainers

- Biró, Csaba Attila (Soriarty) - [link]


.. These are examples of badges you might want to add to your README:
   please update the URLs accordingly

    .. image:: https://api.cirrus-ci.com/github/<USER>/F.R.I.D.A.Y.svg?branch=main
        :alt: Built Status
        :target: https://cirrus-ci.com/github/<USER>/F.R.I.D.A.Y
    .. image:: https://readthedocs.org/projects/F.R.I.D.A.Y/badge/?version=latest
        :alt: ReadTheDocs
        :target: https://F.R.I.D.A.Y.readthedocs.io/en/stable/
    .. image:: https://img.shields.io/coveralls/github/<USER>/F.R.I.D.A.Y/main.svg
        :alt: Coveralls
        :target: https://coveralls.io/r/<USER>/F.R.I.D.A.Y
    .. image:: https://img.shields.io/pypi/v/F.R.I.D.A.Y.svg
        :alt: PyPI-Server
        :target: https://pypi.org/project/F.R.I.D.A.Y/
    .. image:: https://img.shields.io/conda/vn/conda-forge/F.R.I.D.A.Y.svg
        :alt: Conda-Forge
        :target: https://anaconda.org/conda-forge/F.R.I.D.A.Y
    .. image:: https://pepy.tech/badge/F.R.I.D.A.Y/month
        :alt: Monthly Downloads
        :target: https://pepy.tech/project/F.R.I.D.A.Y
    .. image:: https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter
        :alt: Twitter
        :target: https://twitter.com/F.R.I.D.A.Y

.. image:: https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold
    :alt: Project generated with PyScaffold
    :target: https://pyscaffold.org/

|

===========
F.R.I.D.A.Y
===========


    Add a short description here!


A longer description of your project goes here...
