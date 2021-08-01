---
title: What is DNS and why should you care
description: A brief introduction to DNS, Domain Name System and how it works. 
date: 2021-07-25
tags: web-dev
layout: layouts/post.njk
---

The Domain Name System is like the phone book of the internet.
Human readable URLs or domain names like `www.google.com` are like home addresses. This URLs are mapped to IP addresses such as `172.16.254.3 ` which are locations of servers which host the website. 

A server in simple terms is just a computer which is connected to the internet and has the files of a website. When you visit a website, the DNS maps the URL to the IP addresses of the computer that that hosts the website.

It queries the local machine first for address. If the local machine is empty it then queries a special kind of server called Recursive Resolver. It is recursive because it makes multiple requests to other servers. You can think of it as giving out different phonebooks to a classroom of students and asking them to search for a specic person's phone number. The students in this example are like other servers. They will do this at the same time and one of them will be able to find it. That is how Recursive Resolver works in a nutshell.

The other servers that Recursive Resolver queries are called TLD servers or Top Level Domain servers. They store data of top level domains such as .com, .net or .io. The Resolver gets a response of the authoritative name server's IP address which is the server of the requsted website.
This is sent back to the client and is cached for future use. All this happens happens in seconds despite sounding very complicated.happens

When you buy a domain name from companies such as BlueHost or TrueHost, it is handled by a Registrar. The record is then maintained by a Registry who stores your DNS settings and distributes them to other DNS servers around the world.

After acquiring a domain name you will be asssigned a Zone File which you can use to configue your domain settings. Every Zone has SOA, Start Of Authority Record that tell other dns servers who is in charge of that domain.
There is also the 'A' record. It means 'Address' and it maps or matches a domain or sub-domain to IP address of it's host.

In other cases we may want to redirect a domain to another domain on the internet instead of an IP address. In such case a CNAME or Canonical Name will be used to serve this purpose. 
Finally we have the NS or Name Server record. This is URL the internet can ping to find an IP address.
DNS is import to understand because when you plan on having a website you will need to acquire a domain name and using DNS is unavoidable. Unless you will relegate this task to a Web developer, it is fundamental to understand what DNS is and how it works.
This has been a brief overview of what Domain Name System or DNS is. 



