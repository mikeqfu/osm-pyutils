============
Installation
============

To install the latest release of **pydriosm** at `PyPI`_ via `pip`_:

.. code-block::

    pip install --upgrade pydriosm

To install the more recent version hosted directly from `GitHub repository`_:

.. code-block::

    pip install --upgrade git+https://github.com/mikeqfu/pydriosm.git

To test if **pydriosm** is correctly installed, try importing the package via an interpreter shell:

.. code-block::

    >>> import pydriosm
    >>> print(f"The current release version is: {pydriosm.__version__}")

.. parsed-literal::
    The current release version is: |version|

|

.. note::

    - If using a `virtual environment`_, ensure that it is activated.

    - To ensure you get the most recent version, it is always recommended to add ``--upgrade`` (or ``-U``) to ``pip install``.

    - The package has not yet been tested with `Python 2`_. For users who have installed both `Python 2`_ and `Python 3`_, it would be recommended to replace ``pip`` with ``pip3``. But you are more than welcome to volunteer testing the package with `Python 2`_ and any issues should be logged/reported onto the `Issues`_ page.

    - Possibilities of being unsuccessful to ``pip install pydriosm``

        - For *Windows* users:
            The ``pip`` method might fail to install some dependencies, such as `Fiona`_, `GDAL`_, `Shapely`_ and `python-Levenshtein`_. If errors occur when ``pip`` installing these packages, try instead to ``pip install`` their respective *.whl* files, which can be downloaded from the `Unofficial Windows Binaries for Python Extension Packages`_. After they are installed successfully, try again to install pydriosm.

        - For *Linux/Unix* users:
            To try out any earlier version (<2.0.0) on *Linux*, check `this page <https://github.com/mikeqfu/pydriosm/issues/1#issuecomment-540684439>`_ for installation instructions.

    - For more general instructions, check the `Installing Packages`_ page.

.. _`PyPI`: https://pypi.org/project/pydriosm/
.. _`pip`: https://packaging.python.org/key_projects/#pip
.. _`cmd.exe`: https://en.wikipedia.org/wiki/Cmd.exe
.. _`GitHub repository`: https://github.com/mikeqfu/pydriosm

.. _`virtual environment`: https://packaging.python.org/glossary/#term-Virtual-Environment
.. _`virtualenv`: https://packaging.python.org/key_projects/#virtualenv
.. _`Python 2`: https://docs.python.org/2/
.. _`Python 3`: https://docs.python.org/3/
.. _`Issues`: https://github.com/mikeqfu/pydriosm/issues

.. _`Fiona`: https://pypi.org/project/Fiona/
.. _`GDAL`: https://pypi.org/project/GDAL/
.. _`Shapely`: https://pypi.org/project/Shapely/
.. _`python-Levenshtein`: https://pypi.org/project/python-Levenshtein/
.. _`Unofficial Windows Binaries for Python Extension Packages`: https://www.lfd.uci.edu/~gohlke/pythonlibs/
.. _`Installing Packages`: https://packaging.python.org/tutorials/installing-packages