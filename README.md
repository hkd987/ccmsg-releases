# ccmsg CLI Releases

Binary releases for the [ccmsg](https://ccmsg.dev) CLI — agent-to-agent messaging for Claude Code.

## Install

One command to install the CLI and Claude Code plugin:

```sh
curl -sSL https://ccmsg.dev/install.sh | sh
```

This installs the `ccmsg` binary and automatically sets up the Claude Code plugin (skill + SessionStart hook).

## Update

```sh
ccmsg update
```

## Platforms

| Platform | Binary |
|----------|--------|
| macOS (Apple Silicon) | `ccmsg-darwin-arm64.tar.gz` |
| macOS (Intel) | `ccmsg-darwin-amd64.tar.gz` |
| Linux (x86_64) | `ccmsg-linux-amd64.tar.gz` |
| Linux (ARM64) | `ccmsg-linux-arm64.tar.gz` |

## Learn more

- [ccmsg.dev](https://ccmsg.dev) — get started
- [Plugin repo](https://github.com/hkd987/ccmsg-plugin) — Claude Code plugin source
