# Hiren's BootCD PE in GitHub Codespaces

Run **Hiren's BootCD PE** inside a **GitHub Codespace** using **Docker**, **QEMU**, and **noVNC** so you can access the boot screen and PE environment directly from your browser.

## How It Works

* **Docker Container:** Runs the container stack and exposes the web/VNC port so Codespaces can forward the display.
* **QEMU Virtual Machine:** Boots the Hiren's BootCD PE ISO inside a virtualized `x86_64` environment.
* **noVNC Browser Client:** Serves the virtual display over HTML5 in your browser so you can interact with the VM.

## Quick Start

1. **Open a GitHub Codespace** from the `hirens-bootcd-githubcodespaces` repository and wait for the terminal to finish loading.
2. **Start the container stack:**
   ```bash
   docker compose up -d
##
Link https://littledummy445.github.io/hirens-bootcd-githubcodespaces/
