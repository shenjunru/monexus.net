---
layout:     post
title:      "Weinre: remote debugging tool"
categories: JavaScript
tags:       [mobile, tools]
---
# Weinre: remote debugging tool

Today, i found a cool tool calls "weinre" when i google the solution of mobile
web debugging.

[Here is it.](http://people.apache.org/~pmuellr/weinre/)


## Introduction
Weinre is a debugger for web pages, like FireBug (for FireFox) and Web Inspector
(for WebKit-based browsers), except it's designed to work remotely, and in
particular, to allow you debug web pages on a mobile device such as a phone.

## Install
* install [node.js](http://nodejs.org)
* install weinre `npm install weinre`
* run it `weinre --boundHost -all- --httpPort 9090`
* browse <http://localhost:9090> in chrome or safari.
* now start debugging, follow the guide on that page.

![weinre](http://people.apache.org/~pmuellr/weinre/docs/latest/images/weinre-demo.jpg)
