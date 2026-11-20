# Nebula VPN

A Windows desktop VPN client prototype. The current build is a frontend demo; it does not establish a VPN tunnel or route/encrypt network traffic.

## Prototype setup

1. Install Node.js LTS.
2. Download and extract `NebulaVPN.zip` from this repository.
3. Open a terminal in the extracted project directory.
4. Run `npm install` then `npm run dev`.

## Roadmap
- [x] Dashboard UI, server selection, settings and demo state
- [ ] Tauri Windows packaging
- [ ] Own VPN server deployment
- [ ] WireGuard integration
- [ ] Actual connection status and traffic metrics

Do not commit private keys, credentials, or environment secrets.
