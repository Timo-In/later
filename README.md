# Later



https://user-images.githubusercontent.com/7581348/176900722-6ceb1fb7-b235-4a6a-991c-6273edc31b30.mp4


Save all your Mac apps for later with one click 🖱️

Later is a Mac menu bar app that clears and restores your workspace with ease. Switch off from work, tidy up your desktop before screen sharing, schedule apps for later, and more.


<a href="https://www.producthunt.com/posts/later-aa762753-cafe-475e-9acb-d534de9e6adf?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-later&#0045;aa762753&#0045;cafe&#0045;475e&#0045;9acb&#0045;d534de9e6adf" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=332569&theme=light" alt="Later - Save&#0032;all&#0032;your&#0032;Mac&#0032;apps&#0032;for&#0032;later&#0032;with&#0032;one&#0032;click | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

> You can support this project (and many others) through [GitHub Sponsors](https://github.com/sponsors/alyssaxuu)! ❤️

Made by [Alyssa X](https://twitter.com/alyssaxuu)

Note: I am not maintaining this project any longer, I have open sourced it so anyone can make changes and improvements, or build their own version of it.

## Table of contents

- [Features](#features)
- [Installing Later](#installing-later)
- [Source code](#source-code)

## Features

👻 Hide or close all your apps<br> ⚡️ Restore your session with just one click<br> 👀 View metadata and a preview of your saved sessions<br> ⏱ Schedule apps to reopen after some time to get back in the flow<br> 🔋 Save battery by closing your apps instead of leaving them open<br> ⌨️ Keyboard shortcuts to save and restore your session<br> ⚙️ Advanced settings to ignore apps, terminate instead of hiding, etc.

## Installing Later
You can install Later on macOS 12.0 or later.

### Option 1: Via Homebrew (Recommended)
You can install Later directly using Homebrew from the tap repository:
```bash
brew tap Timo-In/tap
brew install --cask later
```

To update Later via brew in the future:
```bash
brew upgrade --cask later
```

### Option 2: Direct Download (.dmg)
1. Download the latest installer `Later.dmg` from the [GitHub Releases](https://github.com/Timo-In/later/releases).
2. Open `Later.dmg` and drag the **Later** app into your `/Applications` folder.
3. Right-click while holding the `Control` key on the **Later** app in Applications, and select **"Open"** from the context menu (or open System Settings -> Privacy & Security to allow it).
4. Since the application is not notarized with an Apple Developer certificate, macOS will ask for confirmation. Click **"Open"** to proceed (or run `xattr -cr /Applications/Later.app` in Terminal if needed).
5. Later will launch and stay accessible directly in your menu bar.

You can read the [FAQ](https://necessary-duke-5f6.notion.site/FAQ-c1a7231ecf34441e9d3d6944199e4705) if you have any questions.

## Source code
You can open Later in Xcode if you'd like to make any changes, or develop it further.
1. Download the [Xcode folder](https://github.com/alyssaxuu/later/tree/master/xcode) in the repo.
2. Open Xcode, and choose the option to "Open a project or file"
3. Select the Xcode folder you downloaded
4. You might be prompted with a warning, select "Trust and open" to proceed.
