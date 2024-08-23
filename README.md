# Team Failure - Failbreak

[![GitHub stars](https://img.shields.io/github/stars/Team-Failure/Failbreak?style=social)](https://github.com/Team-Failure/Failbreak/stargazers)

A full featured bootstrap for iOS 15.0-17.0 A8-A17 & M1+M2 using our Procursus.

##### *WARNING:* By using this software, you take full responsibility for what you do with it. Any unofficial modifications to your device may cause irreparable damage. Refer to the FAQ linked in the `Usage` section for safe usage of this software.

Failbreak is available to download on this repositories [Releases](https://github.com/Team-Failure/Failbreak/releases).

## Building

You'll need MacOS to build, as you require Xcode from the App Store. Simply having Xcode Command Line Tools is *insufficient*. Here's how to build the app (also you can fork, modify and build with the workflow):

 1. Update/Install Theos with our Procursus support
    
    ```
    bash -c "$(curl -fsSL https://raw.githubusercontent.com/Team-Failure/theos/master/bin/install-theos)"
    ```
    *If you encounter errors from a previous Theos installation, remove Theos in its entirety before continuing.*

 2. Clone the GitHub repository and enter directory

    ```
    git clone https://github.com/Team-Failure/Failbreak/ && cd Failbreak
    ```

 3. Build `Bootstrap.tipa`

    ```
    make package
    ```

 4. Transfer `Bootstrap.tipa` from `./packages/` to your device and install it with TrollStore

## Usage

The Failbreak application **must** be installed with [TrollStore](https://ios.cfw.guide/installing-trollstore/). Use version `2.0.9` or later for enabling developer mode on-device.

Tweaks not compiled or converted to our Procursus will not work out-of-the-box with Failbreak. Refer to the FAQ below on how to use roothide Patcher.

By design, our Procursus does not inject tweaks into any applications by default. To enable tweak injection into an application, press `App List` in the Failbreak app, and enable the toggle of the application you want to inject into. Injection into `com.apple.springboard` or daemons is not possible with Failbreak. Refer to the FAQ below on injection into `com.apple.springboard`.

**A roothide Bootstrap FAQ** is available [here](https://github.com/dleovl/Bootstrap/blob/faq/README.md). (it is the roothide Bootstrap FAQ because it is just a fork)

## Develop tweaks

Both rootful and rootless tweaks aren't out-of-the-box compatible with our Procursus, so you'll need to develop them specifically to support it. You can refer to the developer documentation [here](https://github.com/roothide/Developer).

## Discord server

You can join the roothide Discord server for support or general discussion [here](https://discord.com/invite/scqCkumAYp).

For moment the Team Failure's discord server is not created.

## The "Our Table" Icon

The ProcursusTeam logo was originally made by [@TheAlphaStream](https://github.com/TheAlphaStream), and later edited by [@sourcelocation](https://github.com/sourcelocation).
