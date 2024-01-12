# keyboard

- The F keys have priority
- I'm not using a specific layer for windows. Press the M2 to toggle between layer 2 and 0. (layer 2 is the numpad layer for the moment)

- Put lock on the left to not be hit by mistake so often (too close to del and F12)
- M1 (together with bindings below) moves cursor 10 lines up/down
```JSON
  {
    "key": "ctrl+shift+up",
    "command": "cursorMove",
    "args": {
      "to": "up",
      "by": "line",
      "value": 10
    },
    "when": "editorTextFocus"
  },
  {
    "key": "ctrl+shift+down",
    "command": "cursorMove",
    "args": {
      "to": "down",
      "by": "line",
      "value": 10
    },
    "when": "editorTextFocus"
  },
  ```

- M5 / go to line on vscode / ctrl + g
- M15 / cmd+space / now used for the moment
- Double ctrl. For the moment there are 2 controls to the left. Still not sure what to do here, but for the moment it will work like this.
