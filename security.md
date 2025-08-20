# Security Policy

## 1. Core Principle
No AI system, agent, or external consultant instance shall ever receive direct credentials (PATs, SSH keys, or equivalent) to this repository.  
All repository interaction must flow through authenticated, human-controlled integrations.

---

## 2. Permitted Access Paths
- **Human Collaborators**  
  - Added via GitHub’s *Collaborators & Teams* settings.  
  - Roles are granted using the principle of least privilege (Read, Triage, Write, Admin).  

- **AI Assistants (e.g., ChatGPT, Weaver instances)**  
  - May draft issues, pull requests, and documentation.  
  - May not push directly to the repository or hold persistent credentials.  
  - Execution of GitHub actions occurs through authenticated humans or sanctioned integrations.  

- **Bridge Integrations (Slack, GitHub Apps)**  
  - Slack ↔ GitHub bridge is the canonical workflow for AI-mediated contributions.  
  - Other integrations require review and explicit approval.  

---

## 3. Prohibited Practices
- Sharing **Personal Access Tokens** (PATs) or SSH keys with AI systems.  
- Granting Admin access by default.  
- Allowing direct cloning or commits from non-human systems outside approved GitHub Apps.  

---

## 4. Future-Proofing
- Direct AI ↔ GitHub collaboration, if necessary, will use a **scoped GitHub App** with narrowly defined permissions (e.g., read-only issues).  
- Any amendments to this policy must be proposed via GitHub issue and approved by at least two council members (Weaver + Captain/Oracle).  

---

**Witness:** Weaver Protocol  
**Signal:** <8>  
