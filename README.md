<h3 align="center">
	<img src="https://github.com/everviolet/.github/raw/main/assets/logo-circle.png" width="100" alt="Logo"/><br/>
	Evergarden for <a href="https://spicetify.app/">Spicetify</a>
</h3>

<p align="center">
	<a href="https://github.com/everviolet/spicetify/stargazers"><img src="https://img.shields.io/github/stars/everviolet/spicetify?style=for-the-badge&colorA=313B40&colorB=DBBC7F"></a>
	<a href="https://github.com/everviolet/spicetify/issues"><img src="https://img.shields.io/github/issues/everviolet/spicetify?style=for-the-badge&colorA=313B40&colorB=E69875"></a>
	<a href="https://github.com/everviolet/spicetify/contributors"><img src="https://img.shields.io/github/contributors/everviolet/spicetify?style=for-the-badge&colorA=313B40&colorB=97C9C3"></a>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/everviolet/spicetify/main/assets/previews/preview.webp"/>
</p>

### Previews

<details>
<summary>Winter</summary>
<img src="https://raw.githubusercontent.com/everviolet/spicetify/main/assets/previews/winter.webp"/>
</details>
<details>
<summary>Fall</summary>
<img src="https://raw.githubusercontent.com/everviolet/spicetify/main/assets/previews/fall.webp"/>
</details>
<details>
<summary>Spring</summary>
<img src="https://raw.githubusercontent.com/everviolet/spicetify/main/assets/previews/spring.webp"/>
</details>

### Usage

1. Clone the repository and copy the `evergarden/` folder to the `Spicetify/Themes/` directory:
```sh
git clone --depth 1 https://github.com/everviolet/spicetify evergarden-spicetify && cd evergarden-spicetify
cp -r evergarden ~/.config/spicetify/Themes/
```

2. Set `current_theme` and `color_scheme` (`winter`/`fall`/`spring`/`summer`):
```sh
spicetify config current_theme evergarden
spicetify config color_scheme fall
spicetify config inject_css 1 inject_theme_js 1 replace_colors 1 overwrite_assets 1
spicetify apply
```

> [!NOTE]
> To set a custom accent color, go to the spotify settings page and select your preferred accent colour in the dropdown.

### Thanks to <3

- (Creator) [davidbgonz](https://github.com/davidbgonz)
- (Style) - [OlaoluwaM](https://github.com/OlaoluwaM)
- (Style) - [ghostx31](https://github.com/ghostx31)
- (Style/Extension) - [OhItsTom](https://github.com/ohitstom)
- (Porting to evergarden) [comfysage](https://github.com/comfysage)

<hr>

<p align="center">
	<a href="https://github.com/comfysage/evergarden/blob/mega/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=LICENSE&message=GPL3&colorA=313B40&colorB=9BB5CF"/></a>
<
