.. Resume documentation master file, created by
   sphinx-quickstart on Mon Apr  1 22:18:41 2019.

Zachary Johnson
==================================
zjohnson@adobe.com

.. image:: me_circle.png

About Me
========
- BS in Computer Science @ Brigham Young University
- Software Engineer @ Adobe Systems
- Former BYU Linux Club VP
- Avid programmer
- A little nerdy
- `Github`_

.. _Github: https://github.com/zachanator070


Job History
===========
- Mar 2017 - Present : SKMS Software Developer @ Adobe
- Dec 2016 - Mar 2017 : CPT Software Developer @ Adobe
- May 2016 - Dec 2016 : CPT Intern @ Adobe
- Nov 2015 - May 2016 : Automation Infrastructure Intern @ Microfocus
- April 2013 - Nov 2015 : Student System Administrator @ BYU CS Department

Experience
==========

SKMS
----
- Improve Global Performance
   - Used docker to plan scalability into SKMS
   - Split read/write MySQL connections
   - HA Proxy
   - Master/Slave MySQL cluster in Docker
   - Simulated artificial lag in Docker
   - Session management

- MediaWiki Deprecation
   - Used Splunk and Adobe Analytics to determine users of deprecated pages
   - Scraped pages using MediaWiki Api
   - Converted pages to markdown using Pandoc
   - Automated using Python3

- Object Relationship Security Vulnerability
   - Used Splunk logs to determine broken permission methods
   - 400+ edits to current security permissions
   - Provided unit tests to prove functionality
   - Zero impact on deployment

- Infoblox Integration
   - Created sync process in SKMS that bi-directionally syncs IP blocks
   - Configurable source of record
   - Abstracted in PHP7

IQ
--
- Designed to update CMDB assets with data from various API sources
- Integrations with:
   - VCenter API
   - Dell RacADM API
   - Splunk API
   - RackHD API
   - SKMS API
- Uses asyncio for dealing with async processes
- Implemented AI model to predict role of a device found
- Experimented with Naive Bayes and Neural Network for AI model
- Uses scikitlearn for AI implementation
- Deployed through Moonbeam/Ethos
- Distributed tasks using RabbitMQ
- Transitioned from Python2 to Python3
- Unit tests > 80% code coverage
- Swagger Docs + Sphinx Docs

For Fun
=======

World Forge
-----------
- Dungeons and Dragons + google maps
- Mongo DB
- passport.js
- react.js
- quill.js
- jimp.js

Incognito
---------
- Party game where you lie to your friends
- Mongo DB
- react.js
- socket.io to transmit game state changes