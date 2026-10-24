# ToneCustoms Prop Generator — Update Metadata

**Public update-information endpoint · Not a source code repository**

This repository hosts a machine-readable `update.json` manifest for the ToneCustoms Prop Generator update process.

## Contents

| File | Purpose |
| --- | --- |
| [`update.json`](update.json) | Version and update metadata for supported update clients |

The manifest may contain `version`, `download_url`, `sha256` and `notes` fields. These fields describe an update record, but **do not independently verify that the download is current, trustworthy, available, or an approved public release**.

## Publishing safeguards

- Update this manifest only after an owner-approved build is verified working.
- Check the approved version, download destination, release notes and SHA-256 checksum before publishing.
- Do not publish repository tokens, private download entitlements, credentials, or internal build information.
- Keep actual private application source and protected customer assets outside this public metadata repository.
- If an update points to a private or restricted distribution method, verify that authorization is enforced by the distribution service.

## Support & official links

- [ToneCustoms documentation](https://github.com/tonyiswavy/tonecustoms-docs)
- [Customer information](https://github.com/tonyiswavy/tonecustoms-docs/tree/main/policies)
- [Discord](https://discord.gg/JdZ7NTG5KF)
- [Tebex](https://tonecustoms.tebex.store/)

*ToneCustoms — Built for roleplay. Made with purpose.*
