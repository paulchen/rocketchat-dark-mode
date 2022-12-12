# rocketchat-dark-mode

> **An easy user-togglable dark mode for Rocket.Chat**

This repo was migrated for ease of collaboration from [my gist](https://gist.github.com/pbaity/73beb1dd11fdc8b90e4ee032f1b3f7de) which was a fork of [**chall8909**'s gist](https://gist.github.com/chall8908/c03dd6cc443cdb9cbb7034d441a1350d), to which this project is greatly indebted.

## Overview

[**dark-mode-toggle.js**](dark-mode-toggle.js) creates and adds a click handler for a dark mode toggle button. This toggle button lives in the toolbar at the top of the left-hand sidebar:

![Toggle dark mode on with moon icon](images/button-light.png)

And when dark mode is active:

![Toggle dark mode off with sun icon](images/button-dark.png)

[**dark-mode.css**](dark-mode.css) contains the styles which - y'know, make everything dark, like so:

![Dark mode in action](images/dark-mode.png)

## Installation

If you want to "install" this dark mode, here's all you need to do:

1. Be an administrator of your Rocket.Chat instance, or send these instructions to one and pester them to do it for you
2. Go to the **Administration** panel > **Settings** > **Layout**
3. Copy the contents of [dark-mode.css](dark-mode.css) into **Custom CSS**
4. Copy the contents of [dark-mode-toggle.js](dark-mode-toggle.js) into **Custom Script for Logged In Users** (third field) under **Custom Scripts**
5. Refresh your local Rocket.Chat instance (a server restart is _not_ required). You may need to clear your cache if using a web browser.

**NOTE:** This repo aims to keep the dark mode working for the latest stable release of Rocket.Chat. Older versions may or may not work.

Rocket.Chat version(s) | Branch to use
--- | ---
latest stable | master
5.0.0 - 5.3.5 | [**5.3.5**](https://github.com/pbaity/rocketchat-dark-mode/tree/5.3.5)
4.7.5 - 4.8.2 | [**4.8.2**](https://github.com/pbaity/rocketchat-dark-mode/tree/4.8.2)
4.2.3 - 4.7.4 | [**4.7.4**](https://github.com/pbaity/rocketchat-dark-mode/tree/4.7.4)
4.0.0 - 4.2.2 | [**4.2.2**](https://github.com/pbaity/rocketchat-dark-mode/tree/4.2.2)
3.11.3 - 3.18.3 | [**3.18.3**](https://github.com/pbaity/rocketchat-dark-mode/tree/3.18.3)
3.9.2 - 3.11.2 | [**3.11.2**](https://github.com/pbaity/rocketchat-dark-mode/tree/3.11.2)
3.8.0 - 3.9.1 | [**3.9.1**](https://github.com/pbaity/rocketchat-dark-mode/tree/3.9.1)
3.4.0 - 3.7.2 | [**3.7.2**](https://github.com/pbaity/rocketchat-dark-mode/tree/3.7.2)
3.2.2 - 3.3.3 | [**3.2.2**](https://github.com/pbaity/rocketchat-dark-mode/tree/3.2.2)


## Contributing

If you encounter any problems with this dark mode plugin, please open an issue - or better yet, fix it and open a pull request.

See [the contributing guidelines](./CONTRIBUTING.md).
