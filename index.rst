.. Platformus CMS documentation master file, created by
   sphinx-quickstart on Thu Aug 27 14:17:59 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. _index:

Introduction
============

Platformus CMS is free, open source and cross-platform CMS based on ASP.NET 5 and
[Platformus framework](https://github.com/Platformus/Platformus). It is build using the best and the most
modern tools and languages (Visual Studio 2015, C#, TypeScript, SCSS etc). Join our team!

Platformus CMS is completely modular and currently consists of 8 extensions:

* Platformus.Barebone;
* Platformus.Configuration;
* Platformus.Security;
* Platformus.Static;
* Platformus.Globalization;
* Platformus.Content;
* Platformus.Navigation;
* Platformus.Forms.

Each extension may consist of several projects:

* Platformus.X;
* Platformus.X.Data.Models;
* Platformus.X.Data.Abstractions;
* Platformus.X.Data.SpecificStorageA;
* Platformus.X.Data.SpecificStorageB;
* Platformus.X.Data.SpecificStorageC;
* Platformus.X.Frontend;
* Platformus.X.Backend;
* etc.

Using the features of the underlying Platformus framework you can easily create your own extensions
to extend the functionality of Platformus CMS.

Basic Concepts
--------------

Platformus CMS is object-oriented CMS and object is the central unit of its data model. Objects can be
standalone and embedded. While standalone objects can be accessed via URL, embedded objects can only be
used as the part of others.

Each object consists of properties and relations and is described by its class. Classes describe properties and
relations of the objects with the members. Each member has code, name, data type (for properties) or class (for
relations). In addition, with the data sources, classes describe which objects are to be loaded together with
the object.

For example, let’s say we have Developer class and Team class. Also, we can have Contact class too. Each
developer should have first name and last name properties and one relation to the object of class Team and one
or many relations to the objects of class Contact.

How to Use
----------

It is very easy to use Platformus CMS. Please take a look at our
[demo project](https://github.com/Platformus/Platformus-CMS-Demo) on GitHub.

You can also download our [ready to use sample](http://platformus.net/files/Platformus-CMS-Demo-1.0.0-alpha1.zip).
It contains everything you need to run Platformus CMS from Visual Studio 2015, including SQLite
database with the test data.

Links
-----

Website: http://platformus.net/ (under construction)

Docs: http://docs.platformus.net/ (under construction)

Contents
--------

.. toctree::
   :titlesonly:

   basic_concepts/index
   quick_start/index