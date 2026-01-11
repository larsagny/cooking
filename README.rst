=======
cooking
=======


Cook book for my kids. Makes use of mkdos. With every push to the main branch the static sites are build afresh and published to the corresponding netlify project. See the github action file for details.   

.. image:: https://img.shields.io/pypi/v/cooking.svg
        :target: https://pypi.python.org/pypi/cooking

.. image:: https://img.shields.io/travis/larsclaussen/cooking.svg
        :target: https://travis-ci.com/larsclaussen/cooking

.. image:: https://readthedocs.org/projects/cooking/badge/?version=latest
        :target: https://cooking.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status


mkDocs Boilerplate contains all the boilerplate you need to create a mkDocs site.


* Free software: MIT license
* Documentation: https://cooking.readthedocs.io.


Installation
------------

Create an virtual environment and then run 


`pip install -r requirements.txt`




Run locally
-----------

To run locally start the mkdocs server wit the command

`mk serve`

This will serve the sites on http://127.0.0.1:8000/. 


Netlify integration
-------------------

The netify project has been set up manually. A personal netlify access token has been created and registered with the github repository as a secret. The manual project creation produces an app id that can be         used when running the `netlify deploy --dir=public --prod` command. This command picks up the `NETLIFY_SITE_ID` and the `NETLIFY_AUTH_TOKEN` environmental variables. 


Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage
