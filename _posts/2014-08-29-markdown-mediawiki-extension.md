---
layout:     post
title:      Markdown Mediawiki Extension
date: 2014-08-29 11:47:47.000000000 -05:00
categories:
- Programming
tags: []
status: publish
type: post
published: true
meta:
  _edit_last: '1'
author:
  login: Blake
  email: contact@blakeharley.com
  display_name: Blake
  first_name: Blake
  last_name: Harley
redirect_from:
  - /2014/08/markdown-medawiki-extension/
---

When it came time to get a wiki running at work to document several projects, Mediawiki
was the “obvious choice.” Unfortunately, the state of extensions over there is a very sad
state. Numerous extensions have not been updated in years and most are poorly documented.

Most notably, there was a distinct lack of Markdown syntax support. You’d figure with
Markdown being all the rave these days, **someone** would have made an extension for this.
The only thing I could find was [this extension][MarkdownSyntax]. To my surprise, the
extension didn’t work.

To get things running around here, I quickly threw together a Markdown extension for
Mediawiki: [Markdown].

It’s a little rough around the edges, and there are a few
[usability issues][Github issues]. Feel free to use it though.

**Bonus** I also made a [HideSubpageParents] plugin. Enjoy!

[MarkdownSyntax]: http://www.mediawiki.org/wiki/Extension:MarkdownSyntax
[Markdown]: https://github.com/bharley/mw-markdown
[Github issues]: https://github.com/bharley/mw-markdown/issues/1
[HideSubpageParents]: https://github.com/bharley/mw-hidesubpageparents