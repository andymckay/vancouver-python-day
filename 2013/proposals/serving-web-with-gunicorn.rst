Serving Web with Gunicorn (instead of mod_wsgi)
-----------------------------------------------

Summary:

Apache is a ubiquitous web server and many of us end up using it to serve our python web apps in combination with mod_wsgi. I'll talk about my experiences switching to the Gunicorn_ web server using lightweight eventlet_ workers: memory utilization, reverse proxies, threadlocal confusion, and other highlights.

Intendened audience:

Python web app developers: Pyramid, Django, Flask, whatever...

Given before?:

No

About you:

At Zymeworks_, I develop a Lab Information Management System using Python, Pyramid, SQLAlchemy, and AngularJS. I also tinker with DevOps, DIY electronics, and the arts.

.. _Gunicorn: http://gunicorn.org
.. _eventlet: http://eventlet.net
.. _Zymeworks: http://zymeworks.com