### [Alacritty](https://github.com/alacritty/alacritty)

#### Install using Git

If you are a git user, you can install the theme by cloning the repo:

    $ git clone https://github.com/getomni/alacritty.git

#### Install manually

Download using the [GitHub .zip download](https://github.com/getomni/alacritty/archive/main.zip) option and unzip them.

#### Activating theme

1. Copy the `omni.yml` file to your `alacritty` config folder - `~/.config/alacritty` for example
2. Edit the Alacritty config file by adding:
```yaml
import:
  - ./omni.yml
```
3. Alacritty reloads the config automagically
