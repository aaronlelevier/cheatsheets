# Sublime Text

### Preference.sublime-settings - User

```json
{
    "font_size": 15,
    "ignored_packages":
    [
        "Vintage"
    ],
    "tab_size": 4,
    "translate_tabs_to_spaces": true
    "rulers": [80, 100],
}
```

### Shorcut Keys

On Menu Bar: **Sublime Text > Preferences > Key Bindings - User**

```json
[{
    "keys": ["pageup"],
    "command": "scroll_lines",
    "args": {
        "amount": 30.0
    }
}, {
    "keys": ["pagedown"],
    "command": "scroll_lines",
    "args": {
        "amount": -30.0
    }
}, { "keys": ["alt+s"], "command": "toggle_in_selection",
    "context": [{"key": "panel", "operand": "replace"}, {"key": "panel_has_focus"}]
}]
```

### 3rd Party Packages

[Install package control](https://packagecontrol.io/installation)

[PEP8 Autoformat](https://packagecontrol.io/packages/Python%20PEP8%20Autoformat)

[HTMLBeautify](https://packagecontrol.io/packages/HTMLBeautify)

[Javascript Beautify](https://packagecontrol.io/packages/Javascript%20Beautify)
