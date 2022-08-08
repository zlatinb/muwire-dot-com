---
layout: wikipage
permalink: /nicknames.html
---
# Nicknames

Every MuWire user has a nickname.  The nickname is created by combining their chosen name with their unique cryptographic I2P address.

The nickname has two forms - short and full.  The short form is easier to read, and it looks like:
```
zlatinb@3k2gijdfdcuczkfypfddj4qsnnf744mj
```
The full form can be used to find them on the MuWire network.  For example, you can use the full form to browse the files they are sharing.  To do that, copy-paste the full nickname into the search field and press Enter.

Full nicknames are also used when logging into sites based on the [MuCats](https://github.com/zlatinb/mucats) code.

My full nickname is:
```
AQAHemxhdGluYiN~3G-hPoBfJ04mhcC52lC6TYSwWxH-WNWno9Y35JS-WrXlnPsodZtwy96ttEaiKTg-hkRqMsaYKpWar1FwayR6qlo0pZCo5pQOLfR7GIM3~wde0JIBEp8BUpgzF1-QXLhuRG1t7tBbenW2tSgp5jQH61RI-c9flyUlOvf6nrhQMZ3aoviZ4aZW23Fx-ajYQBDk7PIxuyn8qYNwWy3kWOhGan05c54NnumS3XCzQWFDDPlADmco1WROeY9qrwwtmLM8lzDCEtJQXJlk~K5yLbyB63hmAeTK7J4iS6f9nnWv7TbB5r-Z3kC6D9TLYrQbu3h4AAxrqso45P8yHQtKUA4QJicS-6NJoBOnlCCU887wx2k9YSxxwNydlIxb1mZsX65Ke4uY0HDFokZHTzUcxvfLB6G~5JkSPDCyZz~2fREgW2-VXu7gokEdEugkuZRrsiQzyfAOOkv53ti5MzTbMOXinBskSb1vZyN2-XcZNaDJvEqUNj~qpfhe-ov2F7FuwQUABAAHAAAfqq-MneIqWBQY92-sy9Z0s~iQsq6lUFa~sYMdY-5o-94fF8a140dm-emF3rO8vuidUIPNaS-37Rl05mAKUCcB
```

### Managing your identity

The cryptographic part of your MuWire identity is stored in a file called `key.dat` in the MuWire settings directory.  That directory is:
* on Windows `c:\Users\<username>\AppData\Roaming\MuWire\`
* on Mac `/Users/<username>/Library/Application Support/MuWire/`
* on Linux `$HOME/.MuWire/` (older versions) or `$HOME/.config/MuWire` (newer versions)`

It is a good idea to backup that file to a safe place.  If that file gets lost, your identity cannot be recovered.  Do not give that file to anyone else or they will be able to impersonate you.

The human-readable part of your identity (the nickname you choose) is stored in a file called `MuWire.properties`.  That file is in text format and you can edit it with any editor.  You can change your nickname and keep the cryptographic identity but that is not recommended because it will confuse others users.

### Moving to another computer

If you want to move MuWire to another computer and keep your identity, you should ideally copy everything from the settings directory to the new machine.  If you can't, copy at least `key.dat` so that your identity doesn't get lost.

Only one MuWire instance can run with a given identity at any time.  You can't have the same identity running on two computers simultaneously, if you try to do so MuWire will have trouble connecting to the network, searching for files, and will in general perform poorly. 

### Creating a new identity

To create a new identity stop MuWire, delete `key.dat` and start MuWire again.

### Multiple identities

If for whatever reason you want to have multiple identities, you need to create them manually and manage the `key.dat` files yourself.  To change your identity, stop MuWire, replace `key.dat` with the one for the new identity, and start MuWire.
