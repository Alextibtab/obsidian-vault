---
thm_path: Red Team Fundamentals
platform: THM
---
# Red Team Fundamentals

## Vulnerability Assessments
The simplest form of security assessment, and it's main objective is to identify as many vulnerabilities in as many systems in the network as possible. To this end, concessions may be made to meet this goal effectively. For example the attacker's machine may be allowlisted on the available security solutions to avoid interfering with the vulnerability discovery process. This makes sense because the objective is to look at every host on the network and evaluate it's security posture.

A vulnerability assessment focuses on scanning hosts for vulnerabilities so that security deficiencies can be identified and effective security measures can be deployed to protect the network. Most of the work is done with automated tools and performed by operators without requiring much technical knowledge.

## Penetration Tests
On top of scanning every single host for vulnerabilities, we often need to understand how they impact the network as a whole. Penetration tests add to vulnerability assessments by allowing pentesters to explore the impact of an attacker on the overall network.
- Attempt to exploit the vulnerabilities found on each system. This is important as sometimes a vulnerability might exist in a system but controls in place effectively prevent the exploitation
- Conduct post exploitation tasks on any compromised hosts allowing
tags: #THM #Red_Team_Path