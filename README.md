# Digital Sovereignty Denmark — Organisation Structure

**🇩🇰 Open collaboration for Denmark’s digital sovereignty.**

This repository defines the organisational structure, governance model, and
configuration of the **Digital Sovereignty Denmark** GitHub organisation.

It acts as the **single source of truth** for teams, repositories, and
permissions, and provides the foundation for transparent community governance.

---

## 🧭 Purpose

The purpose of this repository is to:

- Document how the organisation is structured  
- Define all GitHub teams and their responsibilities  
- Specify repository naming conventions and ownership  
- Declare permission models and branch protection rules  
- Support open, auditable governance processes  
- Enable future automation (GitHub Actions, GH CLI, Terraform, etc.)

This ensures that the organisation remains **transparent**, **consistent**, and
**easy to contribute to** as it grows.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| **`teams.yaml`** | Definitions of all GitHub teams, their roles, visibility, and responsibilities. |
| **`repositories.yaml`** | Planned and existing repositories, naming conventions, and team ownership. *(To be added)* |
| **`permissions.yaml`** | Default organisation-wide permissions and per‑repository overrides. |
| **`.github/CODEOWNERS`** | Declares which team must review and approve changes to this repository. |

Future files (e.g., templates, governance documents, automation scripts) may be added as the organisation evolves.

---

## 🧩 How This Repository Works

This repository does **not** automatically configure GitHub — at least not yet.

Instead, it defines a **declared state** of how the organisation *should be*
structured. This allows:

- maintainers to review and approve structural changes
- accountability in decisions
- clear onboarding for new contributors
- the possibility of “organisation-as-code” automation later

The YAML files here **can be enforced** by future automation if desired (for
example via GitHub Actions or Terraform).

---

## 🏛 Governance Model

The **Organisation & Meta** team is responsible for:

- reviewing all changes to this repository  
- maintaining consistency across YAML files  
- approving structural updates to teams and permissions  
- managing long‑term governance direction  

Because of this, CODEOWNERS enforces that all pull requests here go through that team.

---

## 🔧 Editing the Structure

### 1. Propose a change  
Open a Pull Request modifying one of the YAML files.

### 2. Automatic review assignment  
CODEOWNERS will automatically request review from the **Organisation & Meta** team.

### 3. Discussion & approval  
Changes should be discussed openly via PR comments or organisation Discussions.

### 4. Merge  
Once approved and validated, the change is merged to main and becomes the new
declared structure.

---

## 🚀 Future Automation (Optional)

This repository is designed to support (later, if desired):

- GitHub Actions that validate YAML structure  
- Scripts that sync permissions to the GitHub organisation  
- Terraform-based “organisation as code”  
- CI that checks consistency across repos  

For now, the repository serves as the **governance blueprint**.

---

## 🤝 Contributing

Anyone is welcome to propose improvements to the organisational structure.

Please:

1. Open a Pull Request  
2. Describe the motivation clearly  
3. Keep changes focused and minimal  
4. Follow existing naming and structural conventions  

Discussions about process or strategy can also be raised under the
**Discussions & Ideas** team or in organisation-wide Discussions.

---

## 🛡 Licence

This repository contains only configuration and documentation.  
If a licence becomes needed, the Organisation & Meta team will define one.

---

## 🌐 About Digital Sovereignty Denmark

Digital Sovereignty Denmark is a community-driven initiative working to explore,
map, and strengthen digital sovereignty in Denmark through open knowledge,
open tools, and open collaboration.
