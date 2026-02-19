Assets live here under a subfolder per client.

Structure example:

assets/
  tpc1016/
    logo.png
    background.jpg
    sounds/
      join.mp3
      win.mp3

At runtime, the app resolves paths via config.assetPath(relative).

