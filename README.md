# KTRLBoy

Current release notes: Alpha v1.4 (`1.4.0-alpha`)

KTRLBoy is a StreamElements-inspired chatbot launcher for Twitch, YouTube, and Kick. It supports streamer-owned authorization flows, a simplified GUI dashboard, command management, automation, and moderation setup.

## Alpha v1.4 Highlights

- Simplified dashboard: Dashboard, Connections, Commands, Automation, and Moderation.
- Consumer login install page so streamers can authorize KTRLBoy for their own chats from `/install`.
- Client-side Client ID saving in the Connections setup flow.
- HTTPS support for the GUI, install page, launcher API, and OAuth callbacks.
- Windows launcher self-test coverage for HTTP and HTTPS startup.

## Verification

- `npm.cmd run check`
- `npm.cmd run test:local`
- `npm.cmd run test:https`
- `npm.cmd run test:ktrl-service`
- `npm.cmd run test:streamer-auth`
- `npm.cmd run test:chat-commands`
- `npm.cmd run build:exe`
- `dist\KTRLBoy\KTRLBoy.exe --self-test --no-browser`

## Local v1.4 Artifact

The Alpha v1.4 executable package was built and verified locally as `KTRLBoy.zip` with SHA-256 `7DA71A673EFD99C0BD938FA48C6FDCC21031DDBBE1CFFF621206F9530741DD42`.
