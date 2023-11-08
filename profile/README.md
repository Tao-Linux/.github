<p align="center">
<img src="https://github.com/Tao-Linux/Tao-ISO/blob/main/assets/tao-text.svg?raw=true" width="50%" height="50%">
</p>

<h1 align="center">Tao Linux</h1>

<p align="center">An Arch Linux based distribution centered around the Catppuccin theme</p>

## What's Tao?

Tao Linux is an [Arch Linux](https://archlinux.org/)-based distribution that heavily utilizes Catppuccin. From the official [Catppuccin GitHub repository](https://github.com/catppuccin/catppuccin)'s README:

> Catppuccin is a community-driven pastel theme that aims to be the middle ground between low and high contrast themes.

In particular, Tao Linux uses the Mocha flavor of Catppuccin.

Tao also uses the highly configurable [BSPWM](https://github.com/baskerville/bspwm).

Tao Linux aims to make the installation of a beautiful and efficient system easier than ever before!

## How can I install Tao?

Please follow the guide linked [here](https://github.com/Tao-Linux/Tao-ISO/#installation) in order to install Tao Linux on your machine. Please note, **we are in early development** and you may experience some issues, which we encourage you to [report](https://github.com/Tao-Linux/Tao-ISO/issues).

## Is Flatpak included in Tao?

Tao Linux does **not** come with Flatpak pre-installed. However, you can easily add it using the `pacman` package manager. The reason for not including Flatpak by default is primarily related to theming. Tao uses the BSPWM window manager, which doesn't seamlessly integrate with Flatpak applications in terms of theming. While you can still install Flatpak apps, they might not match Tao's default Catppuccin theme, and achieving that seamless integration is quite complex and time-consuming. In our perspective, Tao doesn't heavily rely on Flatpak due to the rich software availability in the official Arch repositories and the AUR (Arch User Repository). If a piece of software isn't present in the official repositories, we usually compile it ourselves and make it available in our repos. While we understand the security benefits of using Flatpak, the effort required to set it up properly on our unique window manager setup is a significant factor. That being said, if you're up for the challenge, you're more than welcome to contribute! If you can set up Flatpak with the Catppuccin theme to seamlessly blend with Tao's aesthetic, feel free to [submit a pull request to the ISO repository](https://github.com/Tao-Linux/Tao-ISO/pulls). Your contribution could potentially provide a smoother Flatpak experience for Tao users who value both security and visual consistency.

## Who develops Tao?

Tao is a labor of love, primarily developed by [Yatoub](https://github.com/yatoub), with contributions from dedicated friends. While we don't accept monetary donations, you can support us by spreading the word and recommending Tao to others. Your enthusiasm is our greatest reward.

## What is Tao licensed under?

Most repositories and projects under the Tao name are licensed under the [GPLv3 License](https://www.gnu.org/licenses/gpl-3.0.en.html). The Catppuccin theme is licensed under the [MIT License](https://opensource.org/license/mit/). Licenses for other software included in the distribution are usually found within the files provided by their respective packages.

## Does Tao use the Contributor Covenant?

As you know by now, Tao Linux heavily utilizes the Catppuccin theme for GTK, Qt, and standalone apps. Catppuccin is a project that uses the [Contributor Covenant Code of Conduct](https://github.com/catppuccin/.github/blob/main/CODE_OF_CONDUCT.md). **However,** unlike Catppuccin, we do not wish to use this code of conduct at this time. While it is an admirable action to add a code of conduct to your project, we find that the Contributor Covenant is too vague and subjective, and we also have concerns over the views of its creator. We are not saying not to use the Contributor Covenant; you are free to do so in whatever project you like. However, do not expect Tao Linux to begin use of the Contributor Covenant any time soon. Right now, we are under the [AntiCoC](https://github.com/Nekosis/anticoc/blob/main/CODE_OF_CONDUCT.md).

## I need to get in contact regarding a legal issue.

If you have found that Tao has violated any licenses or copyrights, please don't hesitate to open an issue on the repository/repositories that do so and we will do our best to respond in a timely manner.

##

<p align="center">All repositories are copyleft 🄯2023-present <a href="https://github.com/Tao-Linux/">Tao Linux</a> and licensed under the <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">GPLv3 License</a>. Some rights reserved.</p>
