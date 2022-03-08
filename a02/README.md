# A02 - Cryptographic Failures

## Introduction and background

In previously OWASP lists, this vulnerability was named
_Sensitive Data Exposure_. OWASP changed the name due to this is more a broad
symptom rather than a root cause. The focus should be on failures related to
cryptography (or lack thereof), which again could lead to exposure of
sensitive data.

### CWEs

Notable Common Weakness Enumerations:

- [CWE-259:](https://cwe.mitre.org/data/definitions/259.html)
Use of Hard-coded Password
- [CWE-327:](https://cwe.mitre.org/data/definitions/327.html)
Broken or Risky Crypto Algorithm
- [CWE-331:](https://cwe.mitre.org/data/definitions/331.html)
Insufficient Entropy

Notable Common Weakness Enumerations (CWEs):

## CVEs

>Note to self: Elaborate on some ... examples?

## Examples of attacker scenarios using juice shop


## Primary defenses

- [OWASP's transport layer protection cheat sheet](https://cheatsheetseries.owasp.org/cheatsheets/Transport_Layer_Protection_Cheat_Sheet.html)
- [OWASP's user privacy protection cheat sheet](https://cheatsheetseries.owasp.org/cheatsheets/User_Privacy_Protection_Cheat_Sheet.html)
- [OWASP's password and cryptographic storage cheat sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html)
