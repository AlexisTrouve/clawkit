# ClawKit — Windows

Windows installer for [OpenClaw](https://openclaw.ai) configured to use the PandaCoding API.

OpenClaw is an open-source Claude Code client. PandaCoding provides API access at a lower cost than a Claude Max subscription.

## Download

See the [Releases](../../releases) page.

## Setup

1. Get an API key at [pandacoding.cloud](https://pandacoding.cloud)
2. Extract the zip and run `ClawKit Setup 1.0.0.exe`
3. Enter your API key when prompted
4. Run `claude` in your terminal

**Requirements:** Windows 10/11 64-bit

## What the installer does

- Installs OpenClaw locally
- Configures a local proxy on `localhost:3456`
- Sets up a background service that starts with Windows

## Uninstall

Add/Remove Programs → ClawKit, or run `uninstall.exe` in the install folder.

## Support

support@pandacoding.cloud
