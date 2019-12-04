# OVERVIEW
## ** I. ** Packaging and Unpackaging Python Projects

#### A. Create the following directory using this structure:
> ```bash
>	**my_proj_package/**
>		**my_app_pkg/**
>			__init__.py
> ```

#### B. ADD the required files which are needed for distribution of your project
##### Directory Structure
> ```bash
>	**my_proj_package/**
>		**my_app_pkg/**
>			__init__.py
>	_setup.py_
>	_LICENSE_
>	_README.md_
> ```
>___
> 'setup.py:' is the build script for setuptools. It tells setuptools about your package (such as the name and version) as well as which code files to include.



packaging_tutorial/
  example_pkg/
    __init__.py
Once you create this structure, you’ll want to run all of the commands in this tutorial within the top-level folder - so be sure to cd packaging_tutorial.

example_pkg/__init__.py is required to import the directory as a package, and can simply be an empty file.
