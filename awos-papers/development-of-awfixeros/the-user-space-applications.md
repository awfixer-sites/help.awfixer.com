---
description: and the weird optimizations and changes and things we did to make it work fast
---

# the User Space Applications

{% hint style="info" %}
if you think that AWFixerOS is anything like other operating systems you are wrong. just keep that in mind as you read though my chicken scratch
{% endhint %}

so the first thing that you should be aware of is that when you develop applications for AWFixerOS, once it has reached a full v1.0.0-stable release tag - you will have to use the AWOS ADK, which will be talked about in another section (and linked to when I get done with that/those page(s))

I have been playing around with the idea that we can integrate a few things together for security, speed, and general use purposes. This stemmed from the ideas I was working with for our AntiCheat and DRM software. We have strong opinons on both of those and have decided that we will develop version at the operating system level that do what they are supposed to, then banning other forms of it. When I was thinking about how to impliment this it occured to me that a similar way of binding software might be possible for our applications in the userspace.

When I was looking into this idea I found that the devs over at [Tauri](https://tauri.app/) had already begun to do something similar with their applciation setup
