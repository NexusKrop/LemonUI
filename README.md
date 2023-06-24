# LemonUI

[![Nuget](https://img.shields.io/nuget/v/NexusKrop.LemonUI.SHVDNC?style=flat-square&logo=nuget&logoColor=white)](https://www.nuget.org/packages/NexusKrop.LemonUI.SHVDNC)

> **Unofficial version. Not endorsed or supported by Lemon.**
>
> For the official version, **[Click here](https://github.com/LemonUIbyLemon/LemonUI)**. Do not report issues that occurs while using this fork to LemonUI upstream; report to this repository.

This is a fork of LemonUI, a framework for creating UI systems in Grand Theft Auto V that is compatible with FiveM, RageMP, RagePluginHook ScriptHookVDotNet 2 and ScriptHookVDotNet 3. It allows you to create UI Elements with a NativeUI-like style, or you can also create your own UI System from scratch via the resolution-independant classes for Text, Rectangles and Textures. This fork adds build for `ScriptHookVDotNetCore`.

It was created as a replacement for NativeUI due to being too convoluted to develop and maintain. LemonUI retains most (if not all) of the UI Elements available in NativeUI.

Special thanks to:

* Guad for the original work in NativeUI
* alloc8or for the help with the GTA Online Loading Screen Scaleform
* ikt for helping me to use SET_SCRIPT_GFX_ALIGN and SET_SCRIPT_GFX_ALIGN_PARAMS
* Dot. for the snippet of code used for the item scrolling
* deterministic_bubble for answering some questions about some missing C# classes in FiveM
* PNWParksFan for helping me with some RPH question when I was doing the port

## Download

* [5mods](https://www.gta5-mods.com/scripts/lemonui)
* [GitHub Releases](https://github.com/LemonUIbyLemon/LemonUI/releases)
* [GitHub Actions](https://github.com/LemonUIbyLemon/LemonUI/actions) (experimental versions)

## Installation

### Users

Download from releases and extract contents of the `SHVDNC` folder inside the archive to your `scripts` folder.

### Developers

Add any of the NuGet packages linked above and start working in your IDE.

If you are using RagePluginHook or ScriptHookVDotNet, you can disable the copy of the dll in your IDE so your users always have to use the latest version available.

If you are using RageMP, you will need to download the latest release and copy **LemonUI.RageMP.cs** to you client solution.

## Usage

Once installed, the mods that require LemonUI will start working.

If you are a developer, check the [wiki](https://github.com/LemonUIbyLemon/LemonUI/wiki) for information to implement LemonUI in your mod.

[actions-img]: https://img.shields.io/github/actions/workflow/status/LemonUIbyLemon/LemonUI/main.yml?branch=master&label=actions
[actions-url]: https://github.com/LemonUIbyLemon/LemonUI/actions
[nuget-img-2]: https://img.shields.io/nuget/v/LemonUI.SHVDN2?label=nuget%20%28shvdn%202%29
[nuget-url-2]: https://www.nuget.org/packages/LemonUI.SHVDN2/
[nuget-img-3]: https://img.shields.io/nuget/v/LemonUI.SHVDN3?label=nuget%20%28shvdn%203%29
[nuget-url-3]: https://www.nuget.org/packages/LemonUI.SHVDN3/
[nuget-img-f]: https://img.shields.io/nuget/v/LemonUI.FiveM?label=nuget%20%28fivem%29
[nuget-url-f]: https://www.nuget.org/packages/LemonUI.FiveM/
[nuget-img-m]: https://img.shields.io/nuget/v/LemonUI.RageMP?label=nuget%20%28ragemp%29
[nuget-url-m]: https://www.nuget.org/packages/LemonUI.RageMP/
[nuget-img-r]: https://img.shields.io/nuget/v/LemonUI.RagePluginHook?label=nuget%20%28rph%29
[nuget-url-r]: https://www.nuget.org/packages/LemonUI.RagePluginHook/
[patreon-img]: https://img.shields.io/badge/support-patreon-FF424D.svg
[patreon-url]: https://www.patreon.com/lemonchan
[paypal-img]: https://img.shields.io/badge/support-paypal-0079C1.svg
[paypal-url]: https://paypal.me/justalemon
[discord-img]: https://img.shields.io/badge/discord-join-7289DA.svg
[discord-url]: https://discord.gg/Cf6sspj
