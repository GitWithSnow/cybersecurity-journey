# Day 2 — Cybersecurity Foundations

## Asset

An asset is anything valuable that an individual or organisation wants
to protect.

Examples:

- Devices
- Accounts
- Data
- Applications
- Networks
- Reputation

## Threat

A threat is something capable of causing harm to an asset.

Threats can be:

- Intentional, such as an attacker
- Accidental, such as deleting a file
- Technical, such as hardware failure
- Environmental, such as fire or flooding

## Vulnerability

A vulnerability is a weakness that could be exploited by a threat.

Examples:

- Weak passwords
- Unpatched software
- Incorrect permissions
- Missing encryption
- Poor security awareness

## Risk

Risk is the possibility that a threat will exploit a vulnerability and
cause harm to an asset.

A basic way to think about risk is:

Risk = Likelihood × Impact

## Security Control

A security control is a safeguard used to reduce the likelihood or
impact of a security risk.

Examples:

- Multi-factor authentication
- Encryption
- Backups
- Firewalls
- Antivirus
- Access controls
- Security awareness training

## CIA Triad

### Confidentiality

Information should only be accessible to authorised people.

Example failure: Someone reads private information without permission.

### Integrity

Information should remain accurate and should not be changed without
authorisation.

Example failure: Someone modifies marks in a college database.

### Availability

Systems and information should be accessible when authorised users need them.

Example failure: A website becomes unavailable during an important deadline.

## Additional Security Principles

### Attack Surface

The attack surface consists of all possible points through which a system
could be attacked.

### Least Privilege

A user or application should receive only the minimum access required to
perform its task.

### Defence in Depth

Multiple security controls should protect an asset so that security does
not depend on a single control.

## Security Event vs Security Incident

A security event is an observable action, such as a login attempt or
firewall connection.

A security incident is an event or group of events that threatens the
confidentiality, integrity, or availability of an asset.

Every incident contains events, but not every event is an incident.

## Windows Security Observation

| Security Area | Status | Asset Protected | Threat Reduced |
|---|---|---|---|
| Virus & threat protection | Enabled  | Files | Malware |
| Account protection | Enabled | Accounts&Passwords | Account Theft |
| Firewall & network protection | Enabled  | Decices | Unauthorised Access |
| App & browser control | Enabled  | Laptop | Browser Attacks |
| Device security | Enabled  | Device | Hijacking of a device |

## Personal Laptop Risk Assessment

| Asset | Threat | Vulnerability | Possible Impact | Existing Control | Risk |
|---|---|---|---|---|---|
| College email account | Attacker | Weak Password | High | Strong Password Policy | Medium |
| Personal files | Technical,Environmental&Intentional | Hardware failures,Insecure application download,etc | Medium | Virus&Threat Protection | medium |

## Mini Quiz

### 1. What is the difference between a threat and vulnerability?
A threat is somethign which can harm the assest and vulnerability is something which a threat uses to harm an assest

### 2. What are the three parts of the CIA triad?
Confidentiality, Integrity & Availability

### 3. Give one example of an integrity failure.
Unexpected Changes made in Database

### 4. What does least privilege mean?
Giving the access only what is needed to perform the action 

### 5. Is every failed login a security incident? Explain.
No, Security incident is something which disturbs/causes harm to the CIA Triad

### 6. What is the difference between an asset and a control?
Assent is something which an individual or organisation will like to protect and control is a safegaurd which  
reduces the limit and liklihood of an attack 

### 7. Why does defence in depth use multiple controls?
So that if one layer fails the others can minimize the damage or stop the attack completely
