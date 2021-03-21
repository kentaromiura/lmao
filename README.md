# lmao

lmao fast bsd port installer
===

`lmao` is a script to ease the installation of BSDs ports, copy this script on your /usr/local/bin and then you can use it to install ports

eg:
```
cd /usr/ports/doas
lmao
```

What does this do
---

It tries to install as much dependencies as possible from the pkg pre-built after that it runs `portmaster` shortening build time, on my X230 installing kdbg takes only minutes compared to hours.

Requirements:
As this is a node.js script it only requires node pre-installed, portmaster will be installed by the script if missing.

`sudo pkg install node`
