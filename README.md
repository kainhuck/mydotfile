- 这是我的i3wm配置，参考多位大神的配置，综合而成

- 系统： manjaro i3

## alacritty

安装

```
pacman -S alacritty
```

配置文件直接使用即可

alacritty配色参考



## i3

直接使用即可

注意：我绑定了一些快捷键，你们可能没有安装这些应用

| 快捷键        | 应用                         |
| ------------- | ---------------------------- |
| $mod + Return | alacritty                    |
| Alt + k       | deepin-screenshot            |
| $mod + o      | qq                           |
| $mod + i      | electron-netease-cloud-music |
| $mod + F2     | google-chrome-stable         |
| $mod + F3     | firefox                      |
| $mod + d      | rofi                         |
| $mod + c      | vscode                       |

另外`$mod + Shift + Return`我改成了打开`pcmanfm`manjaro i3自带的文件管理器

## polybar

安装

```
pacman -S polybar
```



参考大神`dwt1`的配置，项目地址

https://gitlab.com/dwt1/dotfiles/tree/master/.config/polybar

## vim

参考

https://github.com/humiaozuzu/dot-vimrc

## neofetch & rofi

```
pacman -S neofetch rofi
```

配置直接使用即可

参考大神`da-edra`

https://github.com/da-edra/dotfiles

## oh-my-zsh主题

https://github.com/Powerlevel9k/powerlevel9k

## 字体

```
pacman -S ttf-dejavu
pacman -S ttf-droid
pacman -S ttf-font-awesome
pacman -S ttf-font-icons
pacman -S ttf-font-logos
pacman -S wqy-microhei
pacman -S adobe-source-han-sans-cn-fonts
pacman -S powerline-fonts
```