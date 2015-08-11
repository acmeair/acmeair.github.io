---
layout: post
title:  "acmeair-driver has moved!"
date:   2015-08-11 16:38:07
categories: repositories
tags: acmeair-driver
---
The  acmeair-driver module which used to be in the [acmeair](https://github.com/acmeair/acmeair) repository has moved to a new location! 
A new [acmeair-driver](https://github.com/acmeair/acmeair-driver) repository was created for the workload driver. The same workload driver is intended to be used with both the Java and the Node.js implementations of Acme Air.  Since the Node.js Implementation of Acme Air was split in to its [own repository](https://github.com/acmeair/acmeair-nodejs), it made sense to do the same thing for the workload driver.  In addition, the JMeter scripts and supporting java classes were moved to an acmeair-jmeter module, so that eventually additional scripts of the acmeair workload might eventually be created (Like [Gatling](http://gatling.io), for example..)

