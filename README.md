# 🌆 wallcli

an interactive, fast cli tool to set image and video wallpapers on arch/endeavouros using mpvpaper and python. built it because dragging files manually is annoying and i use a terminal anyway.

---

## ✨ features

* **interactive menu:** shows a clean terminal menu to choose your wallpaper using questionary.
* **random mode:** instantly picks a random image or video from your folder.
* **permanent config:** saves your custom path to `~/.config/wallcli/config.conf` so you don't have to keep retyping it.
* **stop switch:** kills all active mpvpaper instances with one command.

---

## 🚀 installation

you can grab it from the aur using yay:

```bash
yay -S wallcli
```

---

## 🛠️ usage

just run the command to open the selection menu:

```bash
wallcli
```

### flags

| flag | long flag | what it does |
| :--- | :--- | :--- |
| `-s` | `--stop` | kills all running mpvpaper instances |
| `-r` | `--random` | sets a random wallpaper |
| `-p` | `--path` | pops up a prompt to change your wallpaper folder path |

---

## 📁 configuration

the script saves your path inside this file:
`~/.config/wallcli/config.conf`

---

## 🧰 dependencies

if you clone this locally make sure you have these installed:
* `python3`
* `mpvpaper`
* `python-questionary`
