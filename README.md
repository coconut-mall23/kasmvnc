
# Linux on codespaces

Instead of using codespaces to make a proxy, use codespaces as the proxy








## Installation

Run this command in termanal and press enter

```bash
 docker stop chromium >/dev/null 2>&1 || true && docker rm chromium >/dev/null 2>&1 || true && docker run -d --name=chromium --security-opt seccomp=unconfined -p 3000:3000 --shm-size=2gb -v ${containerWorkspaceFolder}/.chrome-data:/config -e CHROME_CLI=https://play.geforcenow.com lscr.io/linuxserver/chromium:latest
```
when a popup appears bottom right, press the green button and a new tab should open with geforce now already oppened
## Demo



