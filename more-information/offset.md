---
description: What is offset in MCsniperPY?
---

# Offset

## What is offset?

Offset is simply how early _MCsniperPY sends requests_.  OFfset is measured in milliseconds. This is used to compensate for API lag and ping.

{% hint style="info" %}
Offset is the new name for "Custom Delay" from the old MCsniperPY version.
{% endhint %}

## How do I find an offset that works for me?

While finding an offset is now fairly easy, it still requires some manual tweaking. Start by running MCsniperPY `offset-test --aim-for .1` in your terminal. After a little bit it should say `[success] <offset> is a good offset!` Start with that offset and tweak based on if you're early or late. Compare the droptime of the name to the time of the requests. if you are late, then that means your offset is too low. if you are early, that means your offset is too high. Keep tweaking until you find something that works for you!

