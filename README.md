# Haven Client Releases

This repository is the public update channel for Haven Client.

- Source code is maintained in a separate private repository.
- Windows installers are published under **Releases**.
- `latest.json` is consumed by the Haven Launcher update service.
- Every downloaded installer is verified by SHA-256 and file size before it
  can be opened.

Do not manually edit `latest.json`. Publish releases with the release tooling
in the private Haven Client source repository.
