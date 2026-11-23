# Modern Classics — Quarterly Security Digest, Special Retrospective

## Apache Log4j "Log4Shell" — CVE-2021-44228 (disclosed December 2021)
- **GitHub advisory (GHSA):** GHSA-jfh8-c2jp-5v3q
- **Severity:** Critical / CVSS 9.8 (NVD base score 10.0)
- **First fixed version:** 2.15.0 (org.apache.logging.log4j:log4j-core); JNDI lookup disabled by default from 2.16.0
- **Advisory link:** https://github.com/advisories/GHSA-jfh8-c2jp-5v3q
- **Logo:** https://commons.wikimedia.org/wiki/File:Apache_Log4j_Logo.png
- **What to tell your team:** Never leave Log4j on 2.14.x default config — jump to 2.17.0+; old configs amplify the RCE.

## OpenSSL Heartbleed — CVE-2014-0160 (disclosed 2014)
- **GitHub advisory (GHSA):** GHSA-w8r8-w5w4-4w4v
- **Severity:** High / CVSS 7.5
- **First fixed version:** OpenSSL 1.0.1g (released 2014-04-08); affected 1.0.1 through 1.0.1f
- **Advisory link:** https://github.com/advisories/GHSA-w8r8-w5w4-4w4v
- **Logo:** https://commons.wikimedia.org/wiki/File:OpenSSL_logo.png
- **What to tell your team:** Regenerate all TLS keys after patching OpenSSL 1.0.1g (2014-04-08); never leave vulnerable versions.

## GNU Bash Shellshock — CVE-2014-6271 (disclosed 2014)
- **GitHub advisory (GHSA):** GHSA-6hfc-grwp-2p9c
- **Severity:** Critical / CVSS 9.8
- **First fixed version:** Bash 4.4 (first patch in 4.3.25, March 2014); the original 4.3 fix was incomplete
- **Advisory link:** https://github.com/advisories/GHSA-6hfc-grwp-2p9c
- **Logo:** https://commons.wikimedia.org/wiki/File:Gnu-bash-logo.svg
- **What to tell your team:** Upgrade Bash to 4.4 — the first fix shipped in March 2014; the Python 2 Bash line is end-of-life.

## xz utils backdoor — CVE-2024-3094 (disclosed 2024)
- **GitHub advisory (GHSA):** GHSA-rxwq-x6h5-x525
- **Severory**: Critical / CVSS 10.0
- **First fixed version:** xz 5.6.5 (malicious code introduced in 5.6.0 upstream tarballs)
- **Advisory link:** https://github.com/advisories/GHSA-rxwq-x6h5-x525
- **Logo:** https://upload.wikimedia.org/wikipedia/commons/6/67/XZ_logo_contributed_by_Jia_Tan.png
- **What to tell your team:** Verify tarball integrity, pin xz 5.6.5+, and treat XZ Utils tarballs as untrusted.
