# SonyBoy Spotify Theme

### I've been using the [Comfy Theme](https://github.com/Comfy-Themes/Spicetify) by [kyrie25](https://github.com/kyrie25) for a long time now. Finally, I decided to customize it for me.

### Here's what came out of it:

![example](https://raw.githubusercontent.com/JustRomacH/SonyBoy-SpotifyTheme/master/Images/example_1.png)

---

## Installation

- #### Spicetify (Powershell):

```powershell
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex

iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.ps1 | iex
```

- #### Spicetify (Bash):

```bash
curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.sh | sh

curl -fsSL https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.sh | sh
```

- #### Theme:

  - Download the repository

  - Move the "SonyBoy_Theme" folder to %USERPROFILE%\\.spicetify\Themes

- #### Theme (Powershell):

```powershell
cd %USERPROFILE%\.spicetify\Themes

git clone https://github.com/JustRomacH/SonyBoy-SpotifyTheme

spicetify config current_theme SonyBoy_Theme

spicetify apply
```

- #### Theme (Bash):

```bash
cd "$(dirname "$(spicetify -c)")/Themes

spicetify config current_theme SonyBoy_Theme

spicetify apply
```
