<h1 align="center">
    <br>
    <img src="./media/tomato.gif" alt="tomatowelcome" width="175px">
    <img src="./media/coffee.gif" alt="tomatocoffee" width="175px">
    <img src="./media/machine.gif" alt="tomatomachine" width="175px">
    <img src="./media/beach.gif" alt="tomatobeach" width="175px">
    <br>
    Tomato.C
    <br>
</h1>

<h4 align="center">A pomodoro timer written in pure <a href="https://www.open-std.org/JTC1/SC22/WG14/www/standards" target="_blank">C</a>.</h4>

<p align="center">
<a href="./LICENSE"><img src="https://img.shields.io/badge/license-GPL-3.svg" alt="License"></a>
<a href="https://www.buymeacoffee.com/gabrielzschmitz" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 20px !important;width: 87px;" ></a>
<a href="https://github.com/gabrielzschmitz/Tomato.C"><img src="https://img.shields.io/github/stars/gabrielzschmitz/Tomato.C?style=social" alt="Give me a Star"></a>
</p>

<p align="center">
  <a href="#-how-to-install">How to Install</a> •
  <a href="#-how-to-use">How to Use</a> •
  <a href="#%EF%B8%8F-controls-and-preferences">Controls and Preferences</a> •
  <a href="#-the-pomodoro-method">The Pomodoro Method</a> •
  <a href="#-to-do">To-do</a> •
  <a href="#-dependencies">Dependencies</a> •
  <a href="#-contribute">Contribute</a> •
  <a href="#-license">License</a>
</p>

## 💾 How to Install
<b>Note</b>: a good practice is to clone the repo at <i>$HOME/.local/src/</i>
```
$ git clone https://github.com/gabrielzschmitz/Tomato.C.git
$ cd Tomato.C
$ sudo make install
```

## 🚀 How to Use
Just <b>type it</b> in the <b>terminal</b>:
```
$ tomato
```

<b>Tip:</b> For the best terminal resolution use [setsid](https://man7.org/linux/man-pages/man1/setsid.1.html) (the geometry depends on your font size):
```
$ setsid -f "$TERMINAL" -g 33x21 -c tomato -e tomato
```

## 🕹️ Controls and Preferences
<img src="./media/preferences.gif" alt="preferences" width="210px" align="right">

Use the following <b>keys</b> to <b>control</b> the application:

 * <b><i>Arrows or VIM Keys:</i></b> To move and select;
 * <b><i>ENTER:</i></b> To select;
 * <b><i>CTRL+X:</i></b> To return to the main menu wherever you are;
 * <b><i>ESC or Q:</i></b> To quit.

You can configure the following settings:

 * <b><i>Pomodoros Amount</i></b>;
 * <b><i>Work Time</i></b>;
 * <b><i>Short Pause Time</i></b>;
 * <b><i>Long Pause Time</i></b>.

## 🍅 The Pomodoro Method
<img src="./media/tomatomethod.gif" alt="tomatomethod" width="210px" align="right">

The technique basically consists of using a timer to break down work into <b>intervals</b>, follow the <b>steps</b>:

 1. Get a <b>to-do list</b>;

 2. Start [Tomato.C](https://github.com/gabrielzschmitz/Tomato.C) and focus on a <b>single task for 25 minutes</b> straight until notification pops up;

 3. Then <b>record what you completed</b> and enjoy a <b>5 minutes break</b>;

 4. After <b>4 pomodoros</b> (steps 2 and 3), take a longer, <b>30 minutes break</b>;

 5. <b>Restart</b>.

<b>Note</b>: the <b>timers</b> and the <b>amount of pomodoros can be changed</b> by the user.
## 📝 To-do
- [X] Make a welcome screen
- [X] Rewrite using ncurses
- [X] Implement input controls
- [X] Implement user options
- [X] Make it auto center
- [X] Add a notification sound
- [ ] Implement save current state
- [ ] Implement mouse support
- [ ] Implement simple note taking (maybe using a nvim instance)

## ⚓ Dependencies
It only needs [gcc](https://gcc.gnu.org/) to compile, [ncurses](https://invisible-island.net/ncurses/) as the graphic library, [dunst](https://github.com/dunst-project/dunst) to show notifications, [mpv](https://mpv.io/) for the notifications sounds and a [Nerd Font](https://www.nerdfonts.com/) for the icons.

<b>Note</b>: if you're using <b>WSL</b>, use the [wsl-notify-send](https://github.com/stuartleeks/wsl-notify-send) to get the notifications!

## 🤝 Contribute
Feel free to contribute to the project, the only requirement is to follow the commit tittle pattern:

 * File-Related-Emoji Tittle

## 📜 License
This software is licensed under the [GPL-3](./LICENSE) license.

