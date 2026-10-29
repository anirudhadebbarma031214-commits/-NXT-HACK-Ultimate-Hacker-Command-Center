# NXT-HACK — Ultimate Hacker Command Center

Responsive neon-green cybersecurity learning dashboard built with plain HTML, CSS, and JavaScript.

## Modules
- Overview dashboard with Matrix-style animation and ethical-use notice.
- Fictional hacker terminal: help, whoami, date, system-check, scan-demo, matrix, clear.
- Ethical toolkit: local password-strength estimate, SHA-256 text hash, public IP info, public DNS lookup, URL format checker.
- Security Center checklist for hardening websites you own or administer.
- Beginner Cyber Lab with safe challenges.

## Run / deploy
Open index.html, or run `python -m http.server 8000` and visit `http://localhost:8000`.
GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root).

## Safety and privacy
The terminal is simulated and does not run OS commands or contact targets. Public IP lookup contacts ipapi.co; DNS queries use Google's public DNS-over-HTTPS service. Do not enter real passwords or secrets. The URL checker validates formatting only, not reputation. This static site has no account backend and does not perform port scans or automated vulnerability scans. Only assess systems with explicit permission.

© 2026 NXT-HACK · ANI STUDIO