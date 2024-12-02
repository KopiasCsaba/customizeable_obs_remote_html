# Simple Web based OBS  remote controller

This repository is a single HTML file, that connects to an OBS instance through websocket.

The point is to be able to create an easy-to-use remote control for OBS that anyone with access can use
to manage the live stream.

![screenshot.png](assets/screenshot.png)

Here is a [screen capture](https://github.com/KopiasCsaba/customizeable_obs_remote_html/raw/refs/heads/main/assets/obsremotescreencapture.mp4) as well.

You can customize the following things easily in the source:
 * host,port,password
 * Buttons (label, action, style)

With a bit more understanding you can also customize anything in it of course to your liking.
 
# Features
 * Simplicity
 * Customizability in code
 * Automatic connection & reconnection

# How to use
 * Download the [index.html](index.html) file.
 * Edit connection details first.
 * Open it up and let it connect.
 * Open the web developer toolbar (CTRL+SHIFT+K on firefox, CTRL+SHIFT+J on chrome)
 * Upon first connection there is a dump of hotkey names, scene ids and scene item ids. Use this information to edit the `const hotkeyButtons`.
 * Serve it locally on your device or with a webserver, but don't use https (can't connect to a non-secure websocket from https due to browser policies)
 * Enjoy!

