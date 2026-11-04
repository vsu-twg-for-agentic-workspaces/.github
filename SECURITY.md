# 🛡️ Security and Data Privacy Policy

## 1. Compliance with Philippine Republic Act No. 10173 (Data Privacy Act of 2012)

The **VSU Technical Working Group for Agentic Workspaces** maintains a strict policy regarding the protection of personal and institutional data:

1. **Zero Real Data in AI Prompts:**
   - Under no circumstances should real, identifiable student data, employee personnel files, payroll registers, grades, disciplinary records, or non-public administrative communications be fed into cloud-based LLMs or agent prompts.
   - Use only synthesized mock datasets or anonymized tokens.
2. **Sanitization of Code & Workflows:**
   - All repository contributions must be free of exposed API keys, private tokens, passwords, or personal credentials.
   - Use environment variables (`.env`) and `.gitignore` to prevent credential leakage.

## 2. Reporting a Vulnerability

If you discover a security concern or accidental exposure of sensitive information in any repository belonging to this organization:
1. Please **do not** open a public GitHub issue.
2. Contact the Lead Facilitator immediately at: `jomarijoseph.barrera@vsu.edu.ph`.
3. The security incident will be reviewed and mitigated within 24 hours.
