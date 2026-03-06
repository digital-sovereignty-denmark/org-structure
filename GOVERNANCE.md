# Governance Model — Digital Sovereignty Denmark

This document describes how decisions are made within the **Digital Sovereignty Denmark**
GitHub organisation. It provides a transparent, fair, and predictable structure for
contributions, team responsibilities, and organisational evolution.

This governance model is intentionally lightweight and designed to grow alongside the
community.

---

## 🧭 Purpose of This Document

The purpose of this governance document is to:

- Define who is responsible for organisational decisions  
- Explain how contributors can propose changes  
- Clarify how teams operate and collaborate  
- Maintain transparency and predictability  
- Ensure long-term continuity as new contributors join  

This document applies primarily to the **GitHub organisation** and specifically to
repositories, teams, policies, and structural decisions.

---

## 👥 Roles and Responsibilities

### **1. Contributors**

Anyone who engages with the organisation by:
- Proposing issues or discussions  
- Submitting pull requests  
- Suggesting structural or policy improvements  
- Contributing analysis, documentation, or technical work  

All contributors are welcome and encouraged to participate.

---

### **2. Team Members**

Each team within the organisation (as defined in `teams.yaml`) has a specific
domain of responsibility, such as:

- Knowledge & Analysis  
- Tools & Technical Work  
- Discussions & Ideas  
- Resource Collections  
- Organisation & Meta  

Team members may review contributions, lead discussion areas, and help maintain
repositories associated with their team.

Team membership is assigned by maintainers of each team.

---

### **3. Team Maintainers**

Each team may designate *Team Maintainers* who:

- Coordinate work within their team  
- Approve pull requests related to their domain  
- Manage team membership (add/remove members)  
- Serve as the main point(s) of contact for that team  

Team Maintainers are expected to model constructive collaboration and uphold this governance model.

---

### **4. Organisation & Meta Team (Core Governance Team)**

The **Organisation & Meta** team has special responsibilities:

- Maintain the `org-structure` repository  
- Approve changes to organisational structure (teams, YAML definitions, permissions)  
- Manage CODEOWNERS  
- Oversee cross-team coordination  
- Ensure this governance model is followed  

All structural, permission, and policy changes **must** be approved by this team.

---

## 📝 How Decisions Are Made

Decision-making follows a simple, predictable workflow:

### **1. Proposal**
Changes to:
- teams  
- permissions  
- governance  
- repository definitions  
- organisational structure  

…must be proposed through a **Pull Request** to the `org-structure` repository.

### **2. Discussion**
Contributors discuss the proposal via PR comments, Issues, or GitHub Discussions.

Discussion should be:
- respectful  
- transparent  
- evidence-based  
- outcome-focused  

### **3. Review**
GitHub automatically requests review from the **Organisation & Meta** team via CODEOWNERS.

Other teams may comment or provide input as needed.

### **4. Approval**
A pull request is approved when:
- At least **one member** of the Organisation & Meta team approves the change  
- There are no unresolved objections  
- YAML validates (if validation is enabled in CI)  

The Organisation & Meta team uses **lazy consensus**:

> If no objections are raised within a reasonable time, and required approvals are present, the change is considered accepted.

### **5. Merge**
After approval and validation, the PR is merged into `main` and becomes the new declared state.

---

## ⚠️ Dispute Resolution

Most disagreements should be resolved through discussion.  
If no consensus emerges:

1. Team Maintainers discuss the issue together.  
2. If still unresolved, the Organisation & Meta team acts as the final decision-maker.  
3. Decisions are documented in the relevant PR or Discussion.  

This ensures clarity and avoids decision paralysis.

---

## 🧱 Adding, Modifying, or Removing Teams

Changes to teams must be proposed by editing `teams.yaml` and submitted via a pull request.

The Organisation & Meta team must approve changes involving:

- new teams  
- team removals  
- team renaming  
- major changes to responsibilities  
- changes in team visibility  

Teams should have:
- a clear mission  
- defined responsibilities  
- supportive alignment with the group’s purpose  

---

## 🔐 Permissions & Repository Ownership

Permissions and repository ownership are declared in `permissions.yaml`.

The Organisation & Meta team:

- manages default permissions  
- defines branch protection policies  
- ensures CODEOWNERS remains correct  
- approves permission upgrades or new repository creation  

Team Maintainers may propose changes but cannot enforce them without approval.

---

## 🧰 Creating New Repositories

To create a new repository:

1. Propose a new entry in `repositories.yaml`  
2. Assign the primary owning team  
3. Propose an initial permission model (in `permissions.yaml`)  
4. Open a PR for review  
5. After approval, the repository is created manually or by automation  

This ensures consistency and avoids ungoverned sprawl.

---

## 🔄 Changing This Governance Document

This document may be changed via pull request and must be approved by the Organisation & Meta team.

Changes should aim to:
- increase clarity  
- maintain consistency  
- improve processes  
- address the needs of contributors  

Major governance changes may be discussed with the broader community first.

---

## ❤️ Community Values

Digital Sovereignty Denmark operates by principles of:

- openness  
- transparency  
- accessibility  
- respect  
- long-term stewardship  

All participants are expected to uphold these values.

---

## 🧭 Summary

- Anyone can contribute to discussions or propose improvements  
- All structural decisions go through PRs to `org-structure`  
- The Organisation & Meta team is the final decision-maker  
- Teams maintain their own domains but follow shared guidelines  
- Governance evolves with the community  

Thank you for contributing to a transparent and collaborative digital-sovereignty initiative.
