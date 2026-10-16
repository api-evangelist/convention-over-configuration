---
title: "Better ACL S3 control and more"
url: "https://rubyonrails.org/2026/10/9/this-week-in-rails"
date: "2026-10-09"
author: "Wojtek"
feed_url: "https://rubyonrails.org/feed.xml"
---
Hi, Wojtek here. Let’s explore this week’s changes in the Rails codebase. Stop setting the public-read ACL on S3 uploads for services configured with public: true Bucket owner enforced is now both the default and the recommended S3 object ownership setting, and rejects any request that specifies an ACL.
