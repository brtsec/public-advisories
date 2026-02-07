# Public Advisories

This repository serves as a central reference for security vulnerabilities I have responsibly disclosed. Each entry documents a vulnerability that has been assigned a CVE identifier, reported to the affected vendor, and published after a reasonable remediation window.

All advisories follow a consistent format and are structured for easy navigation.

## Advisories

| CVE ID | Vendor | Product | Vulnerability | Severity |
|---|---|---|---|---|
| [CVE-2025-69752](advisories/CVE-2025-69752/) | Ideagen | Q-Pulse 7.1.0.32 | IDOR in User Profile Functionality | Medium |

## Repository Structure

```
public-advisories/
├── advisories/
│   └── CVE-YYYY-NNNNN/
│       ├── README.md
│       ├── screenshots/
│       └── src/
├── templates/
│   └── CVE-TEMPLATE.md
└── .github/
    └── SECURITY.md
```

Each CVE has its own folder under `advisories/`. The advisory writeup is always named `README.md` so GitHub renders it automatically when navigating into the folder. Supporting materials such as screenshots or proof-of-concept code are placed in subfolders alongside it when applicable.

## Disclaimer

Content in this repository is shared for educational and research purposes only. All vulnerabilities documented here were discovered through authorized testing or responsible research. Any use against systems without explicit authorization is prohibited.
