---
layout: work
title: Email Marketing
categories: work
published: true
---

One of the projects we've been working on at Kickserv is an email marketing and engagement application. A key piece to the customer experience is setting up email campaigns.

After some back and forth with customers, we found that providing them with a "psuedo-WYSIWYG" interface resulted in the best outcome. We designed the content creation form to mimic the display of the emails as they'd be seen by the recipient.

[![Email Design Form]({{ site.url }}/assets/email-form.png)]({{ site.url }}/assets/email-form.png)

One of the features that seemed really simple in the early stages of the design process was our Merge Tags, which provides the user a simple way to include variable data in their emails. We wanted to show users the data they could use *visually*, instead of forcing them to use an obscure code or set of special brackets, like `[[customer_first_name]]`. This didn't seem incredibly friendly to us.

So, our front end master Josh worked some magic with `contenteditable` and we implemented a design that has been received quite well so far.

[![Merge Tags Example]({{ site.url }}/assets/merge-tags.gif)]({{ site.url }}/assets/merge-tags.gif)
