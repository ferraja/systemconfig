个人习惯配置，对外没有太大的实际意义。

This repository appeals to personal configurations on linux only, so it may hit nothing for you. Have a nice day! 

**文档、仓库都可能未及时更新，提醒未来的自己，勿无脑使用。**

# v2raya

[install wiki](https://github.com/v2rayA/v2rayA/wiki/%E4%BD%BF%E7%94%A8%E6%96%B9%E6%B3%95)

# gnome

- gnome-tweak-tool

- gnome-shell-extensions

- 
  chrome-gnome-shell

#### 外观配置

- WhiteSur Gtk Theme: https://www.gnome-look.org/p/1403328/ （including icons and cursor）
- gnome-shell style: https://github.com/vinceliuice/Sierra-gtk-theme
- 字体Monaco_Linux-Powerline.ttf

#### gnome插件

- [Dash to dock](https://extensions.gnome.org/extension/307/dash-to-dock/) 定制dock
- [User themes](https://extensions.gnome.org/extension/19/user-themes/) 定制gnome-shell主题
- [Ibus font setting](https://extensions.gnome.org/extension/1121/ibus-font-setting/) 放大输入法字体
- [Good Bye GDM3 Login](https://extensions.gnome.org/extension/3037/good-bye-gdm-flick/) 隐藏登录时的紫色动画
-  [TopIcons Plus](https://extensions.gnome.org/extension/1031/topicons/) 使用deepin-wine系列国产软件时在顶部栏显示qq、微信图标，没有的话qq微信非常难用

# files

该有的仓库里都有，没有就是忘记传了或者不该有。

- chloginbg: 改变登录时的背景，Ubuntu20.04LTS手动改图片已经不行了，或者说不太方便直接。[源于github仓库](https://github.com/thiggy01/change-gdm-background)
- vimrc: 目前只会用来做一些简单的编辑，所以配置也很少，习惯在root下配置，从`/usr/share/vim/vimrc`拷贝来的。
- .zshrc: 配置得也很少，对这些要求不高，通常是加入了一些path
- rclone: 用来连接云存储服务做同步盘，云存储现在是在google drive和阿里云oss中摇摆。[rclone github repo](https://github.com/rclone/rclone)
- flameshot: 截图工具
- synccloudservice: 关机时将本地数据同步到云端。在systemd中调用rclone需要有`/root/.config/rclone/rclone.conf`配置文件，用户级配置的数据保存在用户目录下，用链接导过去。

# system settings

- 切换桌面的快捷键`Alt + 1/2/3/4`
- 截图快捷键`PtrSc`，把系统默认的所有使用内置截图工具的快捷键都禁用
- 输入法切换`Ctrl + Space`

# 终端字典

`sudo apt install sdcv`

字典库见仓库 stardict-oxford-gb.2.4.2

