<div align="right">

[`A3 Environment`](/APPROBATION.md) • [`CHANGELOG`](/CHANGELOG.md) • [`The Clear BSD License`](/LICENSE)

</div>

<div align="center">

The app's name
==

__The Gif Master__

Conversion from .mov to .gif

[![Actions Status](https://github.com/perseusrealdeal/mov2gif/actions/workflows/main.yml/badge.svg)](https://github.com/perseusrealdeal/mov2gif/actions/workflows/main.yml)
[![Style](https://github.com/perseusrealdeal/mov2gif/actions/workflows/swiftlint.yml/badge.svg)](https://github.com/perseusrealdeal/mov2gif/actions/workflows/swiftlint.yml)
[![Version](https://img.shields.io/badge/Version-0.0.6-green.svg)](/CHANGELOG.md)

[![Platforms](https://img.shields.io/badge/Platform-macOS%2010.13+-orange.svg)](https://en.wikipedia.org/wiki/MacOS_version_history)
[![Xcode](https://img.shields.io/badge/Xcode-14.2+-red.svg)](https://en.wikipedia.org/wiki/Xcode)
[![Swift](https://img.shields.io/badge/Swift-5-orange.svg)](https://docs.swift.org/swift-book/RevisionHistory/RevisionHistory.html)
[![SDK](https://img.shields.io/badge/SDK-UIKit%20-blueviolet.svg)](https://developer.apple.com/documentation/uikit)

[![ConsolePerseusLogger](http://img.shields.io/:ConsolePerseusLogger-1.7.1-green.svg)](https://github.com/perseusrealdeal/ConsolePerseusLogger.git)
[![PerseusDarkMode](http://img.shields.io/:PerseusDarkMode-2.2.0-green.svg)](https://github.com/perseusrealdeal/PerseusDarkMode.git)

</div>

---

Contents
==

* [Announcement](#Announcement)
    * [Our terms](#Our-terms)
    * [The why](#The-why)
    * [Preview material](#Preview-material)
    * [Top features](#Top-features)
* [Requirements](#Requirements)
* [First-party software](#First-party-software)
    * [MIT](#MIT)
    * [Unlicense](#Unlicense)
* [Third-party software](#Third-party-software)
* [Gifts](#Gifts)
* [Account points](#Account-points)
* [License](#License)
    * [Other required licenses details](#Other-required-licenses-details)
* [Credits](#Credits)
* [Contributing](#Contributing)
* [Author](#Author)
    * [Contact](#Contact)

---

Announcement
==

> This is the great home-made macOS app project to accomplish `.mov to .gif file conversion` task.

Our Terms
--

| Acronym | Stands for                                                                                                |
| :-----: | --------------------------------------------------------------------------------------------------------- |
| CPL     | [Console_Perseus_Logger](https://github.com/perseusrealdeal/ConsolePerseusLogger.git)                     |
| PDM     | [Perseus_Dark_Mode](https://github.com/perseusrealdeal/PerseusDarkMode.git)                               |
| PGK     | [Perseus_Geo_Kit](https://github.com/perseusrealdeal/PerseusGeoKit.git)                                   |
| A3      | [Apple_Apps_Approbation](https://docs.google.com/document/d/1K2jOeIknKRRpTEEIPKhxO2H_1eBTof5uTXxyOm5g6nQ) |
| T3      | [The_Technological_Tree](https://github.com/perseusrealdeal/TheTechnologicalTree)                         |
| P2P     | Person_to_Person                                                                                          |

The why
--

> The initial point of development process.

Preview material
--

> ADD: Screen shots or/and animated gif.

Top features
--

> ADD: Business features. 

- `Multilanguage:` English and Russian
- `Dark Mode:` Light, Dark, System (auto)
- `Logging:` Viewing log messages. Managing CPL options

Requirements
==

> [!NOTE]
> The current app project is represented in source code only, it's a developer edition.

`To build:`

- [macOS Monterey 12.7.6+](https://apps.apple.com/by/app/macos-monterey/id1576738294)
- [Xcode 14.2+](https://developer.apple.com/services-account/download?path=/Developer_Tools/Xcode_14.2/Xcode_14.2.xip)

`Specifications:`

- [Functional specification](/REQUIREMENTS.md)
- Translations [EN](/Convertor/Configuration/Translations/Translation_en.plist), [RU](/Convertor/Configuration/Translations/Translation_ru.plist)

First-party software
==

MIT
--

| Type     | Name                                                                                                      |
| -------- | --------------------------------------------------------------------------------------------------------- |
| Package  | [ConsolePerseusLogger v1.7.1](https://github.com/perseusrealdeal/ConsolePerseusLogger/releases/tag/1.7.1) |
| Package  | [PerseusDarkMode v2.1.1](https://github.com/perseusrealdeal/PerseusDarkMode/releases/tag/2.1.1)           |
| Class    | [MessageLabel](https://gist.github.com/PerseusRealDeal/dbfed6e01ed80be084983738ba713654)                  |

[Unlicense](https://unlicense.org)
--

| Type     | Name                                                                                                      |
| -------- | --------------------------------------------------------------------------------------------------------- |
| Class    | [WebLabel](/Convertor/FirstPartyCode/WebLabel.swift)                                                      |

Third-party software
==

| Type   | Name                                                                                  | License                            |
| ------ | ------------------------------------------------------------------------------------- | ---------------------------------- |
| Style  | [SwiftLint v0.57.0 Monterey+](https://github.com/realm/SwiftLint/releases/tag/0.57.0) | MIT                                |
| Action | [mxcl/xcodebuild@v3](https://github.com/mxcl/xcodebuild)                              | [Unlicense](https://unlicense.org) |
| Action | [cirruslabs/swiftlint-action@v1](https://github.com/cirruslabs/swiftlint-action/)     | MIT                                |

Gifts
==

- [CurrentSystemLanguageGift.swift](https://gist.github.com/perseusrealdeal/98b082b136d574dd1b5aa760036dac8b)
- [JsonDataDictionaryGift.swift](https://gist.github.com/perseusrealdeal/918c25633122e64d51f363f00059f6f8)
- [JsonDataPrettyPrintedGift.swift](https://gist.github.com/perseusrealdeal/945c9050cb9f7a19e00853f064acacca)
- [LocalizedInfoPlistGift.swift](/PerseusTests/Configuration/LocalizedInfoPlistGift.swift)
- [LocalizedExpectationGift.swift](/PerseusTests/Configuration/LocalizedExpectationGift.swift)

Account points 
==

- Explicit start point [main.swift](/Convertor/main.swift)
- Explicit app delegate [TestingAppDelegate.swift](/PerseusTests/TestingAppDelegate.swift)
- Explicit app globals [AppGlobals.swift](/Convertor/AppGlobals.swift)
- Explicit app options [AppOptions.swift](/Convertor/AppOptions.swift)
- Architectural points: 
    - MVP applied. Based on [Gist](https://gist.github.com/PerseusRealDeal/5301e90881732f0cd0040e2083a78a3d)
    - Coordinator. [`Coordinator.swift`](/Convertor/BusinessContent/Coordinator.swift)
- Localization based on Localizable.strings approach
- [Test Plan](/PerseusTests/TestPlanStarted.xctestplan) configured for EN and RU
- [Changelog](/CHANGELOG.md)
- [A3 environment specification](/APPROBATION.md)
- [Software requirements specification](/REQUIREMENTS.md)
- [GitHub CI build & test](/.github/workflows/main.yml)
- [GitHub CI SwiftLint](/.github/workflows/swiftlint.yml)
- [SwiftLint Rules](/.swiftlint.yml)
- [Git Config](/.gitignore)
- SwiftLint shell script as a build phase, SwiftLint preinstallation required

License
==

__The Clear BSD License__, see [LICENSE](/LICENSE) for details.

Copyright `© 7534 Mikhail A. Zhigulin of Novosibirsk`<br/>
Copyright `© 7534 PerseusRealDeal`

- The year starts from the creation of the world according to a Slavic calendar.
- September, the 1st of Slavic year. For instance, "Sep 01, 2025" is the beginning of 7534.

Other required licenses details
--

© 2025 The SwiftLint Contributors **for** SwiftLint</br>
© GitHub **for** GitHub Action cirruslabs/swiftlint-action@v1</br>

Credits
==

<table>
  <tr>
      <td>Balance and Control</td>
      <td>Mikhail Zhigulin</td>
  </tr>
  <tr>
      <td>Source Code</td>
      <td>Mikhail Zhigulin</td>
  </tr>
  <tr>
      <td>Documentation</td>
      <td>Mikhail Zhigulin</td>
  </tr>
  <tr>
      <td>Approbation</td>
      <td>Mikhail Zhigulin</td>
  </tr>
<!--
  <tr>
      <td>Artwork</td>
      <td>Mikhail Zhigulin</td>
  </tr>
-->
  <tr>
      <td>English</td>
      <td>Mikhail Zhigulin</td>
  </tr>
  <tr>
      <td>Russian</td>
      <td>Mikhail Zhigulin</td>
  </tr>
</table>

<!--
- Artwork tool: [GIMP](https://www.gimp.org/) / [2.10.36](https://download.gimp.org/gimp/v2.10/osx/) for macOS 10.12 Sierra or newer
-->
- Language support: [Reverso](https://www.reverso.net/) 
- Git clients: [SmartGit](https://syntevo.com/) and [GitHub Desktop](https://github.com/apps/desktop)

Contributing
==

> [!NOTE]
> The product is constructed in `P2P` relationship paradigm that means the only one single and the same face in the product team during all development process.

`Translations and bug reports are welcome`, create an issue and give details.

If you'd like `to see the app in your native language` consider [translation for EN](/Convertor/Configuration/Translations/Translation_en.plist) as a template, then prepare your translation in the same way and create an issue, EN and RU already done.

Author
==

<div align="center">

`© Mikhail A. Zhigulin of Novosibirsk`

</div>

Contact
--

<div align="center">

[E-mail](mailto:mzhigulin@gmail.com) • [Telegram](https://t.me/velociraptor1985) • [GitHub](https://github.com/perseusrealdeal)

</div>
