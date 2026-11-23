# Modern Classics — Quarterly Security Digest, Special Retrospective

## Apache Log4j "Log4Shell" — CVE-2021-44228

- **CVE:** CVE-2021-44228
- **GitHub Advisory Database (GHSA):** GHSA-jfh8-c2jp-5v3q
- **Severity/CVSS:** Critical — CVSS 10.0 (CVSS v3.1, AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H)
- **First fixed version:** 2.16.0
- **Disclosure:** December 2021
- **Authoritative link:** https://github.com/advisories/GHSA-jfh8-c2jp-5v3q
- **Logos:** [Apache Log4j logo](https://upload.wikimedia.org/wikipedia/commons/f/f9/Apache_Log4j_Logo.png)

> What to tell your team: Patch Log4j to 2.16.0+ immediately (or downgrade); scan for 2.14.1 through 2.15.0.

## OpenSSL "Heartbleed" — CVE-2014-0160

- **CVE:** CVE-2014-0160
- **GitHub Advisory Database (GHSA):** GHSA-w8r8-w5w4-4w4v
- **Severity/CVSS:** High — CVSS 7.5 (CVSS v3.1, AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N)
- **First fixed version:** 1.0.1g (April 7, 2014)
- **Disclosure:** 2014
- **Authoritative link:** https://github.com/advisories/GHSA-w8r8-w5w4-4w4v
- **Logos:** [OpenSSL logo](https://upload.wikimedia.org/wikipedia/commons/a/a1/OpenSSL_logo.png)

> What to tell your team: Upgrade OpenSSL to 1.0.1g+; check repos for 1.0.1f and 1.0.2-beta.

## GNU Bash "Shellshock" — CVE-2014-6271

- **CVE:** CVE-2014-6271
- **GitHub Advisory Database (GHSA):** GHSA-6hfc-grwp-2p9c
- **Severity/CVSS:** Critical — CVSS 9.8 (CVSS v3.1, AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H)
- **First fixed version:** 5.0 (Nano Bash / Red Hat)
- **Disclosure:** September 2014
- **Authoritative link:** https://github.com/advisories/GHSA-6hfc-grwp-2p9c
- **Logos:** [GNU Bash logo](https://cdn.simpleicons.org/gnubash/4EAA25)

> What to tell your team: Update to Bash 5.0+; patch affected systems for sub-4.3 versions; watch for the CVE-2014-7169 variant.

## xz utils backdoor — CVE-2024-3094

- **CVE:** CVE-2024-3094
- **GitHub Advisory Database (GHSA):** GHSA-rxwq-x6h5-x525
- **Severity/CVSS:** Critical — CVSS 10.0 (CVSS v3.1, AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H)
- **First fixed version:** 5.7.x (5.7.0 shipped April 2024)
- **Disclosure:** March 2024
- **Authoritative link:** https://github.com/advisories/GHSA-rxwq-x6h5-x525
- **Logos:** [XZ Utils logo](https://upload.wikimedia.org/wikipedia/commons/6/67/XZ_logo_contributed_by_Jia_Tan.png)

> What to tell your team: Binaries/xz 5.6.0+ are affected — upgrade to 5.7.x or revert from affected tarballs; verify SSH/server builds for the SShd backdoor.
