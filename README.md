# TCR Demo

The setup that Kent Beck's setup is for `Python`, the following works for `Swift`.

To have this setup, hit the `CMD + Shift + P`, type in "settings.json", choose the one that says user's settings, and the add the following to your settings.

```
    "runOnSave.commands": [
        {
            "command": "clear; swift test | xcpretty && git commit -am working || git reset --hard",
            "runIn": "terminal"
        }
    ],
```

`runOnSave` is a vscode extension, this [one]()
