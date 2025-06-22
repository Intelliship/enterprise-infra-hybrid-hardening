# Hybrid Infrastructure Hardening Baseline

This document outlines the reference architecture simulated in this repository. Each layer is modular, allowing tailored hardening strategies across identity, endpoint, network, and cloud systems.

| Layer     | Control Focus                        | Example Controls                     |
|-----------|--------------------------------------|--------------------------------------|
| Identity  | Entra ID / Okta policy enforcement   | MFA, Conditional Access, SCIM sync   |
| Endpoint  | Addigy MDM, compliance validation    | Device enrollment, posture check     |
| Network   | Fortinet NGFW, segmentation          | East-west traffic isolation          |
| Cloud     | Azure Policy, secure baselines       | Subscription compliance, tagging     |

> This structure provides the scaffolding for future automation using tools like Ansible, Terraform, and Azure Policy-as-Code.
