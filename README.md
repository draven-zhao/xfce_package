xfce
Mac 桌面下载 https://www.opencode.net/lsteam/xfce-big-sur-setup-file
安装 WhiteSur-gtk-theme https://github.com/vinceliuice/WhiteSur-gtk-theme
安装 WhiteSur-icon-theme  https://github.com/vinceliuice/WhiteSur-icon-theme
安装 WhiteSur-cursors  https://github.com/vinceliuice/WhiteSur-cursors
安装和配置 Rofi Launcher sudo pacman -S rofi https://github.com/adi1090x/rofi
安装和配置 LightDM-Webkit2-Greeter sudo pacman -S lightdm-webkit2-greeter主题 https://github.com/manilarome/lightdm-webkit2-theme-glorious
安装 Comice 控制中心 https://github.com/libredeb/comice-control-center


00:00 - 介绍
00:10 - 最终结果
02:24 - 初始设置
04:03 - 安装和配置主题、图标、光标和字体
04:05 - 安装 WhiteSur-gtk-theme - https://github.com/ vinceliuice/WhiteS... 
05:49 - 安装 WhiteSur-icon-theme - https://github.com/vinceliuice/WhiteS... 
06:27 - 安装 WhiteSur-cursors - https://github.com/vinceliuice/ WhiteS... 
07:02 - 安装字体
08:52- 安装全局菜单安装 Vala-Appmenu manjaro/arch : pamac build vala-panel-appmenu-common-git vala-panel-appmenu-registrar-git vala-panel-appmenu-xfce-git sudo pacman -S appmenu-gtk-module启用 vala-appmenu 后执行此命令： xfconf-query -c xsettings -p /Gtk/ShellShowsMenubar -n -t bool -s true xfconf-query -c xsettings -p /Gtk/ShellShowsAppmenu -n -t bool -s true 
10:41 - 配置 Xfce 面板 | 下载 Xpple 菜单：https://www.pling.com/p/1529470/ 
16:35 - 安装和配置 Plank Dock sudo pacman -S plank
19:35 - 安装和配置 Rofi Launcher sudo pacman -S rofi 来源：https： //github.com/adi1090x/rofi 
20:29- 安装和配置 Ulauncher pamac build ulauncher
23:03 - 安装和配置 Conky pamac build conky-lua-nv sudo pacman -S jq curl
24:46 - 安装和配置 LightDM-Webkit2-Greeter sudo pacman -S lightdm-webkit2-greeter主题：https://github.com/manilarome/lightdm... 
28:29 - 安装和配置 Picom Compositor pamac build picom-ibhagwan-git 
30:17 - 自定义 Firefox Web 浏览器
32:01 - 自定义 Xfce 终端
35:09 - 安装 Nautilus 文件管理器 sudo pacman -S nautilus
36:12 - 安装 Comice 控制中心 git clone https://github.com/libredeb/comice-co...
sudo pacman -S util-linux gsettings-desktop-schemas wireless_tools iproute alsa-utils dbus-python sudo pacman -S python-pip sudo pip3 install -r requirements.txt ./comice-control-center 40:09
