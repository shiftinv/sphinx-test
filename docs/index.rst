.. sphinx-test documentation master file, created by
   sphinx-quickstart on Wed Oct  5 20:32:52 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to sphinx-test's documentation!
=======================================

[things and stuff here]


Intersphinx
~~~~~~~~~~~

.. code-block:: rst

   :attr:`minute attribute <datetime.time.minute>`
   :attr:`minute attribute but with inventory name <python:datetime.time.minute>`

   :ref:`datetime.datetime header <python:datetime-datetime>`
   :ref:`datetime.datetime header with inventory name <python:datetime-datetime>`

This renders to:

| :attr:`minute attribute <datetime.time.minute>`
| :attr:`minute attribute but with inventory name <python:datetime.time.minute>`

| :ref:`datetime.datetime header <python:datetime-datetime>`
| :ref:`datetime.datetime header with inventory name <python:datetime-datetime>`
