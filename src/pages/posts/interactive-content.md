---
layout: "../../layouts/BlogPost.astro"
title: "UnderDog Devs css-3"
description: "a underdog devs challange"
publishDate: "12 Sep 2021"
followMe:
  username: "xNikkoTx"
  href: "https://twitter.com/xNikkoTx"
heroImage:
  src: "/assets/blog/css-4.png"
  alt: "underdog devs css challange"
setup: |

  import FollowMe from "../../components/FollowMe.astro"
---

<FollowMe username={frontmatter.followMe.username} href={frontmatter.followMe.href} />


