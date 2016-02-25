---
layout: post
title: Get retain count in ARC mode
categories: [memory management]
tags: [retaincount]
fullview: true
comments: true
---

```
NSLog(@"Retain count is %ld", CFGetRetainCount((__bridge CFTypeRef)myObject));

```