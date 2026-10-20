# Holm releases

Official [Holm](https://holmhq.com) binaries, checksums, and signed release manifests. [Get the latest release](https://github.com/holmhq/releases/releases/latest).

## Install and try

On Linux or macOS (`amd64` or `arm64`), [review the installer](https://holmhq.com/install.sh), then run:

```sh
curl -fsSL https://holmhq.com/install.sh | bash
export PATH="$HOME/.local/bin:$PATH"
holm --version
holm license show
holm --help
```

Choose **3 — CLI Only** to explore without starting a server. For a disposable node on Linux with systemd, choose **2 — Local Development** and open the dashboard URL printed by the installer. That mode uses `dev/dev` on a local network IP; use it only on a trusted network.

Read the [Holm Usage License Agreement](https://license.holmhq.com/v1/) and accept it yourself when prompted; agents should not auto-accept. For instance setup and first CLI operations, follow the [agent quickstart](https://holmhq.com/llms-full.txt).
