---
description: How to initialize MCsniperPY to be run
---

# Initialization

## How initialization works

{% hint style="info" %}
This is just explaining how the backend things work. You can move on to the next heading if you're not interested!
{% endhint %}

Something that MCsniperPY does differently than other snipers is it's method for loading accounts and your configuration. Rather than requiring you to be in a certain directory with your config and accounts file, MCsniperPY requires you to initialize it in a directory which will act as your "home" directory \(not to be confused with your system's home directory\). When you run `mcsniperpy init`, MCsniperPY does a lot of stuff under the hood. It starts by making \(or not, if it already exists\) a directory in `$HOME` or `%userprofile%` called `.mcsniperpy` and putting a "backend" configuration file, which contains a path to your current working directory \(which is now your "home" directory for MCsniperPY\) in that directory. This is where MCsniperPY looks to figure out where your accounts and config are. If you move or delete this directory or config file your sniper will not function until you run `mcsniperpy init` again. After that, it makes your config and accounts file in your current directory. Whenever you run the `mcsniperpy snipe` command from now on it will check that config file to find your accounts and main config file.

## Initializing Your Sniper

Initializing your sniper is very simple. It's the same no matter what platform you're on. All you do is run the command shown below in a terminal / command prompt. It should do everything mentioned in "How Initialization Works."  to sum up that section, it makes a config and accounts file for you and then stores the path to both of those files so you don't have to worry about what directory you're in again! Now that you've run that command you can move on to the next section. 

```
mcsniperpy init
```



