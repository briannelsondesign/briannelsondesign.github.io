---
layout: post
title:  "Change the pane width in Github Atom "
date:   2014-04-07
categories: blog
---

I'm loving Github's [Atom text editor](http://atom.io) but there are a few things here and there that need some adjustment.

Here's a quick and dirty way to set a custom width for split panes. Add this to your Atom stylesheet:

```
.pane-row .pane:first-child {
  flex:10%;
}
```

You can substitute `:first-child` with `:last-child` depending on which pane you want to widen, and change the `flex` value to suit your needs.

It should be mentioned that this will affect any multi-pane layout. You can expand upon it with `:nth-child` to your heart's content, but I only ever need two panes at a time, for the most part.

Happy coding.
