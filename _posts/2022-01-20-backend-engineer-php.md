---
layout: post
title: "Backend engineer, PHP"
tags: Jobs
excerpt_separator: <!--more-->
---

![Team](/assets/bricks/1.jpg)
<br>

**TL;DR**   
**We want you to build our PHP/Postgres backend, full-time, probably in Prague. We will get you challenge, opportunity and help. Great team, good money and stock options. You should have experience building backend. Clean code, testing, DDD, CQRS.**

<!--more-->

There's currently only one guy (actually [me]({{ site.baseurl }}/team#ondrej)) doing all the backend work, on top of leading the tech.
I need a partner!

Join our awesome [team]({{ site.baseurl }}/team)! We are scaling our engineering right now.
The infant hacky two years of Outfindo are over, we are reasonably sure about what we need to build now.

This is an **opportunity to do things the way you want, to learn a lot**, and to be part of the formative period of our company.
If you help us to make it, there's a lot in it for you as well.

## What we do

Outfindo helps people to find the right bike. We know all about a bike (including custom insights) and we know where to buy it. We
* build a product catalog from various sources, automating the whole process
* enhance the data to gain insight using classification based on expert know-how
* obtain availability data from shops/eshops and match them with our catalog
* build a marketplace where we help customers to find the right bike and to get it
* actively research and prototype new and fun ways of assistance for the customer to get product insight

See **[outfindo.cz](https://outfindo.cz)** and [outfindo.com](https://outfindo.com).

## What will you do

* take care of our backend codebase (15 kloc src, 10 kloc tests)
* implement changes to API for frontend features based on well-researched user stories by product manager [Adlo]({{ site.baseurl }}/team#adlo)
* work with PostgreSQL database
* set up integrations with 3rd party services
* participate on product decisions during early phases of dev process - we are not a [feature factory](https://cutle.fish/blog/12-signs-youre-working-in-a-feature-factory)
* pair-program and review code with [Ondřej]({{ site.baseurl }}/team#ondrej) so that you can learn from each other
* refactor the code regularly to eliminate tech debt, delete unused code often (so satisfying! :)
* ship small changes with feature toggles so that we can deploy continuously
* participate on architecture decisions, propose new tech
* help set up the infrastructure
* participate in team activities - learning sessions, sharing experience, workshops

## What tech and practises do we use

* PHP 8.1 (readonly properties and enums FTW)
* Symfony 6 (but trying to be framework-agnostic)
* PHPUnit tests, both unit and integration/database, TDD approach when suitable
* static code analysis (PHPStan/Psalm)
* [Domain-driven design](https://martinfowler.com/tags/domain%20driven%20design.html), [CQRS](https://martinfowler.com/bliki/CQRS.html), [Value objects](https://martinfowler.com/bliki/ValueObject.html), [Hexagonal architecture](https://matthiasnoback.nl/2017/07/layers-ports-and-adapters-part-1-introduction/)
* read (and sometimes write) models using plain SQL instead of Doctrine
* PostgreSQL (managed on Digitalocean)
* Git, GitHub
* Digitalocean for hosting our system
* makefiles and shell scripts for task automation
* dockerized dev stack

## What we are starting or planning to do

These may be one of your first tasks:
* better data models on API, OpenAPI specs
* GitHub Actions CI pipeline (not needed for one-man show:)
* better monitoring
* GraphQL instead of REST-ish API for more data-driven endpoints
* Elasticsearch or similar tech for engine that powers our product catalog
* messaging, queues for asynchronous task processing
* split backend into more independent services (monolith is ok and preferred, but some functionality may need different tech stack)
* discoverability, better separation of layers, better error handling

## What do we expect from you

This position will suit you if you
* have previous backend coding experience with some of your code running in production
* see patterns around you, apply your experience to new problems
* want your code to be clean, readable and maintainable
* think about application architecture - separation of concerns and layers
* are able of abstract thinking, can solve problems with code
* want to fix things rather than wait for someone else to do it
* ask for help if you don't know what to do - we are ready to help you
* are not afraid of infrastructure - setting up services, know your way around Linux

It is ok to not be sure about some of these things. We are all learning along the way.

We will get along if you
* are open-minded, learning new stuff from others and on your own
* respect others' opinions
* care about your work when given the right challenge

## What do we offer

* money - not garage-startup money, not corporate-level money either, but we want you to be comfortable
* stock options for you to get what is yours when Outfindo gets successful
* all the help we can provide to get you going - let us know
* regular mentoring and leadership by [Ondřej]({{ site.baseurl }}/team#ondrej), can go both ways - we can all learn from each other
* stress-free work environment - there are no "crunches", no time estimates, no hard commitments to deliver changes at certain time
* monthly team events - bike in summer, climbing in winter, off-sites

We are based in Prague with office in Vinohrady.
Remote work is alright, but we prefer to see each other regularly to be effective and have some fun, more so after two years of Covid isolation.
We have comfy chairs, whiteboard, coffee machine and we love cookies.

**If this resonates with you let us know. We are ready to help you if you want to work with us.**

Write an email to [ondrej.bouda@outfindo.com](mailto:ondrej.bouda@outfindo.com) or grab a phone and call [Ondřej]({{ site.baseurl }}/team#ondrej) directly: +420724532118.
