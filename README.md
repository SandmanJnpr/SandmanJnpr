# Eric Sandoval

Network Security Architect, HPE

### LLM agent skill: build the Mist side of an SRX drop ship

- **Asks for every value** the build needs: Mist cloud, API token file, org, site, both serials, per-node values, hub details
- **Checks your org first** with read-only API calls, before any write
- **Builds through the Mist API**: the org objects and both Hub Profiles, one yes per write, each one read back, then assigns each profile to its node
- **Watches the zero-touch (SZTP) onboarding** and verifies the result with you
- **Get it:** [skills/srx400-zero-touch-mist](https://github.com/SandmanJnpr/srx-mnha-zero-touch-mist/tree/main/skills/srx400-zero-touch-mist), one-page [overview](https://github.com/SandmanJnpr/srx-mnha-zero-touch-mist/blob/main/docs/Agent-Skill-Overview.pdf)

### Repositories

- **[srx-mnha-zero-touch-mist](https://github.com/SandmanJnpr/srx-mnha-zero-touch-mist)**: zero-touch (SZTP) onboarding of an SRX MNHA pair into Juniper Mist. Paper, Mist Hub Profiles, node configs, the agent skill, and a one-page [QR code vs SZTP](https://github.com/SandmanJnpr/srx-mnha-zero-touch-mist/blob/main/docs/QR-vs-SZTP.pdf) comparison.
- **[srx400-mnha-mist-branch](https://github.com/SandmanJnpr/srx400-mnha-mist-branch)**: SRX400 MNHA secure branch under Juniper Mist. Design paper, import-tested Mist Hub Profiles and reference Junos configs.

> Reference designs by the author, not an official Juniper Networks or HPE position.
