# entra-id-lab-notes
Practical and theoretical notes for the SC-300 Microsoft Identity and Access Administrator certification

# SC-300 Lab Notes

Hands-on notes from working through the SC-300 (Microsoft Identity and Access Administrator) certification labs.

This repo documents my lab setup, configurations, and lessons learned while preparing for the SC-300 exam. The goal is to reinforce my own understanding and hopefully help others doing the same.

## Lab Environment

- **Tenant:** Microsoft Entra ID with P2 licensing
- **Custom Domain:** <your-custom-domain>
- **On-Prem Simulation:** Windows Server 2025 ARM VM (Parallels on M1 Mac)
- **Hybrid Identity:** Entra Connect Sync

## Contents

| Section | Description |
|---------|-------------|
| [01 - Initial Setup](./01-initial-setup.md) | Tenant creation, licensing, VM setup |
| [02 - Users and Groups](./02-users-and-groups.md) | Dynamic groups, custom security attributes |
| [03 - Custom Domains](./03-custom-domains.md) | Adding and verifying a custom domain |
| [04 - Company Branding](./04-company-branding.md) | Customizing the sign-in experience |
| [05 - Conditional Access](./05-conditional-access.md) | MFA policies, risk-based access |
| [06 - Hybrid Identity](./06-hybrid-identity.md) | AD DS setup, Entra Connect configuration |

## Prerequisites

To follow along, you'll need:

- An Entra ID tenant (free tier works for some labs, P2 required for others)
- A registered domain name with DNS access
- A Windows Server environment (VM or cloud) for hybrid identity labs

## Notes

These are learning notes, not official documentation. I've done my best to keep things accurate, but always refer to Microsoft's docs for production scenarios.

## About Me

I'm an MDR analyst working toward my SC-300 certification. You can find me on [LinkedIn](your-link) or [GitHub](your-link).
