# Candidate Career Portfolio Website

**Candidate:** Rahul Sharma  
**Target Roles:** Workday Integration Lead | Workday–ADP Payroll Transformation Lead | HR Technology Delivery Lead  
**Governing Skill:** `.agents/skills/career-portfolio-site/SKILL.md`  
**Compliance Standard:** [`AGENTS.md`](file:///Users/rahul/Documents/Job%20Hunt%20Automation/AGENTS.md) (Zero deployment, zero public git repository, zero unverified claims).  
**Status:** Local Preview Stage (Awaiting candidate review and explicit deployment approval).

---

## 1. Local Preview Instructions

You can preview the responsive portfolio site locally using any standard browser:

### Option A: Python Local Web Server (Recommended)
Run this command from your terminal:

```bash
cd "/Users/rahul/Documents/Job Hunt Automation/website"
python3 -m http.server 8080
```
Then open your browser to: **`http://localhost:8080`**

### Option B: Direct File Open
Open the HTML file directly in your browser:
- **macOS Terminal:** `open "/Users/rahul/Documents/Job Hunt Automation/website/index.html"`
- Or double-click `index.html` in macOS Finder.

---

## 2. Content-to-Evidence Traceability Matrix

Every statement, badge, case study, and skill category on this website is mapped directly to verified evidence items in [`career/evidence/evidence-ledger.csv`](file:///Users/rahul/Documents/Job%20Hunt%20Automation/career/evidence/evidence-ledger.csv):

| Website Section / Element | Claim / Content Displayed | Mapped Evidence ID | Verification Notes |
|---|---|:---:|---|
| **Hero Badges & Headline** | Workday HCM & PECI, ADP GlobalView, 10+ Interface Streams | `E-0003`, `E-0009` | Verified exposure and analysis across 10+ interface families. |
| **Specialization 1** | Workday–Payroll Data Flow Analysis (PECI & CCW) | `E-0003`, `E-0009` | Framed truthfully as analysis and governance. |
| **Specialization 2** | Calculated Fields & Business Logic (LRVs, Evaluate Expressions) | `E-0004` | Precedence formulation for branch codes and Z1–Z8 contracts. |
| **Specialization 3** | Cross-System Data Reconciliation (Workday to ADP IT0001/IT0027) | `E-0002` | Structured source-to-target reconciliation controls. |
| **Specialization 4** | Defect Root-Cause Analysis (RCA on AUF01 & BAPI rejections) | `E-0005` | Translation of technical gateway failure modes into mapping fixes. |
| **Specialization 5** | Test Governance & Operational Runbooks (Z1–Z8 matrices) | `E-0006`, `E-0007`, `E-0008` | Test execution and G2 supplemental load runbook authoring. |
| **Specialization 6** | Cross-Functional Leadership (Payroll, HR, IT, and AMS vendors) | `E-0009`, `E-0010` | Stakeholder standups and SLA turnaround management. |
| **Case Study 1** | Multi-Contract Labor Classification & Cost Allocation Architecture | `E-0004`, `E-0005`, `E-0006`, `E-0007` | Sanitized; zero client names or AUF01 values exposed. |
| **Case Study 2** | Cross-System Identity Linkage & Access Remediation | `E-0001`, `E-0002` | Sanitized; employee profile and payslip access recovery. |
| **Architecture Model** | Workday-to-ADP System Context & Sequence Diagram | `E-0002`, `E-0003`, `E-0004` | Clean SVG diagram derived from portfolio artifact. |
| **Skills Depth** | Labeled by Expert (Owned) vs. Advanced (Governed) vs. Working | All `E-0001`..`E-0010` | Zero claims of unverified Studio Java coding or Workday Pro cert. |

---

## 3. Privacy & Sanitization Checklist

- [x] **Client & Employer Names:** 100% sanitized. No specific company or client names appear in public text.
- [x] **Employee & Payroll Data:** Zero real employee IDs, names, compensation numbers, or bank details are present.
- [x] **Internal Technical Codes:** Specific AUF01 order numbers, tenant keys, and internal server paths are generalized.
- [x] **Contact Information:** Direct phone numbers and personal email addresses are omitted to prevent automated scraping.
- [x] **Zero External CDN Dependencies:** Pure CSS and native SVG. Renders 100% offline without external network calls.

---

## 4. Deployment Stop Gate

> [!CAUTION]
> **DO NOT DEPLOY WITHOUT APPROVAL:**
> In accordance with persistent rules in `AGENTS.md`, no GitHub repository, Vercel/Netlify hosting, Cloudflare Pages, or custom domain may be created or configured without explicit candidate authorization for the exact content and provider.
