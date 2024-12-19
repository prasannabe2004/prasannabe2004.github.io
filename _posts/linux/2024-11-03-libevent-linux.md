---
title : Libevent in Linux
layout : post
category : linux
date: 2024-10-03 19:05:32 +5:30
comments : true
google_adsense: true
excerpt : Learn how to use libevent in linux using C program
keywords : 
toc : true
---
## Introduction

The libevent API provides a mechanism to execute a callback function when a specific event occurs on a file descriptor or after a timeout has been reached. Furthermore, libevent also support callbacks due to signals or regular timeouts.
libevent is meant to replace the event loop found in event driven network servers. An application just needs to call event_dispatch() and then add or remove events dynamically without having to change the event loop.


```c
#include
```
