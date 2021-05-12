---
description: How to download MCsniperPY
---

# Installing the sniper

{% hint style="info" %}
This is the installation for the **recode**, not the main version of the sniper.
{% endhint %}

## MCsniperPY Installation \(Windows\)

Before you begin, make sure you have Python and Pip installed. To check if you have these installed run `py -V` and `py -m pip -V`. If you don't have these installed go to the [python website](https://www.python.org/downloads/) and [download](https://www.python.org/downloads/) the latest version of Python. After that you can run this command in cmd to install MCsniperPY.

```text
py -m pip install mcsniperpy
```

Many windows users will have to run `py -m mcsniperpy` instead of the `mcsniperpy` command in the future sections of these docs. you'll want to **always do this or it won't work.**

## MCsniperPY Installation \(Linux and MacOS\)

Before you begin, make sure you have Python and Pip installed. To check if you have these installed run `python3 -V` and `python3 -m pip -V`. If you don't have these installed google "[How to install python and pip for &lt;insert your operating system here&gt;](https://www.google.com/search?q=how+to+install+python+and+pip+YourOS)". After that you can run this command to install MCsniperPY.

```text
python3 -m pip install mcsniperpy
```

If you get a message saying something like `WARNING: The script mcsniperpy is installed in '/home/$USER/.local/bin' which is not on PATH.` then run the command below. If that fails, try replacing `bashrc` with `zshrc`.

```text
echo "PATH=$PATH:/home/$USER/.local/bin" >> ~/.bashrc && source ~/.bashrc
```

