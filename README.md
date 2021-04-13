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
</p>

<p align="center">
    <img src="https://raw.githubusercontent.com/cristianovitorino/figwrapper/master/Images/screenshot.png"
    alt="screenshot"/>
</p>

## About

`Figwrapper` is a script that integrates the [Figma](https://www.figma.com/) design tool (web version) generated by [nativefier](https://github.com/jiahaog/nativefier) into a complete, fully integrated application with local font support for Linux. It uses the [Electron](https://github.com/electron/electron) wrapper generated, which is further customized, to behave like a proper Linux app.

## Why

Convenience and local system font support. Because I use Figma as my main design tool and I'm a Linux user, I wanted a full Linux integration and automated install. Figwrapper offers improvement over the generated nativefier files, transforms it into a full, proper Linux application, allows for a quicker workflow due to it's full Linux integration, with proper Linux standard file system paths, system-wide icon and executable binary, proper .desktop and local font support. 

## How

You can manipulate it the way you want through terminal commands, scripts, dmenu/rofi calls, etc and with your WM of choice as well. Local fonts support is possible thanks to [Vin's work.](https://github.com/tryvin/figma-linux-font-helper) A systray funcionality/icon is also possible, but currently there is no feature planned for it, therefore it's disabled by default.

It behaves exactly as if you had installed it through your distro's package manager.

## Key Features
- Full Linux integration.
- Includes a `Font Linux Helper` for local fonts support.

## Requirements
- Internet connection.
- `git`
- `git-lfs`
- `python3`, `python-pip` or `python-pip3` (depends on your distro).
- `python-jinja`
- `flask` through `pip3`, usually something like `pip3 install flask`.

## Install
**Don't** download the Zip file from the repo, **it will not** download the main binary since it's stored through [Git LFS](https://git-lfs.github.com), you **need** to clone the repo through _git_. **Git LFS** is required. Install it through your distro and initialize it with `git lfs install` inside the directory that you want to download the project to. Usually something like `sudo packagemanager install git-lfs`.

```bash
git lfs install
git clone https://github.com/cristianovitorino/figwrapper.git
cd figwrapper
chmod u+x InstallFigwrapper.sh
sh ./InstallFigwrapper.sh
```

## Uninstall

```bash
chmod u+x UninstallFigwrapper.sh
sh ./UninstallFigwrapper.sh
```

## Copyright

Figwrapper © 2020 Cristiano Vitorino, BSD-3-Clause License

[Nativefier](https://github.com/jiahaog/nativefier) © 2016 [Goh Jia Hao](https://github.com/jiahaog), MIT License

[Figma Linux Font Helper](https://github.com/tryvin/figma-linux-font-helper) © 2019 [Vin](https://github.com/tryvin), MIT License

*The Figma logo is a trademark and property of Figma, Inc. and is not affiliated with nor does Figma, Inc. endorse Cristiano Vitorino.*

<div>
The Figwrapper logo is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>

<br/><a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png" /></a>
</div>
