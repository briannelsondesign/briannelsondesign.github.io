---
layout: work
title: Kickserv Onboarding
categories: work
published: true
---

Onboarding users has always been a bit of a challenge at Kickserv, so we began redesigning the process in June of 2015. The biggest issue we've had is that our customers simply don't have time to fill out form after form of information about their business. Some are trying out our software and don't want to set *everything* up before making a decision, so our goal with this redesign was to limit the amount of input by the customer and streamline the onboarding process.

[![Company Information]({{ site.url }}/assets/setup-1.png)]({{ site.url }}/assets/setup-1.png)

One way to limit a user's work is to try and pre-fill some of the information, if we can. When a customer fills in their business address, we look it up with a mapping API and return a geolocation. That allows us to set a time zone and locale. Of course, sometimes there might be mistakes, or a company's dispatch center may operate in a different time zone than its employees, so we allow the user to change it if they need to.

The second bit of information we attempt to predict is the Services a company offers. At Kickserv, we use Services to automate a number of processes throughout our app. For example, a plumber might create a "Toilet Repair" service with a typical cost and duration. We use that information to allow customers to request appointments based on the plumber's schedule.

[![Company Services]({{ site.url }}/assets/service-list-prefilled.png)]({{ site.url }}/assets/service-list-prefilled.png)

To make the creation of Services a little easier, we have a pre-filled list of industries and associated services, so a company can quickly populate their installation with appropriate information. If they need to edit our default list, no problem. And adding new services is simple.

[![Welcome Dashboard]({{ site.url }}/assets/dashboard-new.png)]({{ site.url }}/assets/dashboard-new.png)

Once a user confirms a base set of services to start from, they're all set. They can very quickly start using Kickserv to manage their business, or choose from a short list of options to enhance their experience. By guiding them through the setup process, we hope to get users on board as quickly as possible.
