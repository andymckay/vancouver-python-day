Talk title
----------

Summary:

An overview of the tools and systems we've created at Bron Animation . I'll be
covering things like:
- Python for applications like Maya, Nuke, Katana, MotionBuilder etc.
- Rigging
- File I/O
- Dynamic assembly of complex assets
- Python for asset management in Animation production.
- Web framework AMS
- Client APIs
- Event Daemons
- Caching with redis
- Python for rendering. 

Longer description:

For a long time now Animation, Film and Games have been using Python extensively.
Python is quite commonly the backbone of many pipelines in the industry. I will be
drawing from my experience across multiple studios to show how Python can be
used to solve many issues with production pipelines.

I’ll be explaining how we’ve implemented Python in software like Maya and Nuke to
facilitate artist workflow. There will also be an overview of how we’ve used Python
for interactions with our primary production tracking software, Shotgun, including
an event daemon to catch actions performed in Shotgun to perform automated tasks
and our home-brew caching solution using redis. I’ll then go over the structure of
our Asset Management system in Python using the Django framework and MySQL.
I will cover the advantages and pitfalls in a system like this. There will be brief
coverage on what tools we’ve developed to facilitate rendering on our Qube
renderfarm. Lastly there will be a section devoted to outlining the challenges we see
coming ahead and how Python will help. 

Intendened audience:

VFX, Animation and Games Programmers, or those curious

Given before?:

No

About you:

Kirk has been writing pipelines for film and games for the last 10 years with
companies such as Electronic Arts, ImageMovers Digital, Dr. D, MPC and now Bron
Animation. Python has been an essential part of streamlining Games, Visual Effects
and Animation pipelines. He's used Python for interactions with 3D software such as
Maya, MotionBuilder and Nuke, created asset management systems, deployment
mechanisms and video processing systems among other things. 
