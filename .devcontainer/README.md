# Dev Container

This directory contains the [Dev Container](https://containers.dev/) configuration for headscale.

## Configuration

- **Format details**: <https://aka.ms/devcontainer.json>
- **Config options / template reference**: <https://github.com/devcontainers/templates/tree/main/src/alpine>
- **Available features**: <https://containers.dev/features>
- **Guide for Dockerfile / Docker Compose**: <https://containers.dev/guide/dockerfile>
- **Non-root user info**: <https://aka.ms/dev-containers-non-root>

## Common Customizations

The following optional fields can be added to `devcontainer.json` as needed:

```json
{
  "forwardPorts": [],
  "postCreateCommand": "uname -a",
  "customizations": {},
  "remoteUser": "root"
}
```
