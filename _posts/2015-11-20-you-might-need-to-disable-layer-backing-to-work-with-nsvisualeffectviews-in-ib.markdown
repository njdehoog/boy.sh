---
layout: post
title:  "You might need to disable layer backing to work with NSVisualEffectViews in IB"
date:   2015-11-20 13:27:00 +0100
---

Found yourself unable to move around (or even freakin' select) elements on a layer backed `NSVisualEffectView`?

Just toggle the Core Animation Layer checkbox in Interface Builder and voilà, all fixed. Oh and everything turns red obviously, because `NSVisualEffectView`s need layer backing.. 👍

![Interface Builder showing a red NSVisualEffectView](/assets/blog/Screen_Shot_2015-12-01_at_13.31.21.png)
