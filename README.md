# Installation

## MCsniperPY rewrite installation

{% hint style="danger" %}
This does not function yet!
{% endhint %}

```text
# Run these commands to install the sniper
pip install -U mcsniperpy
mkdir sniping
cd sniping
mcsniperpy init
# *Open config.ini and accounts.txt and add your accounts*
# You can now run mcsniperpy from **any** directory
# run the mcsniperpy command for a list of commands
mcsniperpy
```

## MCsniperPY development installation

Installing MCsniperPY for development is fairly simple.

```
# Run these commands in order. You need git and python installed.
git clone https://github.com/MCsniperPY/MCsniperPY.git
cd MCsniperPY/
git checkout recode
pip install -e .
# You now have acccess to the mcsniperpy shell command
mcsniperpy ping
mcsniperpy --help
```

{% hint style="info" %}
 This installation is only for development. If you want an easier installation check above.
{% endhint %}



