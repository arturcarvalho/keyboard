# keyboard

- M1: Next song
- M2: Create screenshot to paste: `Shift + Ctrl + Cmd + 4`
- M3: Create screenshot window: `Shift + Cmd + 4`
- M5: Toggle dock: `Options + Cmd + D`
- The F keys have priority, Im just ignoring the media keys

- Put lock on the left to not be hit by mistake so often (too close to del and F12)
- Double ctrl. For the moment there are 2 controls to the left. Still not sure what to do here, but for the moment it will work like this.

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
