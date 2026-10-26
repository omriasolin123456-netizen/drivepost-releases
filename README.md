# DrivePost — Windows installers

This repository contains only DrivePost release files: Windows installers, SHA-256 checksums, release notes and signed
update metadata (`stable.json`). The source code is private.

- Latest installer: https://github.com/omriasolin123456-netizen/drivepost-releases/releases/latest
- DrivePost is a local Windows application. It runs on your computer; there is no hosted version.
- The installer is not Authenticode-signed; Windows SmartScreen may warn. Verify the SHA-256 published with each release.
- Installed copies check `releases/latest/download/stable.json`; its Ed25519 signature is verified by the application
  before any update is offered.
