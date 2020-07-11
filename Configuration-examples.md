


#### alacritty
- Repo: https://github.com/aaron-williamson/base16-alacritty


Example configuration:

```yaml
alacritty:
enabled: true
files:
  default:
  path: ~/.config/alacritty/alacritty.yml
  mode: replace
  start_marker: "# <<<<<<<<<<"
  end_marker: "# >>>>>>>>>>"
```

Replace the theme defition in the Alacritty onfig file by:

```
# <<<<<<<<<<
# >>>>>>>>>>
```

#### binary-ninja
- Repo: https://github.com/evanrichter/base16-binary-ninja

Example configuration:
```

//TODO

```
#### blink
- Repo: https://github.com/niklaas/base16-blink.git

Example configuration:
```

//TODO

```
#### c_header
- Repo: https://github.com/m1sports20/base16-c_header

Example configuration:
```

//TODO

```
#### concfg
- Repo: https://github.com/h404bi/base16-concfg

Example configuration:
```

//TODO

```
#### conemu
- Repo: https://github.com/martinlindhe/base16-conemu

Example configuration:
```

//TODO

```
#### console2
- Repo: TODO

Example configuration:
```

//TODO

```
#### crosh
- Repo: TODO

Example configuration:
```

//TODO

```
#### dunst
- Repo: TODO

Example configuration:
```

//TODO

```
#### emacs
- Repo: TODO

Example configuration:
```

//TODO

```
#### fzf
- Repo: TODO

Example configuration:
```

//TODO

```
#### gnome-terminal
- Repo: TODO

Example configuration:
```

//TODO

```
#### godot
- Repo: TODO

Example configuration:
```

//TODO

```
#### gtk2
- Repo: TODO

Example configuration:
```

//TODO

```
#### highlight
- Repo: TODO

Example configuration:
```

//TODO

```
#### html-preview
- Repo: TODO

Example configuration:
```

//TODO

```
#### i3
- Repo: TODO

Example configuration:
```

//TODO

```
#### i3status-rust
- Repo: TODO

Example configuration:
```

//TODO

```
#### iterm2
- Repo: TODO

Example configuration:
```

//TODO

```
#### jetbrains
- Repo: TODO

Example configuration:
```

//TODO

```
#### joe
- Repo: TODO

Example configuration:
```

//TODO

```
#### kakoune
- Repo: TODO

Example configuration:
```

//TODO

```
#### kitty
- Repo: TODO

Example configuration:
```

//TODO

```
#### konsole
- Repo: TODO

Example configuration:
```

//TODO

```
#### mintty
- Repo: TODO

Example configuration:
```

//TODO

```
#### monodevelop
- Repo: TODO

Example configuration:
```

//TODO

```
#### prism
- Repo: TODO

Example configuration:
```

//TODO

```
#### prompt-toolkit
- Repo: TODO

Example configuration:
```

//TODO

```
#### putty
- Repo: TODO

Example configuration:
```

//TODO

```
#### pygments
- Repo: TODO

Example configuration:
```

//TODO

```
#### pywal
- Repo: TODO

Example configuration:
```

//TODO

```
#### qtcreator
- Repo: TODO

Example configuration:
```

//TODO

```
#### qutebrowser
- Repo: https://github.com/theova/base16-qutebrowser

Example configuration:

```yaml
qutebrowser:
  enabled: true
  files:
    default:
    path: ~/.config/qutebrowser/theme.py
    mode: rewrite
```

Example qutebrowser configuration:

```python
config.source('theme.py')
```

#### radare2
- Repo: TODO

Example configuration:
```

//TODO

```
#### rofi
- Repo: TODO

Example configuration:
```

//TODO

```
#### shell
- Repo: TODO

Example configuration:
```

//TODO

```
#### scide
- Repo: TODO

Example configuration:
```

//TODO

```
#### st
- Repo: TODO

Example configuration:
```

//TODO

```
#### stumpwm
- Repo: TODO

Example configuration:
```

//TODO

```
#### styles
- Repo: TODO

Example configuration:
```

//TODO

```

#### sway
- Repo: https://github.com/rkubosz/base16-sway

Example configuration:
```yaml
sway:
  enabled: true
  hook: swaymsg reload
  files:
    colors:
      path: ~/.config/sway/theme.conf
      mode: rewrite
```

Add into sway config:
```
include theme.conf

# Basic color configuration using the Base16 variables for windows and borders.
# Property Name         Border  BG      Text    Indicator Child Border
client.focused          $base05 $base0D $base00 $base0D $base0D
client.focused_inactive $base01 $base01 $base05 $base03 $base01
client.unfocused        $base01 $base00 $base05 $base01 $base01
client.urgent           $base08 $base08 $base00 $base08 $base08
client.placeholder      $base00 $base00 $base05 $base00 $base00
client.background       $base07
```

If you use statusbar, add the following into the bar section:
```
colors {
    background $base00
    separator  $base01
    statusline $base04

    # State             Border  BG      Text
    focused_workspace   $base05 $base0D $base00
    active_workspace    $base05 $base03 $base00
    inactive_workspace  $base03 $base01 $base05
    urgent_workspace    $base08 $base08 $base00
    binding_mode        $base00 $base0A $base00
}
```

#### telegram-desktop
- Repo: TODO

Example configuration:
```

//TODO

```
#### termite
- Repo: TODO

Example configuration:
```

//TODO

```
#### termux
- Repo: TODO

Example configuration:
```

//TODO

```
#### textmate
- Repo: TODO

Example configuration:
```

//TODO

```
#### tmux
- Repo: TODO

Example configuration:
```

//TODO

```
#### tilix
- Repo: TODO

Example configuration:
```

//TODO

```
#### vim
- Repo: TODO

Example configuration:
```

//TODO

```
#### vis
- Repo: TODO

Example configuration:
```

//TODO

```
#### vscode
- Repo: TODO

Example configuration:
```

//TODO

```
#### windows-command-prompt
- Repo: TODO

Example configuration:
```

//TODO

```
#### xcode
- Repo: TODO

Example configuration:
```

//TODO

```
#### xfce4-terminal
- Repo: TODO

Example configuration:
```

//TODO

```
#### xresources
- Repo: TODO

Example configuration:
```

//TODO

```
#### xshell
- Repo: TODO

Example configuration:
```

//TODO

```
#### zathura
- Repo: TODO

Example configuration:
```

//TODO

```
