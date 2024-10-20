
# CPU Toggle <a href="https://github.com/TheVoidBlock/cpu-toggle/releases/latest"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/thevoidblock/cpu-toggle?include_prereleases&logo=github&label=RELEASE&style=for-the-badge"></a> <a href="https://www.gnu.org/licenses/gpl-3.0.en.html"><img alt="License" src="https://www.gnu.org/graphics/gplv3-127x51.png"></a>



## Overview
TUI Tool for toggling CPU cores.

Syntax: ```cpu-toggle [options]```

Keybinds:
> `q` - `quit`<br>
> `up | down` - `move cursor`<br>
> `left | right` - `toggle cpu core`

Options:
> `list` - `list active/inactive cpu cores`

### Preview
<img src="https://raw.githubusercontent.com/TheVoidBlock/cpu-toggle/refs/heads/main/images/preview.png" alt="preview" width="200"/>

## Support
Currently, the only operating system officially supported is [Arch Linux](https://archlinux.org/)

## Installation
<details>
	<summary>Dependencies</summary>
	<br>
	<a href="https://archlinux.org/packages/core/x86_64/bash/">bash</a><br>
	<a href="https://archlinux.org/packages/core/x86_64/findutils/">findutils</a><br>
	<a href="https://archlinux.org/packages/core/x86_64/coreutils/">coreutils</a><br>
	<a href="https://archlinux.org/packages/core/x86_64/ncurses/">ncurses</a><br>
	<a href="https://archlinux.org/packages/extra/x86_64/tcl/">tcl</a><br>
 	<a href="https://archlinux.org/packages/core/x86_64/grep/">grep</a><br>
	<code># pacman -S bash findutils coreutils ncurses tcl grep</code>
</details>

- Clone the latest release, or git
	- Git: ```git clone https://github.com/TheVoidBlock/cpu-toggle```
	- Release: Replace **\<release\>** with the [latest release](https://github.com/TheVoidBlock/cpu-toggle/releases/latest)'s tag ```git clone --branch <release> https://github.com/TheVoidBlock/cpu-toggle/```
- Enter the cloned repository ```cd cpu-toggle```
- Make & Install the package ```makepkg -si```
