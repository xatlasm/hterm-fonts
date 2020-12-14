# hterm-fonts

Inspired by [Powerline Web Fonts](https://github.com/wernight/powerline-web-fonts), this is a hack for enabling the font that I like (MesloLGS NF, used in [powerlevel-10k](https://github.com/romkatv/powerlevel10k)) in the ChromeOS / Crostini terminal emulator.

## Installation

1. Open the Linux Terminal on ChromeOS
2. Open the dev console for the terminal window. A trick that works for me:
    - Right-click the top bar of the window
    - Click Reload
    - Press Enter and immediately press `Search` (aka `CapsLock`) + `+` to bring up the Dev Console. You might have to try a couple times if you don't get the timing right.
3. In the Dev Console terminal, enter the following:

```javascript
term_.prefs_.set('font-family', '"Source Code Pro", monospace');
term_.prefs_.set('user-css', 'https://cdn.jsdelivr.net/gh/xatlasm/hterm-fonts/webfonts.css');
```
4. Done!
