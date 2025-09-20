Vulnerability Scan Report with OpenVAS
1. Objective

The goal of this project is to perform a vulnerability scan on a system using OpenVAS and analyze the results.

2. Environment

Scanner used: OpenVAS (Greenbone Vulnerability Management)

Systems scanned: 3 operating systems, including Windows 11

3. Scan Results

OpenVAS detected three operating systems, one of which is Windows.

Previously, the Windows OS was vulnerable to SMBv2 (srv2.sys):

A specially crafted packet could lead to remote code execution (RCE) or a system crash.

This vulnerability was classified as critical.

4. Remediation

The vulnerability was mitigated by updating the system and installing the patch.

In the current Windows 11 installation, the vulnerability is no longer present.

5. Additional Observations

To fully check all CVEs, it was necessary to temporarily disable Windows Defender Firewall.

With the firewall enabled, the scanner cannot detect the OS or previously relevant CVEs.

Closing ports helps protect against remote attacks, even on unpatched systems.
