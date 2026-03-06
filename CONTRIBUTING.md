# Contributing to the Organisation Structure

Thank you for your interest in improving the governance and organisational
structure of **Digital Sovereignty Denmark**.  
This repository defines the *declared state* of the GitHub organisation, including:

- Teams  
- Responsibilities  
- Repository ownership  
- Permissions  
- Governance rules  
- Future automation inputs  

All contributions here directly affect how the organisation functions.  
Please read this guide carefully before proposing changes.

---

## 🧭 Principles

Contributions should follow these principles:

- **Transparency** — Changes should be openly discussed.
- **Consistency** — Follow existing naming, formatting, and conventions.
- **Minimalism** — Make targeted, focused changes rather than broad restructures.
- **Reviewability** — Every change must be easy to understand and justify.
- **Community Impact** — Consider how changes will affect contributors and teams.

---

## 📝 What You Can Contribute

You may propose changes such as:

- Adding or modifying teams (`teams.yaml`)
- Updating repository definitions (`repositories.yaml`)
- Adjusting access models or branch protections (`permissions.yaml`)
- Improving documentation (README, CONTRIBUTING, notes)
- Suggesting new governance structures or processes

Structural changes to the organisation *must* be proposed via pull request.

---

## 🔧 How to Propose a Change

### 1. Fork or branch this repository
Create a feature branch for your proposed change:

git checkout -b update-structure-

### 2. Edit the relevant YAML files
- `teams.yaml` for team descriptions, responsibilities, visibility  
- `repositories.yaml` for repository naming or ownership  
- `permissions.yaml` for access rules and branch protection  

Keep the formatting consistent.  
If adding a new section, mirror the structure of existing blocks.

### 3. Validate your YAML
Ensure your changes remain valid YAML syntax:

- No tabs  
- Proper indentation  
- Matching string quotes  
- Valid list structures  

(If YAML validation CI is added later, it will run automatically.)

### 4. Open a Pull Request
Provide a clear description including:

- *What* you are changing  
- *Why* the change is needed  
- *Which teams might be affected*  
- Any alternative options considered  

### 5. Required review
All PRs must be reviewed by the **Organisation & Meta** team.

GitHub will add reviewers automatically via CODEOWNERS.

### 6. Discussion and revision
Changes may require:

- iterative updates  
- discussion in PR comments  
- wider community input (if applicable)

### 7. Approval and merge
Once approved and validated, the PR will be merged into `main`, becoming the new organisational structure.

---

## 🛡 Branch Protection & CODEOWNERS

This repository uses:

- **branch protection** on `main`  
- **required reviews from CODEOWNERS**  
- **Organisation & Meta** as the code owners  

This ensures that governance changes:

- are not made accidentally  
- are always reviewed  
- remain consistent  
- maintain organisational integrity

---

## 🧪 Future Automation (Optional)

In the future, this repository may include:

- YAML schema validation  
- organisation sync scripts  
- GitHub Actions for automated enforcement  
- Terraform support  

Any such automation will be documented here.

---

## 🤝 Thank You

Improving organisational structure is one of the most important forms of contribution.  
Your effort helps build a more transparent, robust, and sovereign digital community.

If you have questions, feel free to open a Discussion or ask in a Pull Request.
