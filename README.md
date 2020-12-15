# hterm-fonts

Inspired by [Powerline Web Fonts](https://github.com/wernight/powerline-web-fonts), this is a hack for enabling the font that I like (MesloLGS NF, used in [powerlevel-10k](https://github.com/romkatv/powerlevel10k)) in the ChromeOS / Crostini terminal emulator.

![image](https://user-images.githubusercontent.com/6387989/102071507-e58ebd00-3e43-11eb-9e5c-a86c0cbb053c.png)

## Installation

1. Open the Linux Terminal on ChromeOS
2. Open the Dev Console for the terminal window (`Ctrl`+`Shift`+`J`)
3. In the Dev Console terminal, enter the following:

```javascript
term_.prefs_.set("font-family", '"Source Code Pro", monospace')
term_.prefs_.set(
  "user-css",
  "https://cdn.jsdelivr.net/gh/xatlasm/hterm-fonts/webfonts.css"
)
```
