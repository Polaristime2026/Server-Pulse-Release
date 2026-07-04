# ServerPulse Release

Public release assets for token-free ServerPulse test installs.

## Install

```bash
curl -fsSL https://github.com/Polaristime2026/Server-Pulse-Release/releases/download/v0.2.0/install-panel.sh \
  | sudo env \
      SERVERPULSE_SOURCE_URL=https://github.com/Polaristime2026/Server-Pulse-Release/releases/download/v0.2.0/serverpulse-lite.tar.gz \
      SERVERPULSE_DOCKER_MIRROR=cn \
      SERVERPULSE_INSTALL_MODE=lite \
      bash
```

This lite release uses prebuilt runtime artifacts and Docker Hub mirror configuration for China-friendly 1C1G test installs.
