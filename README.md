# Cybersecurity Projects

A collection of my personal cybersecurity projects: home labs, tooling, write-ups, and experiments I build to sharpen my skills and explore areas of security I'm passionate about.

## About Me

I'm a cybersecurity professional based in Southern California with hands-on experience in identity and access management, compliance (PCI DSS, GRC), SIEM engineering, vulnerability management, and endpoint security. I hold **CISSP**, **CompTIA Security+**, and a few cloud certifications, and I have a B.S. in Information Security and Forensics from Cal Poly Pomona.

I'm especially interested in **Identity & Access Management (IAM)** and **cloud security**, with **vulnerability management** and **threat intelligence** as secondary focus areas.

## What This Repository Is

This repo is the home for everything I build on my own time. Each project lives in its own folder with its own README that covers the goal, architecture, setup steps, and lessons learned.

> **Note:** All projects here are personal and built in lab or sandbox environments. Nothing in this repository contains employer data, credentials, or sensitive information.

## Focus Areas

| Area | What You'll Find |
|------|------------------|
| **Identity & Access Management** | Hybrid Entra ID / Active Directory labs, Conditional Access policies, identity governance |
| **Cloud Security** | Azure security configurations, hardening, and monitoring |

## Projects

| Project | Description | Tech | Status |
|---------|-------------|------|--------|
| [IAM Home Lab](./iam-home-lab) | Hybrid Entra ID and on-prem Active Directory lab behind a pfSense firewall for hands-on identity practice | Entra ID, Active Directory, pfSense, virtualization | 🚧 In progress |
| _More coming soon_ | | | |

## Repository Structure

```
.
├── README.md
├── iam-home-lab/
│   ├── README.md
│   ├── docs/
│   └── scripts/
├── project-name/
│   ├── README.md
│   └── ...
└── resources/        # Cheat sheets, notes, references
```

## Project README Template

Each project follows a consistent format:

1. **Overview**: what it is and why I built it
2. **Architecture**: diagram and components
3. **Setup**: step-by-step build instructions
4. **Usage**: how to run or use it
5. **Lessons Learned**: challenges, mistakes, and takeaways
