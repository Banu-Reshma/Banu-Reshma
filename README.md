## Hi, I'm Reshma Banu

**Identity & Access Management / Authentication Support Engineer** — Bangalore, India.

I spend my days on the unglamorous end of security: why a token stopped working, why one
node in a cluster rejects an agent, why SSO loops back to the login page. Six and a half
years in technical support, the last four of them on RSA SecurID Authentication Manager
and Cloud Authentication Service.

### What I actually work on
- **Authentication** — RSA SecurID, Authentication Manager, Cloud Authentication Service, MFA
- **Protocols** — SAML, LDAP, RADIUS, OAuth/OIDC basics, certificates and trust chains
- **Support engineering** — L2/L3 escalation, reproduction, root-cause analysis, customer comms
- **Platforms** — Windows, Linux, VMware/vSphere appliances, SQL, REST APIs, Postman
- **Learning now** — Docker, Python automation, building small tools instead of repeating steps

### Repositories here
Everything in this account is built from **synthetic data**. Nothing from my employer or any
customer environment appears in these repos — the scenarios are reconstructed, the logs are
generated.

| Repo | What it is |
|---|---|
| `iam-support-runbooks` | Troubleshooting runbooks for the failures I see most: token resync, node secret mismatch, LDAP sync failure, SAML redirect loops, certificate expiry |
| `auth-log-triage` | Python CLI that reads authentication/RADIUS logs and summarises *why* logins failed, instead of making you read 10,000 lines |
| `mfa-push-fatigue-lab` | A small demo of push-bombing against plain approve/deny MFA, and how number matching removes the attack |

### Elsewhere
- Portfolio: https://reshmabanu.great-site.net
- LinkedIn: https://www.linkedin.com/in/reshma-banu97

I write about authentication and support work on LinkedIn — mostly short notes on things that
broke and what the fix taught me.
