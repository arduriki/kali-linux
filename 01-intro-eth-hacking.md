# Index

## Terminology

- **Asset** - Anything that has a value to an organization or person: systems that can be interacted with, people, physical security controls and data.
  - *Tangible* - Physical objects like network devices. If they're compromised, cyber criminals will be able to redirect network traffic to malicious websites that are owned by malicious actors and expand their operations.
  - *Intangible* - Apps, software license keys, intellectual property, business plans and models, and data.
  - *People* - Customers and employees of an organization.

**Threat** - Anything that has the potential to cause harm or damage to a system, network, or person. Industry professionals need to stay one step ahead of threat actors to quickly find security weaknesses in systems, networks, and apps and implement countermeasures.

---

**Vulnerability** - A security weakness or flaw that exists within a system that enables hackers to exploit it in order to gain unauthorized access or control over systems within a network.

---

**Exploit** - A tool or code that is used to take advantage of security vulnerabilities on a system. The threat actor or pentester will either acquire an exploit from various online sources or develop one on their own that has the capability of taking advantage of the security weakness.

---

**Attack** - A method or technique that is used by a threat actor to take advantage of (exploit) a security vulnerability (weakness) within a system.

>[!NOTE]
> An example of ransomware is [LockBit 3.0](https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-075a).

**Attack vector** - An area or pathway through which a targeted system, network or organization can be compromised by a threat actor.
- *Direct access* - Physical access to the target.
- *Wireless* - Vulnerabilities in the wireless network infraestructure.
- *Email* - Physhing
- *Supply chain* - Compromising the security of a vendor or a supplier to gain access to a target.
- *Social media* - Using deceptive messages or "malvertising" to trick the target into revealing sensitive information or downloading a malicious file.
- *Removable media* - Connecting malware-infected media to the targeted system.
- *Cloud* - Exploiting security vulnerabilities within cloud services and its infraestructure.

---

**Risk** - The potential impact that a vulnerability, threat, or attack presents to the assets of an organization and the likelihood an attack or threat has to cause harm systems. The cibersecurity pro will present all the vulnerabilities and possible solutions to help the organization mitigate and reduce the risk.

---

**Attack surface** - All the vulnerable points of entry into a system, network, or organization that can be exploited to gain unauthorized access and expans their foothold on the network.

**Zero-day** - It's when a threat actor discovers a security vulnerability within a product or app and is able to exploit it before the vendor is either aware of the vulnerability or has time to develop a security patch to resolve the issue.

---

## Threat actors

**Script kiddie** - He/She follows the instructions or tutorials of real hackers to perform their own attacks against a targeted system or network.

---

**Cyber terrorist** - Performs cyber-attacks that are designed to compromise communication channels and systems. To cause damage and disruption to create fear to a target society.

**Hacktivist** - To use their hacking skills to perform malicious activities suah as defacing websites or launching Denial of Service (DoS) attacks in support of a political or social agenda.

---

**Insider** - To create a fake activity and CV with the intention of applying for a job within their targeted organization and becoming an employee. Once inside, the person will have access to the internal network and gain better insights into the network achitecture and security vulnerabilites of the company. This actor can create backdoors for remote access to critical systems.

---

**State-sponsored or nation-state actor** - A government my hire one of these to be responsible for performing reconnaissance on other countries and protecting their own country from cyber-attacks and emerging threats.

---

**Organized crime** - They can become and Advanced Persist Thread (APT).

---

**Black hat** - A threat actor. Reasons? To destroy their target's reputation, steal data, or even as a personal challenge to prove a point for fun.

**White hat** - Actors that use their skills to help organizations and people secure their networks and safeguard their assets from malicious hackers.

**Gray hat** - Between black and white hat hackers. Helping during the day and not helping at night.

---

### What matters to them

Hacking focuses on gaining a better understanding of how a system operates and functions, whether there are any flaws within its programming or design, and whether these security flaws can be exploited to alter the functionality of the system to enable the curious mind to take advantage of it.

#### Time

Pentesters need to determine how long it will take to complete a penetration test for a customer and present a report with the findings and security recommendations to help the customer improve their security posture.

#### Resources

To have the proper toolkit and to know how to use it.

#### Financial factors

Pentesters are well funded by their employers to ensure they have access to the best tools within the industry to excel at their jobs.

#### Hack value

The motivation or the reason for performing a cyberattack agains a targeted system, network, or organization.

---
---

## The importance of pentesting

Organizations are realizing the need to hire white hat hackers such as ethical hackers and penetration testers with the skills needed to simulate real-world cyber-attacks on their systems and networks to discover and exploit hidden vulnerabilities and better understand the TTPs (Tactics, Techniques, and Procedures) of cyber criminals. Furthermore, penetration testing helps organizations improve their incident response plans, enhances their security posture, and creates a culture of continuous improvement in cybersecurity practices.

---
---

## Pentesting methodologies

More info about pentesting methodologies can be foung in [here](https://owasp.org/www-project-web-security-testing-guide/latest/3-The_OWASP_Testing_Framework/1-Penetration_Testing_Methodologies)

### Pre-engagement phase

Legal requirements that are tipycally include a **Non-Disclosure Agreement (NDA)** and a **Consulting Services Agreement (CSA)**.

Some questions that help to define the scope of a penetration test:

- What is the size/class (IP addresses and/or network blocks) of the external network? (Network penetration testing)
- What is the size/class (IP addresses and/or network blocks) of the internal network? (Network penetration testing)
- What is the purpose and goal of the penetration test? (Applicable to any form of penetration testing)
- How many site pages does the web application have? (Web application penetration testing)

### Information-gathering phase

Understanding the target is very important before launching any type of attack as a penetration tester, as it helps in creating a profile of the potential target and determining which types of attacks are most effective based on the attack surface.

### Threat modeling

To learn about threat modeling and various frameworks, please see [this](https://www.crowdstrike.com/en-us/cybersecurity-101/threat-intelligence/threat-model/).

To put it simply, during the **information-gathering** phase, a penetration tester profiles the target and identifies any vulnerabilities. **Vulnerability assessments** play a critical role in identifying and prioritizing vulnerabilities for remediation. They are a fundamental component of a comprehensive security program, providing a broad overview of an organization’s security posture. Using the information about the vulnerabilities, the penetration tester will do their **research and create specific exploits that will take advantage of the vulnerabilities of the target** – this is exploitation. We use exploits (malicious code) to leverage a vulnerability (weakness) in a system, which will allow us to execute arbitrary code and commands on the targeted system(s).

During **post-exploitation**, the primary goal is typically to demonstrate the impact that the vulnerability and access gained can pose to the targeted organization. This impact assists in helping executive leadership and decision-makers to better understand the risks, vulnerabilities, and damage it could cause to the organization if a threat were to target their company and assets.

**Report writing** is the medium through which you convey risk and business impact, sumarize your findings, and include remediation steps. It includes explaining technical vulnerabilities in a way that is accessible to non-experts and illustrating the potential business impacts of these vulnerabilities.

---

## Pentesting approaches

**White box** - The pentester is provided with full information about the targeted apps, systems, and networks, and is usuarlly given user credentials with varying degrees of access to quickly and thoroughly identify the attack surface of the target.

**Black box** - The pentester is given very little or no information about the targeted organization, its networks, or its systems except the organization's name.

**Gray box** - The pentester receives enough information to reduce the time needed to conduct reconnaisance and other black box testing activities.

---

## Types of penetration testing
