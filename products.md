---
title: Products
layout: base
---

We're pragmatic about the products we use and build. There's lots of things we use and a couple of things that we've built - because we've needed to scratch an itch. Learn more here.

## Stackbutton

Stackbutton is the center of DevOps, a place to build, evolve and monitor your unique DevOps stack. 
Got a new project?
Stackbutton lets you standup your DevOps stack in minutes:
> The team, communications, the repository, issue tracking, continuous integration/delivery, hosting, promotion and everything else.
Once Stackbutton has created your stack, it becomes the hub to monitor and access all of the components of your projects stack.
Notifications let you know the pace of your projects - commits, builds, deployments, promotions. Stackbutton is the place to go to know it all.

## Rube Goldberg JSON Data Generator 

Generating data is difficult. Getting it in a format that's easy for your application to ingest is even harder. But it's absolutely necessary. You can't create a sufficient development environment for your developers and testers without a way to generate good, production like data.
Editing complex JSON is too a painful. Copying data from production - even if you mask it - is a security risk. Doing nothing will result wreak havoc with your code quality.
We've found a better way.  Sure, it's a [Rube Goldberg](:https://en.wikipedia.org/wiki/Rube_Goldberg) machine ("RG" - that's what we call it), but it works, and it's phenomaly productive once you get the hang of it. Here's what we do:

* Start with Excel - the place everyone uses to manage data.
* Make user friendly data entry tabs - with formats anyone can deal with. One for each JSON file nesting level.
* (The tricky part - until you get used to it) Use Excel formulas as neede to put the people friendly data onto JSON-friendly (and technically precise) Excel tabs that will be exported into CSVs. The resulting CSVs hold isolated JSON data as a series of flat files. We have a pretty cool Excel macro that generates all of the flat files for us.
* (Here's the magic) - we use our Rube Goldberg CSV to JSON converter to merge the CSV into arbitrarily complex JSON structures. Simple as that.

How complex?  Really complex. Here are some examples that were created in a matter of hours.  Imagine trying to create that data in a text editor?
