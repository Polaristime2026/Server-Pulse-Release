# ServerPulse Release

Public release assets for token-free ServerPulse test installs.

## Install

```bash
curl -fsSL https://github.com/Polaristime2026/Server-Pulse-Release/releases/download/v0.2.1/install-panel.sh | sudo env SERVERPULSE_SOURCE_URL=https://github.com/Polaristime2026/Server-Pulse-Release/releases/download/v0.2.1/serverpulse-lite.tar.gz SERVERPULSE_DOCKER_MIRROR=cn SERVERPULSE_INSTALL_MODE=lite bash
```

This lite release uses prebuilt runtime artifacts, installs missing Docker Compose, and configures Docker Hub mirror mode for China-friendly 1C1G test installs.
