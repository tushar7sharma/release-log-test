# template-project

This is a Template for any Python based project, it contains what Project Thoth and the AI CoE need:

1. GitHub defaults and Templates for issues
2. configuration for Coala and Black (code formating)
3. basic configuration for Zuul
4. configuration for Thoth (stage environment, Red Hat VPN only)
5. if you are writing a Python module, Kebechet could manage releases of your packages for you
6. if credentials are provided, Python module releases could be published to PyPI

Dependencies should be managed using `pipenv` (`Pipfile`, and the `Pipfile.lock` could be created by `thamos advise`), `pip3` and a `requirements.txt` files could be used.

# Pushed Test Commit Messages : 
- Fixed bug that impacted server performance
- Support for new clusters added
- Data bug fixed
- Added support for new version of Openshift
- Performance improved
- :pushpin: Automatic update of dependency thoth-common from 0.13.7 to 0.13.8
- :pushpin: Automatic update of dependency deprecated from 1.2.8 to 1.2.9
