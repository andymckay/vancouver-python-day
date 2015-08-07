Scaling the Facebook cache infrastructure with Python
-----------------------------------------------------

Summary:

Facebook leverages in-memory data stores extensively. Even though caching is a conceptually simple service, several problems inherent to our scales make the deployment of our in-memory data store particularly interesting and challenging.

Facebook's real time in-memory data store includes two major services: Memcache, a look aside key-value store, and TAO, a read-through and write-through graph aware cache that supports structured queries. Both daemons run on thousands of dedicated servers.

In this talk, I will give an overview of the problems that we face deploying cache services that answer over a billion queries per second while maintaining sub-millisecond response time. I will describe the strategies that we use to mitigate them and since Python is a critical piece of the puzzle, I will highlight some of the areas where we use it.  I won't spare you from our war stories and the sense of scale could feel crushing at times but I will do by best to keep it entertaining.


Longer description:
N/A


Intended audience:

Web developer and system architects interested in learning how to build extremely scalable applications.


Given before?:

A shorter version of this talk was given at PyCon Canada 2013:
https://2013.pycon.ca/en/schedule/presentation/49/
http://pyvideo.org/video/2320/an-overview-of-the-facebook-cache

The long version was given in September 2013 in from of 120 attendees at the Rochester Institute of Technology.


About me:

Yannick Gingras is a senior developer with over ten years of experience. In addition to designing and developing Web services, he has managed teams, and has worked in the fields of machine learning, bioinformatics and e-commerce. He was the lead organizer of Montréal-Python user group, the co-chair of the PyCon conference, and a frequent contributor to free and open-source projects. Since 2011, he works as a production engineer at Facebook.
