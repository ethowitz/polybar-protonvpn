## Dependencies
This script requires:
    * [font awesome](https://fontawesome.com) to be specified in your polybar config
    * The [Protonvpn Linux CLI](https://github.com/ProtonVPN/linux-cli)

## Usage

Create a custom module in your polybar config file like so:
```
[module/protonvpn]
type = custom/script
exec = $XDG_CONFIG_HOME/polybar/scripts/polybar-protonvpn.sh
interval = 5
```

