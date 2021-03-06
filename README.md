# Omni for [Windows Terminal](https://github.com/microsoft/terminal)

Omni is everywhere

**NOTES:**
- This is a Windows Terminal Theme inspired by [hyper-omni](https://github.com/getomni/hyper-omni)
- This theme works better with WSL Zsh if you want to know in how to customize your WSL terminal, 
  look at **[Terminal com Oh My Zsh, Spaceship, Dracula e mais - PT-BR](https://blog.rocketseat.com.br/terminal-com-oh-my-zsh-spaceship-dracula-e-mais/)**

![Preview of Omni Windows Terminal Theme](https://raw.githubusercontent.com/Avlye/omni-windows-terminal/master/windows-terminal.png)

## Install

Start Windows Terminal and click on down arrow symbol from menu bar and select Settings option, or use **Ctrl+,** shortcut.

In your **settings.json** file, find the **schemes** section and paste the content bellow.

```json

"schemes": [
    {
        "name": "Omni",

        "background": "#272935",
        "foreground": "#F8F8F2",
        "black": "#000000",
        "red": "#ff5555",
        "green": "#50fa7b",
        "yellow": "#effa78",
        "blue": "#bd93f9",
        "purple": "#ff79c6",
        "cyan": "#8d79ba",
        "white": "#bfbfbf",

        "brightBlack": "#4d4d4d",
        "brightRed": "#ff6e67",
        "brightGreen": "#5af78e",
        "brightYellow": "#eaf08d",
        "brightBlue": "#caa9fa",
        "brightPurple": "#ff92d0",
        "brightCyan": "#aa91e3",
        "brightWhite": "#e6e6e6",

        "cursorColor": "#f8f8f2",
        "selectionBackground": "#483C67"
    }
]

```

Note: Issue [Border color still not supported](https://github.com/microsoft/terminal/issues/3746)

## Activate

Now that the color scheme is defined, find your profiles section and add Omni as your default color scheme. Or alternative you can enable only in WSL.

Example #1: Define as your default color scheme.

```json
"profiles": {
    "defaults": {
      "colorScheme": "Omni"
    },
}
```

Example #2: Define the color scheme only in one profile.

```json
{
  "name": "Windows PowerShell",
  "commandline": "powershell.exe",
  "hidden": false,
  "colorScheme": "Omni"
}
```
