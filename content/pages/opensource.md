Title: Opensource

I always loved the freedom that opensource software gives you as a software developer,
it allows me to deal with any need that came up in a library, framework or technology I have to deal with.

Are you stuck because you hit a bug in a library you are using? Just fix it, and you are back on the path.
Do you lack a feature in a framework on which your application is written? Feel free to add it!

Open source has always been present in my free time too. If I needed a software that wasn't available
on the platform that I was using, I could take the codebase and port it myself so that it became available.
Not only I could fix the things I had to deal with at work, but I could also fix the games I was playing
or the tools I was using if I was lucky enough that their codebase is available.

During the course of the years I have been involved in many Opensource projects,
at multiple levels:

### ![Apache Arrow](/images/arrow.png){height=32px;} Apache Arrow
[https://arrow.apache.org/](https://arrow.apache.org/)
  
Since 2021 I got involved in the Apache Arrow project, and more specifically
in the PyArrow library. Arrow is a swiss army knife for data analysis,
it acts both as a zero serialization interchange format, as a storage format,
as a Dataframe library or as a full feature query engine.
It's probably the most frequently used in-memory format for data science projects
and databases.

### ![TurboGears2](/images/turbogears.png){height=32px;} TurboGears2
[https://www.turbogears.org](https://www.turbogears.org)
  
My favourite web framework, I used and loved it so much that I became
release manager and then maintainer since version 2.2, given how much
it evolved during the course of the years, most of the code since version 2.3
has been written by me.

### DukPy
[https://github.com/amol-/dukpy](https://github.com/amol-/dukpy)

DukPy is a Javascript interpreter that I created for Python based on top of
the duktape engine. At the time
I was using quite heavily ReactJS for my web application, and as a Python
developer I fed of having to involve NodeJS only to compile my React widgets.
The Javascripts implementations for Python are
very heavy, hard to compile, have ton of dependencies and are too general purpose.
So I created mine and made sure that it was super straightforward to compile
and that it made possible to run all the Javascript tools that I needed.
Nowadays hundred of projects are relying on DukPy for their own needs.

### ![DEPOT](/images/depot.png){height=48px;}
[https://github.com/amol-/depot](https://github.com/amol-/depot)

DEPOT is a file management framework especially designed to deal with
attachments in web applications. It supports storing files in multiple
backends and pairing them to any column of a database providing full
transactional behaviour (file upload is rolled back if database transaction fails)
Nowadays DEPOT is used by many web projects, including the [Kotti CMS](https://kotti.readthedocs.io/en/latest/)

### Ming
[https://ming.readthedocs.io/en/latest/](https://ming.readthedocs.io/en/latest/)

Ming is a Object Document Mapper for MongoDB, it allows to interact
with MongoDB databases using Models defined in Python.
Ming has been the first ORM/ODM for MongoDB in Python and it's still
one of the most powerful. 
I have been co-maintainer and a main contributor to the project, 
especially in the areas of the MongoInMemory implementation and the ODM layer.
The project is heavily used by [https://sourceforge.net/](https://sourceforge.net/)
as their interface to MongoDB.

### ![Kajiki](/images/kajiki.jpg){height=32px;} Kajiki
[https://kajiki.readthedocs.io/en/master/](https://kajiki.readthedocs.io/en/master/)

Kajiki is a incredibly fast validated template engine for Python.
It has been created to replace Genshi, which was a powerful and validated template
engine for Python, that suffered from slow speed problems. Kajiki can be
tens of times faster while still retaining validation, which means that
your HTML code will never contain errors, as kajiki will detect those in your templates.
I have been a co-maintainer of kajiki up to 2021 when the project has moved
in the hands of Jack Rosenthal.

### Beaker
[https://github.com/bbangert/beaker](https://github.com/bbangert/beaker)

A Caching and Session management framework used by many web frameworks.
I have been the maintainer for a few years after Ben Bangert had left that role.

### Cython
[https://github.com/cython/cython](https://github.com/cython/cython)

As an heavy Cython user, I contributed fixes to the Debugger.
Mostly I focus on making sure the debugger works on OSX

