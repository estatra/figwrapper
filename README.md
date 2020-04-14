<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/icon.png"
    alt="icon"/>
</p>

<h1 align="center">
    Figwrapper
</h1>

<p align="center">
  <a href="https://www.codefactor.io/repository/github/cristianovitorino/figwrapper">
    <img src="https://www.codefactor.io/repository/github/cristianovitorino/figwrapper/badge" alt="CodeFactor">
  </a>
  <a href="https://www.codefactor.io/repository/github/cristianovitorino/figwrapper">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/cristianovitorino/figwrapper">
  </a>
<a href="https://app.fossa.io/projects/git%2Bgithub.com%2Fcristianovitorino%2Ffigwrapper?ref=badge_shield" alt="FOSSA Status"><img src="https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcristianovitorino%2Ffigwrapper.svg?type=shield"/></a>
  <a href="https://github.com/prettier/prettier">
    <img alt="code style: prettier" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square">
  </a>
  <a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Y79WNXRNJCHB4&source=url">
    <img alt="PayPal" src="https://img.shields.io/badge/PayPal-Donate-brightgreen?style=flat-square">
  </a>
</p>

`Figwrapper` is a script that integrates the [Figma](https://www.figma.com/) design tool (web version) generated by [nativefier](https://github.com/jiahaog/nativefier) into a complete, fully integrated application with local font support for Linux. It uses the [Electron](https://github.com/electron/electron) wrapper generated, which is further customized, to behave like a proper Linux app.

<h1 align="center">
    Why
</h1>

Convenience and local system font support. Because I use it a lot and wanted a full Linux integration and automated install. Figwrapper offers improvement over the generated nativefier files, transforms it into a full, proper Linux application, allows for a quicker workflow due to it's full Linux integration, with proper Linux standard file system paths, system-wide icon and executable binary, proper .desktop. 

<h1 align="center">
    How
</h1>

You can manipulate it the way you want through terminal commands, scripts, dmenu/rofi calls, etc and with your WM of choice as well. Local fonts support is possible thanks to [Vin's work.](https://github.com/tryvin/figma-linux-font-helper) A systray funcionality/icon is also possible, but currently there is no feature planned for it, therefore it's disabled by default.

It behaves exactly as if you had installed it through your distro's package manager.

<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/screenshot.png"
    alt="screenshot"/>
</p>

## Key Features
- Full Linux integration.
- Includes a `Font Linux Helper` for local fonts support.

## Requirements
- Internet connection.
- `python3` and `flask` installed through `pip3`.

## Install
**Don't** download the Zip file from the repo, **it will not** download the main binary since it's stored through Git LFS, you need to clone the repo through git. Git LFS is required. Install it through your distro and initialize it with `git lfs install`.

```bash
$ git clone https://github.com/cristianovitorino/figwrapper.git
$ cd figwrapper
$ chmod u+x InstallFigma.sh
$ sh ./InstallFigma.sh
```

## Uninstall

```bash
> chmod u+x InstallFigma.sh
> sh ./UninstallFigma.sh
```

## Copyright

Figwrapper © 2020 Cristiano Vitorino, MIT License

[Nativefier](https://github.com/jiahaog/nativefier) © 2016 [Goh Jia Hao](https://github.com/jiahaog), MIT License

[Figma Linux Font Helper](https://github.com/tryvin/figma-linux-font-helper) © 2019 [Vin](https://github.com/tryvin), MIT License

*The Figma logo is a trademark and property of Figma, Inc. and is not affiliated with nor does Figma, Inc. endorse Cristiano Vitorino.*

---

<div>
The Figwrapper logo is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>

<br/><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png" /></a>
</div>

---
## Donation
If you like my work and want to show some :heart:

[<img height="30" src="paypal-donate.png" alt="PayPal"/>](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=Y79WNXRNJCHB4&source=url)

<a href="https://www.buymeacoffee.com/cristianovitorino" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fcristianovitorino%2Ffigwrapper.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fcristianovitorino%2Ffigwrapper?ref=badge_large)

---

<h6 align="center">
  Made with :heart: from :brazil:!
</h6>
