# Cybersecurity-CTF-Labs-Collection-Infrastructure-Hardening-PKI-Enterprise-Security
A curated index of hands-on CTF labs covering infrastructure auditing, secure administration, load balancer/reverse proxy security, PKI, certificate lifecycles, and smart card authentication from Learn SecByte.
# Infrastructure Hardening, PKI & Enterprise Identity Security CTF Labs Collection

A structured, searchable index of hands-on cybersecurity labs focusing on Infrastructure Hardening & Auditing, Secure System Administration, Reverse Proxy & Load Balancer Security, Storage Configuration, Enterprise Identity Defense, Internal Public Key Infrastructure (PKI), Certificate Lifecycle Management, and Smart Card Authentication hosted on Learn SecByte.

This collection is designed for systems administrators, infrastructure security engineers, network security teams, PKI architects, SOC analysts, and security auditors seeking practical experience in securing core enterprise IT infrastructure.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Infrastructure Hardening, Auditing & Secure Administration](#infrastructure-hardening-auditing--secure-administration)
  - [Network Perimeter, Proxy & Storage Security](#network-perimeter-proxy--storage-security)
  - [Public Key Infrastructure (PKI) & Certificate Lifecycles](#public-key-infrastructure-pki--certificate-lifecycles)
  - [Enterprise Identity & Smart Card Authentication](#enterprise-identity--smart-card-authentication)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Core infrastructure components—ranging from internal certificate authorities and smart card authentication systems to reverse proxies, load balancers, and administrative jump boxes—form the backbone of enterprise networks. Misconfigurations in PKI trust chains, unhardened administrative access, or exposed reverse proxies can give attackers single-step lateral movement or full domain compromise.

This repository organizes hands-on infrastructure security labs from Learn SecByte into structured learning paths covering system hardening, perimeter validation, and identity defense.

---

## Lab Collection & Index

| Lab Title | Domain Focus | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **Infrastructure Auditing** | Governance / Audit | Asset Inventory to Security Verification | [Access Lab](https://learn.secbyte.org/ctf/infrastructure-auditing-from-asset-inventory-to-security-ver) |
| **Secure Administration** | Access Control | Hardening, Monitoring & Bastion Access | [Access Lab](https://learn.secbyte.org/ctf/secure-administration-hardening-monitoring-access-control) |
| **Infrastructure Hardening** | System Security | System Baselines & Security Controls | [Access Lab](https://learn.secbyte.org/ctf/infrastructure-hardening-fundamentals) |
| **Infrastructure Monitoring** | SecOps / Logging | Log Aggregation to Threat Detection | [Access Lab](https://learn.secbyte.org/ctf/infrastructure-monitoring-from-logs-to-detection) |
| **Reverse Proxy Security** | Perimeter / Network | Routing Logic to Exploitation & Defense | [Access Lab](https://learn.secbyte.org/ctf/reverse-proxy-security-from-routing-to-exploitation-and-defe) |
| **Load Balancer Security** | Perimeter / Network | Trust Boundaries & Misconfigurations | [Access Lab](https://learn.secbyte.org/ctf/load-balancer-security-trust-boundaries-misconfigurations-an) |
| **Storage Security** | Infrastructure | Misconfigurations to System Compromise | [Access Lab](https://learn.secbyte.org/ctf/storage-security-from-misconfiguration-to-compromise) |
| **Server Infrastructure** | System Architecture | Foundations & Hardening Baselines | [Access Lab](https://learn.secbyte.org/ctf/server-infrastructure-fundamentals) |
| **Enterprise Infrastructure Defense** | Enterprise Defense | Identity, Network & Log Telemetry | [Access Lab](https://learn.secbyte.org/ctf/enterprise-infrastructure-identity-network-log-defense) |
| **Certificate Lifecycle** | PKI Security | Issuance, Renewal & Revocation | [Access Lab](https://learn.secbyte.org/ctf/certificate-lifecycle-from-issuance-to-revocation) |
| **Smart Card Authentication** | Identity Security | PIN, PKINIT & Privilege Escalation | [Access Lab](https://learn.secbyte.org/ctf/smart-card-authentication-from-pin-to-privilege) |
| **Internal PKI & Certificates** | PKI Security | Trust Chains, Template Abuse & Paths | [Access Lab](https://learn.secbyte.org/ctf/internal-pki-certificates-trust-and-abuse-paths) |

---

## Categories

### Infrastructure Hardening, Auditing & Secure Administration
Hands-on CTF labs exploring asset discovery, baseline system hardening (CIS Benchmarks), administrative access controls, and logging infrastructure:

* **Infrastructure Auditing:** Building comprehensive asset inventories and verifying security control compliance across networks.
  * Lab Link: https://learn.secbyte.org/ctf/infrastructure-auditing-from-asset-inventory-to-security-ver
* **Infrastructure Hardening Fundamentals:** Applying benchmark hardening profiles to OS, service, and network configurations.
  * Lab Link: https://learn.secbyte.org/ctf/infrastructure-hardening-fundamentals
* **Server Infrastructure Fundamentals:** Configuring secure server operating environments, user privileges, and core service defenses.
  * Lab Link: https://learn.secbyte.org/ctf/server-infrastructure-fundamentals
* **Secure Administration & Monitoring:** Setting up hardened bastion/jump hosts, MFA for admin access, and auditing privileged commands.
  * Lab Link: https://learn.secbyte.org/ctf/secure-administration-hardening-monitoring-access-control
* **Infrastructure Monitoring:** Ingesting system events, syslog feeds, and audit streams into detection pipelines for threat monitoring.
  * Lab Link: https://learn.secbyte.org/ctf/infrastructure-monitoring-from-logs-to-detection

### Network Perimeter, Proxy & Storage Security
Practical security labs focused on reverse proxies (Nginx, HAProxy), load balancer trust boundaries, and network storage hardening (SAN/NAS/S3):

* **Reverse Proxy Security:** Analyzing routing misconfigurations, header spoofing, request smuggling, and hardening reverse proxies.
  * Lab Link: https://learn.secbyte.org/ctf/reverse-proxy-security-from-routing-to-exploitation-and-defe
* **Load Balancer Security:** Auditing load balancer trust boundaries, TLS termination risks, and HTTP header trust assumptions.
  * Lab Link: https://learn.secbyte.org/ctf/load-balancer-security-trust-boundaries-misconfigurations-an
* **Storage Security:** Identifying insecure storage exports (NFS, SMB, iSCSI), unauthenticated cloud buckets, and privilege escalations.
  * Lab Link: https://learn.secbyte.org/ctf/storage-security-from-misconfiguration-to-compromise
* **Enterprise Infrastructure Defense:** Integrating network segmentation, log telemetry, and identity defenses across the enterprise footprint.
  * Lab Link: https://learn.secbyte.org/ctf/enterprise-infrastructure-identity-network-log-defense

### Public Key Infrastructure (PKI) & Certificate Lifecycles
Security engineering labs detailing internal Root/Subordinate CAs, certificate enrollment protocols, certificate revocation lists (CRLs), and template abuse vectors:

* **Internal PKI & Certificates:** Mapping internal PKI trust chains, certificate template permissions, and analyzing AD CS/PKI abuse paths.
  * Lab Link: https://learn.secbyte.org/ctf/internal-pki-certificates-trust-and-abuse-paths
* **Certificate Lifecycle Management:** Managing x509 certificate issuance, automated renewal protocols (ACME, EST), CRLs, and OCSP revocation checking.
  * Lab Link: https://learn.secbyte.org/ctf/certificate-lifecycle-from-issuance-to-revocation

### Enterprise Identity & Smart Card Authentication
Labs exploring hardware token security, smart card authentication mechanisms, PIN enforcement, and Kerberos PKINIT integration:

* **Smart Card Authentication:** Auditing smart card PIN mechanisms, certificate-based smart card logon, PKINIT authentication flows, and privilege escalation vulnerabilities.
  * Lab Link: https://learn.secbyte.org/ctf/smart-card-authentication-from-pin-to-privilege

---

## Learning Path

Follow this structured roadmap to master enterprise infrastructure hardening and PKI security:

1. **System Baselines & Secure Administration**
   - Perform Infrastructure Auditing to establish complete asset visibility.
   - Apply Infrastructure Hardening benchmarks and configure Secure Administration bastions.
2. **Perimeter Devices & Storage Defense**
   - Audit Reverse Proxies and Load Balancers for header trust flaws and request smuggling.
   - Harden network storage (SMB/NFS/S3) against unauthorized access and privilege escalation.
3. **Public Key Infrastructure (PKI) Architecture**
   - Study Internal PKI trust models and analyze certificate template misconfigurations.
   - Implement Certificate Lifecycle management to automate issuance and handle revocation.
4. **Hardware Identity & Enterprise Monitoring**
   - Secure Smart Card Authentication and PKINIT logon mechanisms.
   - Centralize system and network telemetry via Infrastructure Monitoring pipelines.

---

## How to Use the Labs

1. Select a practice scenario from the index table or category breakdown above.
2. Launch the target lab environment directly on Learn SecByte using the provided access link.
3. Complete hands-on tasks using infrastructure administration tools (OpenSSL, Certutil, proxy testing tools, Wireshark, system auditing scripts, and SIEM consoles).
4. Review post-lab configuration templates, PKI hardening guides, and defensive architectural patterns to secure enterprise networks.

---

## Disclaimer

This repository is strictly intended for educational research, authorized infrastructure auditing, and defensive engineering training. All concepts, tools, and lab environments are provided to help cybersecurity professionals build practical expertise and defend enterprise infrastructure. Unsanctioned testing or attacks against external systems without explicit written permission are strictly illegal.
