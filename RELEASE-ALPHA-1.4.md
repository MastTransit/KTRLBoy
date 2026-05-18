# KTRLBoy Alpha 1.4

Release version: `1.4.0-alpha`

## Highlights

- Simplified the dashboard into five main sections: Dashboard, Connections, Commands, Automation, and Moderation.
- Added consumer login installs so streamers can authorize KTRLBoy for their own chats from `/install`.
- Fixed Client ID saving in the Connections client setup flow and added visible save confirmation.
- Added HTTPS support for the local GUI, launcher API, install page, and OAuth callbacks.
- Added local certificate generation with `npm.cmd run cert:https` and HTTPS smoke coverage with `npm.cmd run test:https`.
- Updated the Windows executable launcher so it can self-test HTTP and HTTPS startup.

## Verification

- `npm.cmd run check`
- `npm.cmd run test:local`
- `npm.cmd run test:https`
- `npm.cmd run test:ktrl-service`
- `npm.cmd run test:streamer-auth`
- `npm.cmd run test:chat-commands`
- `npm.cmd run build:exe`
- `dist\KTRLBoy\KTRLBoy.exe --self-test --no-browser`

## Artifact

The local Alpha v1.4 package is `KTRLBoy.zip` with SHA-256 `7DA71A673EFD99C0BD938FA48C6FDCC21031DDBBE1CFFF621206F9530741DD42`.
