# Changelog

All notable changes to this project will be documented in this file.

## v0.1.0 - 2026-04-19

Initial open source release.

### Added

- Go implementation of Ruijie 802.1X / EAP-MD5 campus network authentication
- EAPOL start, identity response, and MD5 challenge response flow
- Keepalive and retry behavior after authentication
- Explicit `EAPOL-Logoff` logout command via `-logout` / `-logoff`
- Layered configuration support through CLI flags, environment variables, and JSON config files
- Example config, README, `.gitignore`, and MIT license for open source publishing

### Verified

- Self-tested in Sun Yat-sen University campus network environment

### Notes

- This project is intended to be adapted through configuration instead of school-specific hardcoding
- Compatibility may vary across campuses with custom identity suffixes or vendor-specific behavior
