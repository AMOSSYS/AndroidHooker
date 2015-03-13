Hooker: Automated Dynamic Analysis of Android Applications
==========================================================

Description
===========

Hooker is an opensource project for dynamic analyses of Android applications. This project provides various tools and applications that can be use to automaticaly intercept and modify any API calls made by a targeted application.

It leverages Android Substrate framework to intercept these calls and aggregate all their contextual information (parameters, returned values, ...). Collected information can either be stored in a distributed database (e.g. ElasticSearch) or in json files.

A set of python scripts is also provided to automatize the execution of an analysis to collect any API calls made by a set of applications.

Repository
==========

AndroidHooker is available on [https://github.com/AndroidHooker/hooker](https://github.com/AndroidHooker/hooker).