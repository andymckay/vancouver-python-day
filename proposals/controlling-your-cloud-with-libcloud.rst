Controlling Your Cloud With libcloud
------------------------------------

Summary:

Whether you're using one provider or many of them, `libcloud <http://libcloud.apache.org/>` makes working with the cloud a breeze. With support for many of today's cloud providers, libcloud makes it easy to manage compute and storage resources or to configure load balancers and DNS, and do so while abstracting away many of the differences between vendors. Have a look at how easy it is to take control of your cloud by using libcloud.

Longer description:

What I'd like to show is how easy it is to build up a cloud that makes use of a few different providers, such as creating a couple of Rackspace servers, putting them behind a load balancer, and the servers run a little web app that uses a different storage vendor. I'm not a fan of live demos, especially because it takes time to spin up servers and wait for DNS to propogate and stuff like that, so it'll likely be something I've already executed, but it'll be a very code-heavy walk through.

Intendened audience:

Anyone using "the cloud", especially via any of the many supported providers that libcloud supports (http://libcloud.apache.org/supported_providers.html).

Given before?:

I haven't given it yet, but I'm going to be giving this talk to the Cleveland Python Users Group on November 11, a couple of days before I head up to Vancouver for CascadiaJS and dev week. Although it's not the exact same, I've given a similar talk recently that uses `pyrax <https://github.com/rackspace/pyrax>` at the Chicago Python Users Group: http://www.youtube.com/watch?v=-0P5EvYI0Rk

About you:

I'm a Software Engineer and Python Developer Advocate at `Rackspace <http://www.rackspace.com/>`, where I work on `libcloud <http://libcloud.apache.org/>`, `pyrax <https://github.com/rackspace/pyrax>`, and whatever other open source stuff I can. I'm a CPython core developer, a director of the Python Software Foundation, and organizer and publicity coordinator for PyCon.

If you're asking for speaking experience, I've spoken at the last three PyCons and have presented several times to the Chicago Python Users Group over the last handful of years.
