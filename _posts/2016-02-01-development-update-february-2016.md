---
title: 'Development update February 2016'
excerpt: "So... It's been a while since we last posted about the development of Anchor and I thought we owe you; the community, an update on our progress, what's new and what's next."
---

_So... It's been a while since we last posted about the development of Anchor and I thought we owe you; the community, an update on our progress, what's new and what's next._

**Recent Updates**

First of all I'd like to mention the recent updates we've made to the CMS. We've been integrating a lot of community provided features and bug fixes over the past year or so. Which has all built up to what has become `0.12.*`, the latest release of Anchor (as of Feb 2016).

In this version you will see an improvement in the way we handle the storage of the posts and pages; removing the need to parse the markdown on every request. This alone produces a significant improvement in performance. You will also see fixes when it comes to XSS security, drag & drop image uploads, custom field image uploads and other site settings. Built in support for composer is included right out of the box, we use it to pull in some key dependencies which keep your blog secure. It also allows us to post Anchor on packagist.org, this dramatically improves the installation process.

For example: `composer create-project anchorcms/anchor-cms anchor` will download and setup Anchor's dependencies in a directory called `anchor`; yes, it's that easy!

**What's Next?**

Now that we've got that out of the way let's talk about the future of Anchor. As you may already know, we've been working on 1.0 for many years now (forever, I know). We've gone through a few design iterations and framework changes, but we're finally getting there. We want to make sure it's everything you, the community, have asked for. Including some of the more popular feature requests such as: plugins, user roles, an image gallery... the list goes on.

We'd love to give a solid ETA but to be honest: we all have full-time jobs and aren't able to spend a whole lot of time on this project, and with very little help from the community on version 1.0, development is slow.

If you wish to receive more regular updates then please don't hesitate to follow us on [Twitter](https://twitter.com/AnchorCMS). And head on over to our [Github](https://github.com/anchorcms) to give us a helping hand.
