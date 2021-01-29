---
title: "Getting Started"
description: "One page summary of how to get started with APKLab."
lead: "One page summary of how to get started with APKLab."
draft: false
images: []
menu:
  docs:
    parent: "user-guide"
weight: 21
toc: true
---

## Requirements

- **JDK 8+**
- **Quark-Engine**

  If you want to use the **Malware-Analysis** feature, make sure you have [Quark-Engine](https://github.com/quark-engine/quark-engine) installed. To install it, simply run:
  {{< btn-copy text="pip install -U quark-engine" >}}
  ```bash
  pip install -U quark-engine
  ```
- **ADB**

## Install APKLab

- You can install APKLab directly by clicking on <kbd>Extensions</kbd> from the sidebar in VS Code and searching for APKLab.
- You can also download `.vsix` file directly from [open-vsx.org](https://open-vsx.org/extension/Surendrajat/apklab) and install it manually if you need.


### Open APK or Apktool project

- Open the Command Palette (<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>) ➜ <kbd>APKLab: Open an APK</kbd>

  {{< figure src="/images/screenshots/decode.gif" height="100%" width="100%">}}

- Or Just open an existing Apktool project folder

### Apply MITM patch

- Right-Click on or inside `apktool.yml` file ➜ <kbd>APKLab: Prepare for HTTPS inspection</kbd>

  {{< figure src="/images/screenshots/mitm.gif" height="100%" width="100%">}}

### ReBuild and Sign APK

- Right-Click on or inside `apktool.yml` file ➜ <kbd>APKLab: Rebuild the APK</kbd>

  {{< figure src="/images/screenshots/rebuild.gif" height="100%" width="100%">}}

### Install APK to device

- Right-Click on `.apk` file (in `dist` directory) ➜ <kbd>APKLab: Install the APK</kbd>

  {{< figure src="/images/screenshots/install.gif" height="100%" width="100%">}}
