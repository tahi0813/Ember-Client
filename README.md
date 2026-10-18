# EMBER Client

EMBER Client is a free, non-commercial desktop launcher for macOS (Apple Silicon), developed by an individual.
It launches the official Minecraft: Java Edition, starting with version 1.8.9.

**Status:** in development (not released yet)

## How it works
- Players sign in with their own Microsoft account through the official Microsoft sign-in page in the system browser (OAuth 2.0 + PKCE). The launcher never sees the password.
- Game ownership is checked through the official services. There is no offline or cracked mode.
- Game files are downloaded only from official Mojang servers over HTTPS and verified by SHA-1 and size.
- Access tokens are never written to logs.

## Planned features
- Launcher with version and Java management
- Client-side HUD: FPS, CPS, keystrokes, coordinates, zoom
- No cheating features (no auto-aim, no auto-attack)

## Contact
Please open an issue in this repository.

---
NOT AN OFFICIAL MINECRAFT PRODUCT. NOT APPROVED BY OR ASSOCIATED WITH MOJANG OR MICROSOFT.
