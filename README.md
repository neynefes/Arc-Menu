<img src="https://github.com/LinxGem33/Arc-Menu/blob/master/screenshots/avatar.resized.png?raw=true" alt="Logo" align="left" /> Arc Menu
======

### The new applications menu for Gnome 3.

Arc Menu is a Gnome shell extension designed to replace the standard menu found in Gnome 3 this applications menu extension leverages some of the work from [Zorin OS menu](https://zorinos.com/)., some of the added benefits of the Arc Menu extension is the long awaited search functionality as well as quick access to files on your system and also the current logged in user along with quick access to the software centre and system settings and other features which can be accessed from the settings menu.
##
![](https://github.com/LinxGem33/Arc-Menu/blob/master/screenshots/browser.png?raw=true)
##

### What's next for Arc Menu?

My first initial priority was to get this extension stable enough to upload to extensions.gnome.org as this was a menu baked into the Zorin OS operating system so it had to be ported to work with the gnome shell eco system, now the first stage of development is over features are now being added and I'm pleased to announce a new member of the team ([lexruee (Xander)](https://github.com/lexruee) and now a lead developer in the design and development of this extension hopefully more features are planned for future development and a lot has already been implemented.

##
|Arc Menu integrated with Dash-to-Dock|Arc Menu integrated with Dash-to-Panel|
|:-----:|:-----:|
|![](https://github.com/LinxGem33/Arc-Menu/blob/master/screenshots/apm3.png?raw=true)|![](https://github.com/LinxGem33/Arc-Menu/blob/master/screenshots/apm5.png?raw=true)|
|Click image to enlarge|Click image to enlarge|

##

### Installation

You can now install this extension from extensions.gnome.org as a one click install just click on the link below
> [One Click Install](https://extensions.gnome.org/extension/1228/arc-menu/)

##
### Packages
Awaiting packagers

##
### Manual Installation (for testers & enthusiasts)
Probably, the simplest way to install Arc Menu is using **git**, **make** and **gnome-shell-extension-tool**.
So, if you have installed git, make and gnome-shell-extension-tool, you can proceed as follows.

1) Clone the repository via the git-clone command and change to the Arc-Menu directory:
```
git clone https://github.com/LinxGem33/Arc-Menu.git
cd Arc-Menu
```

2) If you have already installed Arc Menu, then please remove the existing installation via:
```
make uninstall
```


3) Install it via:
```
make install
```

4) Enable or disable the extension via:
```
make enable
```

```
make disable
```

5) Logout from the current GNOME session and login again for the changes to take effect. Alternatively, you can restart the GNOME Shell with:
```
Alt + F2 and enter 'r' (without quotes).
```

##
### Bugs
#### Bugs should be reported [here](https://github.com/LinxGem33/Arc-Menu/issues) on the Github issues page.

Please note that without any information about your system, the Arc Menu Team can only speculate what the problem is.
So, please provide us information about your GNU/Linux distribution and the GNOME Shell version. Otherwise, we are not able to try and solve your problem.

##

#### In summary, it is considered good practice to create bug reports with the following information:

* Problem description

* Information about your distribution. Use the command `lsb_release -a` to retrieve information about your distribution.

* GNOME Shell version. Use the command `gnome-shell --version` to retrieve information about your Shell version.

* Logs from the systemd journal. Use the command `journalctl /usr/bin/gnome-shell -f -o cat` to log the occurrence of the bug.

##
### License & Terms ![](https://github.com/LinxGem33/IP-Finder/blob/master/screens/Copyleft-16.png?raw=true)

Arc Menu is available under the terms of the GPL-2.0 license See [`COPYING`](https://github.com/LinxGem33/Arc-Menu/blob/master/COPYING) for details.

## 
### Top Developers on the Project

This section is reserved for those who have contributed a great deal to the project with their time skill and patience with a big thank you for giving back to the community with their selfless acts of helping.

> “There is a desire within each of us,
in the deep center of ourselves
that we call our heart.
We were born with it,
it is never completely satisfied,
and it never dies.
We are often unaware of it,
but it is always awake.
##
|Ranked :trophy:|Developer Name|Profile / Description|
|:-----:|:-----:|:-----:|
|:heavy_check_mark: |[lexruee (Xander)](https://github.com/lexruee)|Programmer, Tinkerer, Single Board Computer and GNU/Linux enthusiast.|

##

### Credits

This extension leverages some of the work from [Zorin OS menu](https://zorinos.com/).

Additional credits: This extension also leverages the work from [Giovanni Campagna ](https://git.gnome.org//browse/gnome-shell-extensions) gnome Applications Menu used in [Gnome 3](https://www.gnome.org/) to allow the menu to be embedded in the Gnome main panel.
##
### Pull Requests

#### Thanks to the following people for contributing via pull requests:

- @[fishears](https://github.com/fishears/Arc-Menu) (1) compiling the schema's (2) Added suspend button and re-order buttons
- @[JasonLG1979](https://github.com/JasonLG1979/Arc-Menu)  (1) menu style fix, (2) Asynchronously set an icon and handle errors
- @[lexruee](https://github.com/lexruee/Arc-Menu) (1) Added the shortcut 'Tweak Tool' (2) shortcut for opening the trash (3) Implement "super key/keybinding" feature and "disable/enable activities hot corner (4) Implement the menu-position-feature (5) Make file (6) Move the logic for handling settings changes in controller.js (7) Move common constants in constants.js (8) Refactor helper.js (9) Refactor some parts in menu.js (10) Implement the basic GUI option for changing the menu button text and the menu button icon (11) Update the schema file to include the new settings options (12) Add the file am.js, which provides customized GTK GUI elements for the prefs.js file (13) Replace author lexruee with Alexander Rüedlinger
- @[itmitica](https://github.com/itmitica) (1) icon symbolic

#### Bug Fixes: 

- @[JasonLG1979](https://github.com/JasonLG1979/Arc-Menu) (1) menu style fix
- @[lexruee](https://github.com/lexruee/Arc-Menu) (1) correctly restore the Activities button

#### Translations:

|Contributor|Language|Implimented|Contributor|Language|Implimented|
|:-----|:-----|:-----:|:-----|:-----|:-----:|
|@[h3r0n](https://github.com/h3r0n)|Italian|![ti](https://user-images.githubusercontent.com/19158615/27998683-9dd48cd0-650a-11e7-87c3-0ac3256ae574.png)||French|
|@[pkomur](https://github.com/pkomur)|Polish|![ti](https://user-images.githubusercontent.com/19158615/27998683-9dd48cd0-650a-11e7-87c3-0ac3256ae574.png)||Arabic|
|@[danielstuart14](https://github.com/danielstuart14)|Brazilian portuguese|![ti](https://user-images.githubusercontent.com/19158615/27998683-9dd48cd0-650a-11e7-87c3-0ac3256ae574.png)||Chinese|
|@[zakkak](https://github.com/zakkak)|Greek|![ti](https://user-images.githubusercontent.com/19158615/27998683-9dd48cd0-650a-11e7-87c3-0ac3256ae574.png)||Spanish|
|@[mrprobot](https://github.com/mrprobot)|German|![ti](https://user-images.githubusercontent.com/19158615/27998683-9dd48cd0-650a-11e7-87c3-0ac3256ae574.png)||Hindi|
||Portuguese|||Bengali||
||Russian|||Japanese||
||Swedish|||Dutch||
