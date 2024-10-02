## Yorumi Themes for Alacritty

### Installation

Download the themes into `$HOME/.config/alacritty/themes`
```sh
curl -L -o /tmp/yorumi-abyss.toml https://github.com/yorumicolors/yorumi/blob/main/get/apps/terms/alacritty/yorumi-abyss.toml\?raw\=true
curl -L -o /tmp/yorumi-mist.toml https://github.com/yorumicolors/yorumi/blob/main/get/apps/terms/alacritty/yorumi-mist.toml\?raw\=true
mkdir -p $HOME/.config/alacritty/themes
mv /tmp/yorumi-{abyss,mist}.toml $HOME/.config/alacritty/themes
```

Import the theme of your choice in your `alacritty.toml` as follows:
```toml
import = [
    # ...
    "$HOME/.config/alacritty/themes/yorumi-[abyss|mist].toml"
    # ...
]
```

| <img src="/get/apps/terms/alacritty/res/yorumi-abyss_alacritty.png" /> | <img src="/get/apps/terms/alacritty/res/yorumi-mist_alacritty.png" /> |
| --- | --- |
| yorumi abyss | yorumi mist |

