# NOTE

This is a fork of [SwitchKey](https://github.com/itsuhane/SwitchKey) by [@itsuhane](https://github.com/itsuhane). It it based on [@JasprW](https://github.com/JasprW)'s pull request [support default input source and fix layout #48](https://github.com/itsuhane/SwitchKey/pull/48) that adds a major improvement: **Setting a default layout.**

![image](https://github.com/user-attachments/assets/009290dc-fc7c-4a29-b3da-9b1338b6af01)

I just fixed two build errors with Xcode 16.4 and archived the app. You can download it from the releases tab.

Made this for my own, use at your own risk.

---

![switchkey](README.assets/switchkey.png)

# SwitchKey

Automatically use the correct input source.

Ever hassled by wrong input source when switching application?  
SwitchKey can automatically activate your choice for you.

## Download & Install

### Manually:

Download (macOS):  
[![Latest](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=latest&query=%24.tag_name&url=https%3A%2F%2Fapi.github.com%2Frepos%2Fitsuhane%2FSwitchKey%2Freleases%2Flatest&style=social)](https://github.com/itsuhane/SwitchKey/releases/latest/download/SwitchKey.zip)  
Uncompress, then drag & drop into your Applications folder.

### Via Homebrew (thanks to [@fanvinga](//github.com/fanvinga/)):

```
brew install --cask switchkey
```

### Usage

![switchkey-ui](README.assets/switchkey-ui.png)

- Save current input source choice for frontmost application:  
  click "Add Current".

- Enable/disable automatic switch for saved application:  
  check/uncheck the checkbox on the right.

- Remove saved choice:  
  select the one to be deleted, then press delete key.

Not working? See below.

### First Run

Upon first launch, SwitchKey will ask for accessibility permission.  
SwitchKey will open accessibility page, **and exit**.  
After you grant permission, re-launch SwitchKey again.  
The same will happen if you reject the permission later.

![switchkey-ui](README.assets/switchkey-permission.png)

### Purchase

I wrote this because I tried some other tools.  
They are either buggy or too cumbersome to configure.  
I payed money and time for them.  
So you don't have to pay for them anymore.

### Bug Report & Feature Request

Welcome! Please click [here](https://github.com/itsuhane/SwitchKey/issues/new).
