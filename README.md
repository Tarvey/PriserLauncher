<p align="center">This is a fork of prism launcher made to run servers, im not gonna remove functionality, this might come into prism launcher if i create a pull request</p>

<p align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo-darkmode.svg">
  <source media="(prefers-color-scheme: light)" srcset="/program_info/org.prismlauncher.PrismLauncher.logo.svg">
  <img alt="Prism Launcher" src="/program_info/org.prismlauncher.PrismLauncher.logo.svg" width="40%">
</picture>
</p>

<p align="center">
  Priser Launcher is a custom launcher for Minecraft servers that allows you to easily manage multiple installations of Minecraft servers at once.<br />
  <br />This is a <b>fork</b> of the Prism Launcher and is <b>not</b> endorsed by it.
</p>

## Installation



- All downloads and instructions for Priser Launcher can be found on the releases tab
- Last build status can be found in the [GitHub Actions](https://github.com/Tarvey/PriserLauncher/actions).

### Development Builds

There are development builds available in the releases tab.

Prebuilt Development builds are provided for **Linux**, **Windows** and **macOS**.


These packages are also availiable to all the distributions based on the ones mentioned above.

## Community & Support

Feel free to create a GitHub issue if you find a bug or want to suggest a new feature. We have multiple community spaces where other community members can help you:

- **Our Discord server:**

A discord server is coming soon.

- **Our Matrix space:**

This might come, someone can run a community-ran server

- **Our Subreddit:**

[![r/PriserLauncher](https://img.shields.io/reddit/subreddit-subscribers/priserlauncher?style=for-the-badge&logo=reddit)](https://www.reddit.com/r/PriserLauncher/)

## Translations

The translation effort for PrismLauncher is hosted on [Weblate](https://hosted.weblate.org/projects/prismlauncher/launcher/) and information about translating Prism Launcher is available at <https://github.com/PrismLauncher/Translations>, <b>Priser Launcher will use english for some strings.</b>

## Building

If you want to build Prism/Priser Launcher yourself, check the [Build Instructions](https://prismlauncher.org/wiki/development/build-instructions/).

## Sponsors & Partners

Thanks to all of supporters of Prism Launcher, developers and contributors, and the community!

Thanks to all companies, like jetbrains, weblate, netlify for making Prism developers use their products!

## Forking/Redistributing/Custom builds policy

We don't care what you do with your fork/custom build as long as you follow the terms of the [license](LICENSE) (this is a legal responsibility), and if you made code changes rather than just packaging a custom build, please do the following as a basic courtesy:

- Make it clear that your fork is not PrismLauncher and is not endorsed by or affiliated with the PrismLauncher project (<https://prismlauncher.org>). <b>Priser Launcher follows this, we advice you do too.</b>
- Go through [CMakeLists.txt](CMakeLists.txt) and change PrismLauncher's API keys to your own or set them to empty strings (`""`) to disable them (this way the program will still compile but the functionality requiring those keys will be disabled). <b>Applying for a curseforge key, right now its empty</b>

If you have any questions or want any clarification on the above conditions please make an issue and ask us.

Be aware that if you build this software without removing the provided API keys in [CMakeLists.txt](CMakeLists.txt) you are accepting the following terms and conditions:

- [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the [CMakeLists.txt](CMakeLists.txt) file by setting them to an empty string (`""`).

## License [![https://github.com/PrismLauncher/PrismLauncher/blob/develop/LICENSE](https://img.shields.io/github/license/PrismLauncher/PrismLauncher?label=License&logo=gnu&color=C4282D)](LICENSE)

All launcher code is available under the GPL-3.0-only license.

The logo and related assets are under the CC BY-SA 4.0 license.


<b>If any of the Prism developers has complains, please message filebone#2450</b>