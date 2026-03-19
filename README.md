# .files
![Setup example](.repo_assets/setup.png)

dotfiles for my laptop

refined specifically for my laptop [14 inch macbook pro]

required:
- [niri](https://github.com/yalter/niri) ^v25.11
- [danklinux dotfile setup](https://danklinux.com) (DMS ^v1.2)
- [Bibata Modern Classic cursor](https://store.kde.org/p/1914825) wherever you store your cursors (e.g `~/.local/share/icons`)

recommended for all keybinds to work:
- hyprpicker
- zsh
- [Emote](https://flathub.org/en/apps/com.tomjwatson.Emote) emoji picker Flatpak
- wl-copy and wl-paste
- notify-send
- playerctl
- systemd/logind

if you have something that's not the laptop i have you'll probably need to change the display settings. as of late you should just be able to do this in niri

### icon pack (wip)
i'm working on an icon pack for all the apps i use regularly. if you'd like to download them for use on your own system, you can access them [here](https://www.figma.com/design/qJG0yo15zWKf12Md6LFWJJ/mycons?node-id=0-1&t=FxKJavxTBZunUTlH-1). i export them as 960px pngs (due to using a lot of complex SVG things i'm not sure if niri can render) and they scale down nicely to 96px on the dock.

### how to install (more or less)
- when installing danklinux, make sure to select niri as your window manager and ghostty as your terminal
- copy `DankMaterialShell`, `fastfetch`, `niri`, and `hyfetch.json`into your `$XDG_CONFIG_HOME` folder
- copy `userChrome.css` in `firefox_css` folder into the `chrome` folder in your Firefox userprofile directory (make sure stylesheets are enabled)
- copy the scripts in `scripts` to `~/.local/bin` or wherever you like
- add `appledrm.show_notch=1` to your kargs to enable notched rendering
- !!! important for sleep key function like in macos !!!: copy `/usr/lib/systemd/logind.conf` to `/etc/systemd/logind.conf`, uncomment `HandleSuspendKey`, and set it to `ignore`, then reboot
- set your wallpaper to `wallpaper.png` if you like :3


### extra things:
- laptop: 14 inch macbook pro 2021
- distro: Fedora Workstation Asahi Remix 43
- shell: DankMaterialShell
- music player: Gapless
- fetch thing(??): hyfetch + fastfetch
- browser: Zen
- wallpaper: made with art from [@d6016.bsky.social](https://bsky.app/profile/d6016.bsky.social/post/3lcgyu6fohc2b)
- `userChrome.css` file inside `firefox_css` lowers minimum firefox width in order to make 33% look fine
