<div align="center">
  <h1>Fork of <a href="https://github.com/uiriansan/SilentSDDM">SilentSDDM</a> for <a href="github.com/Tapi-Mandy/guhwm">guhwm</a></h1>
</div>

### Presets

https://github.com/user-attachments/assets/3a03e859-c6b9-4c4b-bf7f-ab610b94eb28

<details>
  <summary>configs/catppuccin-latte.conf</summary>
<img src="https://github.com/uiriansan/SilentSDDM/blob/main/docs/previews/catppuccin-latte.png" width="100%" />
</details>

<details>
<summary>configs/catppuccin-frappe.conf</summary>
<img src="https://github.com/uiriansan/SilentSDDM/blob/main/docs/previews/catppuccin-frappe.png" width="100%" />
</details>

<details>
  <summary>configs/catppuccin-macchiato.conf</summary>
<img src="https://github.com/uiriansan/SilentSDDM/blob/main/docs/previews/catppuccin-macchiato.png" width="100%" />
</details>

<details>
  <summary>configs/catppuccin-mocha.conf</summary>
<img src="https://github.com/uiriansan/SilentSDDM/blob/main/docs/previews/catppuccin-mocha.png" width="100%" />
</details>

[`Customization guide`](#Customizing)

### Dependencies

- SDDM ≥ 0.21;
- QT ≥ 6.5;
- qt6-svg;
- qt6-virtualkeyboard
- qt6-multimedia

### Installation

```bash
git clone -b main --depth=1 https://github.com/Tapi-Mandy/guhSDDM && cd guhSDDM
```

### Customizing

The preset configs are located in `./configs/`. To change the active config, edit `./metadata.desktop` and replace the value of `ConfigFile=`:

```bash
ConfigFile=configs/<your_preferred_config>.conf
```

You can also create your own config file. There's a guide with the list of available options in the [wiki](https://github.com/uiriansan/SilentSDDM/wiki/Customizing).

There are some extra tips on how to customize the theme on the [snippets page](https://github.com/uiriansan/SilentSDDM/wiki/Snippets).

---

### Acknowledgements

- [Keyitdev/sddm-astronaut-theme](https://github.com/Keyitdev/sddm-astronaut-theme): Inspiration and code reference
- [Match-Yang/sddm-deepin](https://github.com/Match-Yang/sddm-deepin): Inspiration and code reference
- [qt/qtvirtualkeyboard](https://github.com/qt/qtvirtualkeyboard): Code reference
- [Joyston Judah](https://www.pexels.com/photo/white-and-black-mountain-wallpaper-933054/): Background
- [iconify.design](https://iconify.design/): Icons

Send a message to this [email](mailto:uiriansan@gmail.com?subject=Background%20image%20in%20SilentSDDM) if you are the creator of some of these images and want them removed or acknowledged.
