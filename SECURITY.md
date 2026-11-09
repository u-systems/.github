# Security Policy

## Our Philosophy

At **µSystems**, security is built into the architecture from first principles — strictly enforced in pure Assembly, C11, and Ring 0 kernel space. However, no software is immune to vulnerabilities or unforeseen side effects.

We take all security disclosures extremely seriously. As a core rule of our **Open Source, Closed Contribution** model, external code contributions are not accepted, but **reproducible security research and vulnerability reports are highly encouraged and rewarded with public attribution.**

---

## Supported Versions

Only the latest commit on the `main` branch of each respective repository is actively maintained and supported for security updates.

---

## Reporting a Vulnerability

**Do NOT report security vulnerabilities through public GitHub Issues or Pull Requests.**

To responsibly disclose a security vulnerability:

1. Go to the **Security** tab of the affected repository.
2. Click **Report a vulnerability** to open a private advisory draft.
3. Provide a detailed report including:
   * **Description:** A clear explanation of the issue and its potential impact.
   * **Proof of Concept:** Minimal code, inputs, or steps to consistently reproduce the bug/crash.
   * **Affected Component:** Specific syscalls, kernel hooks, memory structures, or modules involved.

If Private Vulnerability Reporting is unavailable for any reason, contact us directly via GPG-encrypted email:

* **Email:** `tralsesec@gmail.com`
* **PGP Key ID:** `0x6356373DAFD25E17` (published on `keys.openpgp.org`)

---

## What to Expect

* **Initial Response:** You will receive an acknowledgment of your report within **24-72 hours**.
* **Triage & Verification:** We will independently analyze and reproduce the issue.
* **Fix & Release:** Valid vulnerabilities will be patched in-house on an expedited timeline.
* **Credits & CVE Attribution:** Verified reports will be awarded:
  * Public attribution and shoutouts in the release notes and commit logs.
  * Formal co-authoring of a **GitHub Security Advisory**.
  * Issuance of an official **CVE ID** via GitHub Advisory for high-impact disclosures.
