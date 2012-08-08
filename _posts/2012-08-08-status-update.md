---
layout: post
title: "Status Update"
description: ""
category: 
tags: []
---
{% include JB/setup %}

Here is today's status update.

 * nginx
   * 31527183: added the code to the configs but it still doesn't work
 * varnish
   * 33959065: fixes option requests to autosuggest
   * 28018635: handles autosuggest with no query
 * unstarted varnish
   * 32926461: retry on 503 (grace)
   * 32034605: Integrate with 3scale using asynchronous calls through varnish.

The ngix changes still didn't work, so I need some more research on those.

The varnish tasks about autosuggest have been added.  But I didn't reload the config 
yet because I want to find out more about the 3scale stuff before I do anything more.  

