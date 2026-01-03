# External Network Penetration Testing — Academic Case Study

## Disclaimer
This case study documents penetration-testing activities conducted in a controlled academic lab environment using intentionally vulnerable systems. No production systems, real organizations, or live networks were tested.

## Overview

This case study examines an external network penetration test performed against a simulated enterprise environment in a controlled academic lab. The objective was to determine whether an external attacker could identify exposed services and leverage weak security controls to gain access to internal systems.

The assessment followed a structured penetration-testing methodology that included reconnaissance, enumeration, exploitation validation, and reporting. The environment intentionally contained insecure configurations to demonstrate common real-world risks associated with legacy services, weak credential management, and improper perimeter exposure.

Testing identified multiple high-risk security weaknesses that, when combined, allowed an attacker to progress from the public-facing perimeter to internal system access. This case study focuses on methodology, risk analysis, and professional reporting practices rather than exploit instruction.

## Scope & Assumptions

### Scope
- External-facing network services
- Publicly accessible attack surface
- Validation of access paths into internal systems

### Out of Scope
- Denial-of-service attacks
- Phishing or social engineering
- Password spraying or brute-force attacks

### Assumptions
- All systems were authorized for testing
- The environment was intentionally vulnerable for educational purposes
- Findings reflect common real-world misconfigurations

