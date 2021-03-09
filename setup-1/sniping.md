---
description: Start sniping with MCsniperPY!
---

# Sniping

## Pre-snipe

Before you start sniping, add your accounts to the accounts.txt file. Just open the accounts.txt file through your favorite program such as notepad or nano. The format for accounts.txt should be in the file, but in case it's not it is show below in the code block.

{% hint style="info" %}
accounts.txt is located in the directory you initialized mcsniperpy in \(see previous page\). 
{% endhint %}

```
# You can comment out lines (the sniper ignores them) by prefixing them with a hashtag #
# If you have security questions, then the format should look like as shown below:
email:password:answer:answer:answer
# Note: replace all of those answer's with the actual answers to your security questions.

# If you don't have security questions the format will look like this:
email:password

# IMPORTANT!!! If there is a colon in your email or password THIS WILL NOT WORK.
```

Awesome! Now that you've put your account\(s\) in the accounts.txt file it's time to configure the sniper to your liking. Just look for a file named `config.ini` in the same folder / directory as your accounts.txt, and open it with a text editor \(notepad, or something else\). You can edit the values to your liking.

## Sniping

Now that you've got everything setup, it's time to try a snipe! You can start the sniper with one simple command! Just run the command shown below, enter in the necessary values \(i'll cover offset later; it's the same as delay btw\), press enter, and wait for the name to drop! Hopefully you get the name 🤞

```text
mcsniperpy snipe
```



