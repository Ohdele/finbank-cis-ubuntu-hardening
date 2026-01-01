# FinBank CIS Ubuntu Hardening Lab

## Description
CIS benchmark based secure configuration and hardening lab on Ubuntu using Kali for audit validation and proof logging.

## Objectives
- Implement CIS Ubuntu Server 24.04 benchmarks
- Harden system and services
- Validate configuration changes

## SSH Hardening

- Root login disabled
- Host keys regenerated
- Password authentication enabled
- Public key authentication enabled
- Log level set to INFO

Verification performed using sshd -T and localhost SSH login.

## Firewall Hardening
UFW configured with default deny incoming, allow outgoing.
Proof saved in [ufw-proof.txt].

## Implemented  Steps
- System updated and patched
- SSH hardening applied and verified
- UFW firewall configured and verified
- Unnecessary services disabled and documented
- CIS password policies configured and documented
