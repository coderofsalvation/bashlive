bashlive 
========

<img alt="" src="http://2webapp.com/bashlive/bashlive.png" style="height:1em"/>

BASHLIVE is bashcommunitysnippetfunctionframeworkcoderepository-tool for bashhackers.
speedupyourdevelopment,byfacilitatinginsertionofonlinecommunitysnippets,librariesandframeworks.
BASHLIVEisthestartingpointforbashshellscripting,andpossiblyotherlanguagestoo.

in case you didnt follow that, check the link below:

Demo / Usage / Info
===================

See the [website](http://www.bashlive.com)

Run tests 
=========

    source bashlive
    source tests/*

More tests to come

API functions / snippets
========================
see [https://github.com/coderofsalvation/bashlive.repo](https://github.com/coderofsalvation/bashlive.repo) 

Example applications
====================
see [https://github.com/coderofsalvation/bashlive.examples](https://github.com/coderofsalvation/bashlive.examples)

The scope of bashlive
=====================
* bash only
* #interactive: Easily search and source online functions and snippets, and transpile (bake-feature) it into bash.
* #familiar: make it easy for newbies to get what they want ( they would search 'substr' instead of knowing ${foo:1:4})
* #superset-of-shell commands: like coffeescript for nodejs.

Bashlive is sourced when starting a terminal, so you can immediately go ahead and never have
to open a browser to search for some snippets.

ROADMAP bashlive
================

This is a 'chaos' roadmap, which means it doesnt need to follow particular order to keep things fun and flexible.
The issuetracker and the community can ofcoarse vote for- against these things.

* [bashlive] optimize, cleanup and test the bashlive-script (code became already a bit messy)
* [bashlive] configuration-file ~/.bashlive for custom behaviour (the automatic sourcing of the webpipe-script should be defined here)
* [bashlive] introduce a downvoting mechanism for snippets for core api-snippets
* [bashlive] improved security concerning updating & directly sourcing bashcode
* [bashlive.examples] more application examples in https://github.com/coderofsalvation/bashlive.examples
* [bashlive.repo] authentication functions: oAuth1, oAuth2 for easy integration of social services e.g.
* [bashlive] snippethub: live api searchqueries to commandlinefu.com e.g.
* [bashlive] bash-builtins in c for fast json- xml- processing

License
=======

Licensed under the AGPL license
Copyright © 2014 Leon van Kammen

For support see the issuetracker
