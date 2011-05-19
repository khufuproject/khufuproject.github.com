.. Khufu Project documentation master file, created by
   sphinx-quickstart on Wed May 18 17:20:14 2011.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

=============
Khufu Project
=============

What is the Khufu Project?
==========================

The Khufu Project is the umbrella name of all components provided under
name *khufu_* running on the Pyramid_ web framework.

*Khufu* components are really just Pyramid_ components that
make a series of assumptions:

.. _Pyramid: http://pylonsproject.org/projects/pyramid/about

  1. `SQLAlchemy <http://www.sqlalchemy.org>`_ for persistence
  2. `Jinja2 <http://jinja.pocoo.org/docs/>`_ for templating
  3. Traversal-based url mappings

Released Components
===================

  * khufu_opinion 0.2.2: Set of paster templates for rapid Pyramid development

    - Version Control: https://github.com/khufuproject/khufu_opinion

    - PyPi: http://pypi.python.org/pypi/khufu_opinion/

  * khufu_sqlalchemy 0.5.1: SQLAlchemy bindings for Pyramid

    - Docs: http://khufuproject.github.com/khufu_sqlalchemy/

    - Version Control: https://github.com/khufuproject/khufu_sqlalchemy

    - PyPi: http://pypi.python.org/pypi/khufu_sqlalchemy/

  * khufu_script 0.6: Manage script support for Khufu/Pyramid apps

    - Version Control: https://github.com/khufuproject/khufu_script

    - PyPi: http://pypi.python.org/pypi/khufu_script/

  * khufu_siteview 0.9.1: Easy template-to-view support

    - Version Control: https://github.com/khufuproject/khufu_siteview

    - PyPi: http://pypi.python.org/pypi/khufu_siteview/


Clue Components
===============

The *clue_* series of components are generally useful Python and WSGI-based
components that have **no dependency** on **Khufu** or **Pyramid**.

  * clue_script 0.2.4: Easy utils for creating a script runner

    - Version Control: https://github.com/khufuproject/clue_script

    - PyPi: http://pypi.python.org/pypi/clue_script/

  * clue_sqlaloader 0.1.1: Data loader for SQLAlchemy

    - Version Control: https://github.com/khufuproject/clue_sqlaloader

    - PyPi: http://pypi.python.org/pypi/clue_sqlaloader/

.. toctree::
   :maxdepth: 2

Indices and tables
==================

* :ref:`genindex`
* :ref:`search`

