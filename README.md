<p align="center">
<img src="./program_info/polymc-header-black.svg#gh-light-mode-only" alt="PolyMC logo" width="50%"/>
<img src="./program_info/polymc-header.svg#gh-dark-mode-only" alt="PolyMC logo" width="50%"/>
</p>

OfflineMC is a custom launcher for Minecraft that focuses on predictability, long term stability and simplicity.

This is a **fork** of the PolyMC Launcher and not endorsed by PolyMC.
If you want to read about why this fork was created, check out THE NAME.
<br>

# Installation

- All downloads and instructions for PolyMC can be found [here](https://polymc.org/download/)
- Last build status: <https://github.com/PolyMC/PolyMC/actions>

# Help & Support

Feel free to create an issue if you need help.<br>
There is no support for offline accounts. Although, you can try on [PolyMC official repository](https://github.com/PolyMC/PolyMC/issues).

# Development

If you want to contribute to PolyMC you might find it useful to upload something.

## Building

If you want to build PolyMC yourself, check [Build Instructions](https://polymc.org/wiki/development/build-instructions/) for build instructions.

## Translations

The translation effort for PolyMC is hosted on [Weblate](https://hosted.weblate.org/projects/polymc/polymc/) and information about translating PolyMC is available at <https://github.com/PolyMC/Translations>

## Download information

To modify download information or change packaging information send a pull request or issue to the website [here](https://github.com/PolyMC/polymc.github.io/tree/master/src/download).

## Forking/Redistributing/Custom builds policy

We don't care what you do with your fork/custom build as long as you follow the terms of the [license](LICENSE) (this is a legal responsibility), and if you made code changes rather than just packaging a custom build, please do the following as a basic courtesy:

- Make it clear that your fork is not PolyMC and is not endorsed by or affiliated with the PolyMC project (<https://polymc.org>).
- Go through [CMakeLists.txt](CMakeLists.txt) and change PolyMC's API keys to your own or set them to empty strings (`""`) to disable them (this way the program will still compile but the functionality requiring those keys will be disabled).

If you have any questions or want any clarification on the above conditions please make an issue and ask us.

Be aware that if you build this software without removing the provided API keys in [CMakeLists.txt](CMakeLists.txt) you are accepting the following terms and conditions:

- [Microsoft Identity Platform Terms of Use](https://docs.microsoft.com/en-us/legal/microsoft-identity-platform/terms-of-use)
- [CurseForge 3rd Party API Terms and Conditions](https://support.curseforge.com/en/support/solutions/articles/9000207405-curse-forge-3rd-party-api-terms-and-conditions)

If you do not agree with these terms and conditions, then remove the associated API keys from the [CMakeLists.txt](CMakeLists.txt) file by setting them to an empty string (`""`).

All launcher code is available under the GPL-3.0-only license.
  
The logo and related assets are under the CC BY-SA 4.0 license.

## Sponsors

Thank you to all our generous backers over at Open Collective! Support PolyMC by [becoming a backer](https://opencollective.com/polymc).

[![OpenCollective Backers](https://opencollective.com/polymc/backers.svg?width=890&limit=1000)](https://opencollective.com/polymc#backers)

Also, thanks to JetBrains for providing us a few licenses for all their products, as part of their [Open Source program](https://www.jetbrains.com/opensource/).

[![JetBrains](https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.svg)](https://www.jetbrains.com/opensource/)

Additionally, thanks to the awesome people over at [MacStadium](https://www.macstadium.com/), for providing M1-Macs for development purposes!

<a href="https://www.macstadium.com"><img src="https://uploads-ssl.webflow.com/5ac3c046c82724970fc60918/5c019d917bba312af7553b49_MacStadium-developerlogo.png" alt="Powered by MacStadium" width="300"></a>
