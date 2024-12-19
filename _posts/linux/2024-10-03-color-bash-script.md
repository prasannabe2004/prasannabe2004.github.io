---
title : Color logs in bash script
layout : post
category : linux
date: 2024-11-03 19:05:32 +5:30
comments : true
google_adsense: true
excerpt : Learn to color log in bash script
keywords : 
toc : true
published: false
---
## Introduction

Color log your bash script


```bash
#!/bin/bash
clear
echo -e "33[1m Hello World"
# bold effect
echo -e "33[5m Blink"
# blink effect
echo -e "33[0m Hello World"
# back to normal
echo -e "33[31m Hello World"
# Red color
echo -e "33[32m Hello World"
# Green color
echo -e "33[33m Hello World"
# See remaining on screen
echo -e "33[34m Hello World"
echo -e "33[35m Hello World"
echo -e "33[36m Hello World"
echo -e -n "33[0m"
# back to normal
echo -e "33[41m Hello World"
echo -e "33[42m Hello World"
echo -e "33[43m Hello World"
echo -e "33[44m Hello World"
echo -e "33[45m Hello World"
echo -e "33[46m Hello World"
echo -e "33[0m Hello World"
```
