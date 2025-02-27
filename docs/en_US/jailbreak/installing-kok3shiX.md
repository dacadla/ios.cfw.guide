---
lang: en_US
title: Installing kok3shiX
description: Guide to installing kok3shiX
permalink: /installing-kok3shiX
redirect_from:
  - /kok3shiX
  - /kokeshiX
pkgman: cydia
extra_contributors:
  - hopolapopola
---

kok3shiX is capable of jailbreaking every 32-bit iOS device on firmware version 10.3 up to 10.3.4.

Note that the kok3shiX jailbreak is not “persistent” (meaning it does not remain installed after a reboot). You will need to re-run the exploit after every reboot. You will be instructed on how to do this.

Due to how custom applications are installed to the device, in most cases you will need to reinstall the kok3shiX jailbreak application to your device every 7 days from your computer.

We will use Sideloadly to install the application to your device.

::: warning

kok3shiX is an Alpha, as a result you may potentially have more issues than you otherwise would. Backup your data before continuing.

Alternatively, you can follow <router-link to="/installing-h3lix">Installing h3lix</router-link> instead, though it does require more effort to jailbreak.

:::

## Downloads

<div class="custom-container tip" id="ifJailbreaksAppSigned"><p>
kok3shiX is currently signed at <a href="https://jailbreaks.app/legacy.html" target="_blank">jailbreaks.app</a> for easy installation without a computer.
</p></div>

- The latest version of [kok3shiX](https://dora2ios.web.app/kokeshiX.html)
- The latest version of [Sideloadly](https://sideloadly.io/)

## Installing the application

1. Open Sideloadly
1. Plug your iOS device into your computer
    - Make sure your computer is trusted and allowed to view the contents of your device
1. Drag and drop the kok3shiX `.ipa` file into Sideloadly
1. Enter in your Apple ID
1. Enter in your password
    - Sideloadly must make a request to it's servers in order to work with free developer accounts. If you are not OK with this, you may use an alternate Apple ID.

The app will now install to your iOS device.

## Trusting the application

1. Go to `Settings` -> `General` -> `Device Management` -> `<Your Apple ID>`
    - Depending on your usage, `Device Management` may be labeled `Profiles and Device Management`
1. Tap `Trust "<Your Apple ID>"`

The kok3shiX application can now be opened from home screen.

## Running kok3shiX

1. Open the kok3shiX application from your home screen
1. Tap "Jailbreak"

::: warning

If your device crashes or restarts unexpectedly and the jailbreak isn't installed, simply try running the exploit again until it does work.

:::

You should now be jailbroken with Cydia installed on your home screen. You can use Cydia to install <router-link to="/faq/#what-are-tweaks">tweaks</router-link>, themes and more.

::: tip

If you wish to use a more modern package manager, continue to <router-link to="/installing-zebra">Installing Zebra</router-link>

:::