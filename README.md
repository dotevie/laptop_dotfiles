# .files
![Setup example](.repo_assets/setup.png)

dotfiles for my laptop

refined specifically for my laptop [14 inch macbook pro]

required:
- [niri](https://github.com/yalter/niri)
- [danklinux dotfile setup](https://danklinux.com)
- [Bibata Modern Classic cursor](https://store.kde.org/p/1914825) wherever you store your cursors

if you have something that's not the laptop i have you'll probably need to change the display settings in `niri/config.kdl`

### how to install (more or less)
- when installing danklinux, make sure to select niri as your window manager and ghostty as your terminal
- copy `DankMaterialShell`, `fastfetch`, `ghostty`, `niri`, `hyfetch.json`, and `quickshell` into your `$XDG_CONFIG_HOME` folder (make sure to make backups)
- if you're ok with having a bit of clutter in that folder you can just clone it in directly (e.g. `git clone https://github.com/dotevie.com/laptop_dotfiles $XDG_CONFIG_HOME`)
- copy `userChrome.css` in `firefox_css` folder into the `chrome` folder in your Firefox userprofile directory (make sure stylesheets are enabled)
- set your wallpaper to `wallpaper.png` if you like :3


### extra things:
- laptop: 14 inch macbook pro 2021
- OS: Fedora Workstation Asahi Remix 43 (with notched area rendering enabled)
- shell: DankMaterialShell
- music player: Gapless
- fetch thing(??): hyfetch + fastfetch
- browser: Zen
- wallpaper: made with art from [@d6016.bsky.social](https://bsky.app/profile/d6016.bsky.social/post/3lcgyu6fohc2b)
- `userChrome.css` file inside `firefox_css` lowers minimum firefox width in order to make 33% look fine
