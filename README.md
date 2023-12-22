# TCR Demo

Kent Beck's setup is for `Python`, the following works for `Swift`.
He also uses a Formatting tool (which I love `Black` for Python), you can set up `SwiftFormat` for Swift.</br>
[Here](https://github.com/TheAlienMann/SwiftLintingConfig) you can find my setup for it.

To have this setup, hit the `CMD + Shift + P`, type in "settings.json", choose the one that says user's settings, and the add the following to your settings.

```
    "runOnSave.commands": [
        {
            "command": "clear; swift build | swift test && git commit -am working || git reset --hard",
            "runIn": "terminal"
        }
    ],
```

`runOnSave` is a vscode extension, this [one](https://marketplace.visualstudio.com/items?itemName=pucelle.run-on-save)

Funny, since the `swift build` was failing, I just lost the link above and I had to put the link there again. I think I should exclude non-swift files. 🤦‍♂️
