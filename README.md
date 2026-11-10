# TamBoy

A browser-based handheld game player for Game Boy, Game Boy Color, and NES ROMs (`.gb`, `.gbc`, `.nes`).

ROMs are read locally and never uploaded. Uses [jsnes](https://github.com/bfirsh/jsnes) for NES and [WasmBoy](https://github.com/torch2424/wasmboy) for Game Boy / Game Boy Color, loaded from jsDelivr.

## Run

Open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server
```

## Controls

- Arrows / WASD: move
- X: A, Z: B
- Enter: Start, Shift: Select
- P: pause, `-` / `+`: volume
- Drag and drop a ROM onto the screen; USB and Bluetooth gamepads work too.

Features: save/load states, battery saves (IndexedDB), auto-start past title screens, full screen.
