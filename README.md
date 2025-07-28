<img width="1024" height="798" alt="ChatGPT Image Jul 28, 2025, 11_58_17 AM" src="https://github.com/user-attachments/assets/215b6c14-28f9-4433-8f38-7c211f79f88e" />

# 🛡️ Datacom Cybersecurity Internship Portfolio

**Role:** Cybersecurity Consultant </br>
**Intern:** Onyekwere McDonald Uchenna

---

## 🔍 **Project Overview**

As part of the Datacom Cybersecurity Virtual Internship, I assumed the role of a cybersecurity consultant tasked with investigating and responding to a sophisticated cyberattack and assessing the risk posture of a client organization. The project was split into two major tasks:

* **Task 1:** Conducting an in-depth investigation into the Advanced Persistent Threat group APT34.
* **Task 2:** Performing a comprehensive cybersecurity risk assessment for the affected organization.

Through both tasks, I applied real-world tools and frameworks including **OSINT (Open Source Intelligence)** and the **MITRE ATT\&CK Framework** to analyze threats, evaluate vulnerabilities, and propose risk mitigation strategies. This project provided me with hands-on experience in identifying cyber threats, assessing organizational risks, and crafting professional, executive-level recommendations.

---

## 🔎 Task 1: Threat Intelligence Report on APT34

**Objective:**
To conduct an initial investigation into the notorious APT34 group (aka "OilRig") using OSINT tools and apply the MITRE ATT\&CK framework to recommend actionable defense strategies to the client.

### 🧭 **Purpose of the Task**

The purpose of this task was to identify the threat actor responsible for a targeted cyberattack on a major tech corporation and to assess their tactics, targets, and threat level. This would enable the client to understand the potential impact and prepare defenses accordingly.

---

### 🔨 **Steps Taken and What I Did**

#### 1. **Gathered Intel Using OSINT Tools**

I utilized multiple open-source cybersecurity platforms such as:

* **Mandiant**, **CrowdStrike**, **Symantec Threat Intelligence**, and **Kaspersky** for group profiles and threat insights.
* **CyberScoop** and **Dark Reading** for news on APT34's latest activity.
* **MITRE ATT\&CK** to analyze their tactics, techniques, and procedures (TTPs).

#### 2. **Analyzed APT34's Background & Capabilities**

I discovered that:

* APT34 is **state-sponsored** and linked to **Iran**.
* Their targets include sectors such as **oil & gas, finance, government, and critical infrastructure**.
* Their motive is **espionage and strategic advantage**.

#### 3. **Identified Their TTPs**

APT34 uses a range of advanced techniques, such as:

* **Spear phishing** with malicious attachments or links.
* **Credential dumping and password spraying**.
* Deployment of **custom malware** (e.g., PowBAT, Tonnerre).
* **Living-off-the-land** tactics to remain undetected.

#### 4. **Mapped to MITRE ATT\&CK**

Using MITRE ATT\&CK, I linked APT34's behavior to the following:

* **Initial Access:** Phishing (T1566.001)
* **Execution:** PowerShell (T1059.001)
* **Persistence:** Web Shells (T1505.003)
* **Exfiltration:** Exfiltration Over Web Service (T1567)

---

### 📧 **Findings Email Summary** *(Delivered to Client)*

> **Subject:** Security Brief: Threat Group APT34 – Findings & Recommendations
> 
> **Dear Leadership Team,**
> 
> As part of our commitment to strengthening your organization’s cybersecurity, I’ve conducted an investigation into a known threat actor, **APT34**, and prepared key findings along with practical recommendations to help protect your systems and data.
> 
> ---
> 
> ### 🔍 Who is APT34?
> 
> * APT34 (also known as OilRig) is a **cyber-espionage group** believed to be backed by the **Iranian government**.
> * Active since at least **2014**, their main goal is **unauthorized access to sensitive information**, especially in industries like **energy, government, and finance**.
> 
> ---
> 
> ### Who Do They Target?
> 
> * **Industries:** Government agencies, oil & gas, financial services, telecom, and critical infrastructure.
> * **Regions:** Primarily the **Middle East**, but attacks can happen globally based on political interests.
> 
> ---
> 
> ### How Do They Operate?
> 
> APT34 typically uses:
> 
> * **Phishing emails** to trick staff into clicking malicious links or opening infected files.
> * **Stolen passwords** or access to compromised accounts.
> * Custom malware to quietly **monitor, steal data**, and stay hidden inside networks.
> 
> ---
> 
> ### What Can We Do?
> 
> To reduce our risk, I recommend the following high-impact measures:
> 
> 1. **Staff Awareness & Training**
>    * Educate employees on phishing and suspicious emails.
> 2. **Strong Access Controls**
>    * Use **Multi-Factor Authentication (MFA)** for all key systems.
> 3. **Regular Software Updates**
>    * Keep all systems and applications up to date to fix known security flaws.
> 4. **Improved Monitoring**
>    * Implement tools that alert us to unusual activity (e.g., strange logins or file transfers).
> 5. **Backups & Recovery**
>    * Maintain regular, secure backups to recover quickly if needed.
> ---
> 
> ### ✅ Final Note
> 
> While APT34 is a serious threat, the right precautions can greatly reduce our exposure. I recommend we review our current defenses and prioritize the steps above.
> Please let me know if you’d like a short briefing session or written risk summary specific to your department.
> 
> Best regards,</br>
> **Onyekwere McDonald Uchenna** </br>
> Cybersecurity Consultant

---

## 🧠 **What I Learned in Task 1**

* The power of OSINT in understanding threat actors.
* How to connect attacker behavior to known techniques using MITRE ATT\&CK.
* How to write concise, professional communications for executive leadership.

---

## ⚖️ Task 2: Cybersecurity Risk Assessment

**Objective:**
To conduct a detailed cybersecurity risk assessment for the client organization, using the padlock-and-fence analogy to evaluate the current security controls and identify new risks.

---

### 🧭 **Purpose of the Task**

The aim was to determine the level of risk associated with potential cybersecurity threats and vulnerabilities to help the client make informed decisions about protecting their information and infrastructure.

---

### 🔨 **Steps Taken and What I Did**

## ✅ **1. Define the Context (Assets to Protect)**

| **Asset**               | **Description**                                                                              | **Value**                         |
| ----------------------- | -------------------------------------------------------------------------------------------- | --------------------------------- |
| Client Database         | Contains sensitive customer data (e.g. names, emails, billing info, login credentials).      | High (\$500,000+ breach cost)     |
| Financial Records       | Includes payroll data, invoices, bank account information.                                   | Very High (\$1,000,000+ impact)   |
| Internal Communications | Emails, chat logs, meeting minutes – could reveal internal strategies and confidential data. | Medium (\$150,000+ risk exposure) |
| Intellectual Property   | Business strategy documents, proprietary tools, trade secrets.                               | Very High (Intangible, strategic) |
| Network Infrastructure  | Routers, switches, servers that power the entire digital environment.                        | High (\$300,000+ to restore)      |

---

## ✅ **2. Define the Risk Matrix**

### ➤ Likelihood Descriptions

| **Likelihood** | **Description**                                       |
| -------------- | ----------------------------------------------------- |
| Rare           | May happen only in exceptional circumstances          |
| Unlikely       | Could occur at some time but not expected             |
| Possible       | Might occur occasionally                              |
| Likely         | Will probably occur in most circumstances             |
| Almost Certain | Expected to occur in most circumstances or frequently |

### ➤ Consequence Descriptions

| **Consequence** | **Description**                                                       |
| --------------- | --------------------------------------------------------------------- |
| Severe          | Catastrophic impact – data loss, regulatory action, bankruptcy        |
| Major           | Serious impact – loss of reputation, large financial loss             |
| Moderate        | Noticeable disruption – service outages, moderate financial penalties |
| Minor           | Minor disruption – some system downtime, no significant cost          |
| Insignificant   | Little to no impact – minor inconvenience                             |

### Risk Matrix Table

<img width="1898" height="423" alt="risk matrix" src="https://github.com/user-attachments/assets/ba6d3163-d9d3-4387-bec4-034132e66e5c" />

---

## ✅ **3. Define Three Risk Scenarios**

Here are **3 sample scenarios** using the padlock (physical and cyber defense) analogy:

### **R01 – External Cyberattack (e.g. Phishing or Exploit)**

* **Source:** APT34 targeting employee emails with phishing.
* **Consequence:** Breach of sensitive data.

### **R02 – Insider Threat (Negligence or Malice)**

* **Source:** Employee downloads malicious software or leaks info.
* **Consequence:** Exposure of internal systems, data manipulation.

### **R03 – Physical Intrusion or Theft**

* **Source:** Someone physically bypasses perimeter fence/padlock.
* **Consequence:** Theft of hardware or physical access to server/data center.

---

## ✅ **4–6. Risk Rating Table**

| **Risk ID** | **Title**          | **Description**                                          | **Source / Cause**               | **Consequence**                                                           | **Inherent Likelihood** | **Inherent Consequence** | **Inherent Risk Level** | **Existing Measures**                                                                                                                                                             | **Existing Effectiveness**                                                                                                                                          | **Current Likelihood** | **Current Consequence** | **Current Risk Level** | **Additional Measures**                                                                                                                               | **Additional Effectiveness**                                                                                                                                 | **Target Likelihood** | **Target Consequence** | **Target Risk Level** |
| ----------- | ------------------ | -------------------------------------------------------- | -------------------------------- | ------------------------------------------------------------------------- | ----------------------- | ------------------------ | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------------------- | ---------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------- | ---------------------- | --------------------- |
| **R01**     | Cyberattack        | Exploitation of unpatched systems or phishing staff      | APT34 – Spear phishing, malware  | Unauthorized access, data exfiltration, reputational and financial damage | **Likely**              | **Severe**               | **Extreme**             | **Firewall** (in place but lacks deep packet inspection); **Antivirus** (updated regularly); **Employee logins** (weak passwords & no MFA); **Basic spam filter** on email server | **Good** – Firewalls and antivirus are maintained but lack advanced threat protection. Employee awareness is minimal, increasing phishing success rate.             | **Possible**           | **Major**               | **Very High**          | **Implement Multi-Factor Authentication (MFA)**, conduct **quarterly security awareness training**, enforce **patch management policy**               | **Excellent** – These measures close the most exploited vectors used by APT34 (phishing, credential theft, and vulnerabilities in unpatched systems).        | **Unlikely**          | **Major**              | **High**              |
| **R02**     | Insider Threat     | Malicious or careless employee leaks or manipulates data | Employee negligence or malice    | Loss of intellectual property, operational disruption                     | **Possible**            | **Major**                | **Very High**           | **Role-based access controls** (not consistently enforced); **Limited admin rights** for most users; **Basic onboarding/offboarding process**                                     | **Moderate** – Some access control policies exist but lack continuous enforcement and regular review. No monitoring tools to detect unusual user behavior.          | **Possible**           | **Moderate**            | **Medium**             | Implement **Data Loss Prevention (DLP)** tools, **automated user behavior monitoring**, and **quarterly access rights reviews**                       | **Good** – These steps increase visibility into internal misuse, reduce unnecessary access, and detect insider activity early.                               | **Unlikely**          | **Moderate**           | **Low**               |
| **R03**     | Physical Intrusion | Unauthorized entry through perimeter or on-site break-in | Ex-employee or outsider breaches | Theft of servers or gaining physical access to sensitive equipment        | **Possible**            | **Major**                | **Very High**           | **Fence and padlock** around perimeter; **Manual guard patrols** (8 hours/day); **Reception logbook** for visitors                                                                | **Moderate** – The fence and padlock deter casual intruders but can be bypassed easily. No night coverage, no real-time surveillance, and no automated access logs. | **Unlikely**           | **Moderate**            | **Medium**             | Install **24/7 CCTV coverage**, add **biometric access control** to server rooms, and implement an **alarm system** connected to emergency responders | **Good** – Biometric and video surveillance systems provide reliable tracking and instant alerts, while alarms ensure a rapid response to break-in attempts. | **Rare**              | **Moderate**           | **Low**               |

---

## ✅ **7. Risk Assessment Summary Report**

> ### **Client Risk Assessment Report – Summary**
> 
> **Context**:
> The client is protecting a mixture of digital and physical assets such as sensitive databases, financial information, and IT infrastructure. The estimated financial value of these assets is over \$2 million. The perimeter padlock and fence represent initial physical controls, but additional digital safeguards are necessary.
> 
> **Key Risk Scenarios Identified**:
> 
> 1. **Cyberattack** – High risk from APT34 and similar actors.
> 2. **Insider Threat** – Risk from intentional or negligent employee actions.
> 3. **Physical Intrusion** – Risk of unauthorized physical access to infrastructure.
> 
> **Risk Analysis**:
> 
> * **Inherent risk** is very high to extreme across the board due to the valuable nature of the assets and growing cyber threat landscape.
> * **Existing measures** such as padlocks and firewalls reduce risks, but not enough for today’s threat environment.
> * **Target risk** can be reduced to **low or medium** through added controls: MFA, employee training, better physical surveillance, and access monitoring.
> 
> **Recommendations**:
> 
> * Conduct monthly security audits.
> * Deploy endpoint detection & response (EDR) solutions.
> * Train employees quarterly on phishing & social engineering.
> * Introduce biometric access and 24/7 monitoring for high-risk physical areas.
> * Adopt a Zero Trust architecture to segment access internally.

## 🚀 **Final Reflections**

Through this internship, I gained a comprehensive understanding of real-world cybersecurity practices, from intelligence gathering to risk mitigation. I learned how to:

* Use industry frameworks and OSINT tools.
* Break down and assess complex threat scenarios.
* Communicate clearly with technical and non-technical stakeholders.

This experience not only strengthened my cybersecurity foundation but also honed my ability to think strategically, assess threats pragmatically, and recommend real-world solutions in a professional capacity.
