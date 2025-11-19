---
description: because we dont think that old geezers know what the kids need
---

# Juvenile Edition

### What is the MA Juvenile Edition?

basically this edition of the software will be modified to work with internal policies we have been working on and getting opinions on for things related to protection and development of Juveniles. This is in part based on our own experiences, our research, and extensive knowledge that we have helping Juveniles with issues related to their mobile devices we do some talking about this here [phones-are-good.md](../opinions/phones-are-good.md "mention")so go check that out



The modifications that we make to MA to create the Juvenile Edition are as follows:

#### Removal of the App Store

we remove the app store as the first step in creating the Juvenile Edition, as we feel that there are many apps availible on the app store that should not be around childeren, even with our extensive and effective moderation procedures.



#### Removal of the ability to install Apps manually

there is still a background daemon that can manage the installation and updating of apps, as our own apps needs OTA updates that happen more often then updates to the core operating system, We just remove the ability for non system-signed daemons to call and use this feature, and related APIs and fuctions. This is to further seal our removal of the App Store and block side loading of applications.



#### DNS Blocking Modifications

while we still use the same software for DNS blocking on the Juvenile Edition, we change the ability to control it so that it is controlled by a remote server handled by the Guardian of the Juvenile.
