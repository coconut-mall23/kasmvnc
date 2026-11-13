
# GeForce NOW in GitHub Codespaces

Open this repository in a Codespace. The dev container starts Chromium and
automatically opens the forwarded browser on port 3000. Sign in to GeForce NOW
and start a game.

The browser profile is saved in `.chrome-data` so your sign-in survives Codespace
restarts. The display defaults to 1280x720 at 60 FPS to reduce decoding and
forwarding load; increase the `CUSTOM_RES_W` and `CUSTOM_RES_H` values in
`.devcontainer/devcontainer.json` if your Codespace handles higher resolutions
smoothly.

Codespaces does not provide a GPU, and its forwarded browser is not optimized
for low-latency game streaming. GeForce NOW may perform better or may not work
as expected compared with a supported local device and browser.



