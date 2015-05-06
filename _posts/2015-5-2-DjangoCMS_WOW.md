---
layout: post
title: DjangoCMS WOW
tags: django
---

[WOW](http://mynameismatthieu.com/WOW/).js is a javascript framework to allow certain elements to animate when they are revealed. The [website](/robo_web) for Robotix 2016 that is being developed over ```Django CMS``` required ```WOW.js``` to add animation. ```Django CMS``` on the other hand wants us to create plugins to add such effects to a page. This led to the development of a new plugin for Django CMS, the [djangocms-wow](https://pypi.python.org/pypi/djangocms-wow).  

This plugin allows user to apply custom animations from a list of 30 preset animations to any element on a page.  

It took me an entire night to get it working. I eventually attained over 95% coverage with tests that worked fine for ```Django CMS==3.0.x``` but failed for ```DjangoCMS==3.1.x```. However, the plugin was seen to perform consistently well over all versions of ```DjangoCMS>=3.0```.  

The [website](/robo_web) for Robotix 2016 will see the development of many such plugins tailored for our use. Keep watching this space for more updates.