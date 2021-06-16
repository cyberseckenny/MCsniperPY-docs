---
description: What is offset in MCsniperPY?
---

# Offset

## What is offset?

Offset is simply how early _MCsniperPY sends requests_ and is measured in milliseconds. Because of factors like API lag and ping, sent requests are not received instantly by Mojang's API. Offset is used to compensate for this delay, and fine-tuning your offset is **crucial** to becoming a successful sniper. 

Usage of a VPS can be very beneficial when sniping. When compared to your personal computer, VPSes have a much stabler connection and (typically) lower ping. The better your connection, the easier it is to calculate an accurate offset. If you are interested in a VPS, [Digital Ocean](https://www.digitalocean.com/) and [Vultr](https://www.vultr.com/) are two recommended options. Additionally, Kqzz has created a [video](https://www.youtube.com/watch?v=-y2ucB6FYq8) of how to install MCSniperPY onto a VPS running `Ubunutu 20.04`. Make sure to look in the description for two free VPS referral links!

{% hint style="info" %}
Offset is the new name for "Custom Delay" from the old MCsniperPY version.
{% endhint %}

## How do I find an offset that works for me?

While finding an offset is now fairly easy, it still requires some manual tweaking. Start by running MCsniperPY `offset-test --aim-for .1` in your terminal. After a little bit it should say `[success] <offset> is a good offset!` Start with that offset and tweak based on if you're early or late. Compare the droptime of the name to the time of the requests. if you are late, then that means your offset is too low. if you are early, that means your offset is too high. Keep tweaking until you find something that works for you!

