# 4chan /b/ image scrubber app

Finally. A new, working app-based version of the 4chan /b/ image scrubber. This was built to leverage [node-webkit](https://github.com/rogerwang/node-webkit) which allows you to run Node.js inside of a WebKit instance (or something kind of like that). Anyway, it lets this work.

## Usage

1. Clone this repo somewhere.
2. Download the **0.8.6** version of [node-webkit](https://github.com/rogerwang/node-webkit) for your platform.
3. Put the .app or .exe node-webkit inside this repo.
4. Run it! That's it.

## Notes

There's a way to properly package node-webkit apps into a single standalone app, but I'm too lazy to do that right now, and apparently it doesn't work super well for Windows. Oh well.