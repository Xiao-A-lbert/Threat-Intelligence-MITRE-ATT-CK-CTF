# Threat Intelligence and MITRE ATT&CK CTF

<h2>Description</h2>
In this Threat Intelligence task, I explore the Cyber Killchain, different types of intelligence sources, the Pyramid of Pain, the Diamond Model, the Intelligence Lifecycle, and the MITRE ATT&CK Framework. 

<h2>Languages and Utilities Used</h2>

- <b>MITRE ATT&CK</b>

<h2>Environments Used </h2>

- <b>Splunk</b> 

<br />
<br />
The different types of threat intelligence like strategic, tactical, operational, and technical.

![Types of Threat Intelligence](https://github.com/user-attachments/assets/ed73aae5-26ba-4fa0-aecd-1c2c96c0b3e5)

<br />
<br />
The cyber kill chain outlines seven stages of a cyberattack:
Reconnaissance - Attackers gather information about the target.
Weaponization - They create a malicious payload.
Delivery - The payload is delivered via methods like phishing.
Exploitation - The malware is executed on the victim's system.
Installation - The malware is installed to maintain access.
Command and Control (C2) - Attackers establish remote control over the compromised system.
Actions on Objectives - Finally, they achieve their goals, such as data theft or destruction.

![Cybe Killchain](https://github.com/user-attachments/assets/092a3c8c-271e-44f9-8c86-fed25eec9473)

<br />
<br />  
The different types of intelligence sources such as open-source, commercial, vendor publish reports and research, and ISAC. 

![Intelligence Sources](https://github.com/user-attachments/assets/8151519e-e04d-4bbd-8694-7327ec901107)

<br />
<br />
The Pyramid of Pain is a conceptual framework in cybersecurity that categorizes different types of threat indicators based on how difficult they are for attackers to change. It consists of six levels, ranging from easily alterable indicators like hash values and IP addresses at the bottom, to more complex and challenging-to-modify elements like Tactics, Techniques, and Procedures (TTPs) at the top. By focusing on higher levels of the pyramid, security teams can inflict greater disruption on attackers, making it more costly and difficult for them to continue their malicious activities.

![Pyramid of Pain](https://github.com/user-attachments/assets/c4b44d16-8a91-4536-8bc9-6636f6234d55)

<br />
<br />
The Diamond Model of Intrusion Analysis is a framework in cybersecurity that breaks down cyber attacks into four interconnected components: adversary, infrastructure, capability, and victim (or target). This model provides a structured approach to understanding and analyzing cyber threats by examining the relationships between these elements, enabling security teams to gain deeper insights into attack patterns, predict future threats, and develop more effective defense strategies. By visualizing complex attack scenarios and condensing large amounts of data into a simple diagram, the Diamond Model helps cybersecurity analysts explore different links and patterns, ultimately enhancing threat intelligence and incident response capabilities.

![The Diamond Model of Intrusion Analysis](https://github.com/user-attachments/assets/1bfacd39-48c3-435e-b9af-528c74bc82f3)

<br />
<br />
The MITRE ATT&CK Enterprise Matrix is a comprehensive framework that categorizes and visualizes adversary tactics and techniques used in cyberattacks against enterprise environments. It consists of 14 tactics, such as Initial Access, Execution, and Exfiltration, with each tactic containing various techniques that attackers employ to achieve their objectives. This matrix serves as a valuable resource for cybersecurity professionals to understand attack patterns, prioritize defenses, and develop more effective security strategies across different platforms including Windows, macOS, Linux, cloud services, and network infrastructure.

![MITRE ATT CK Framework](https://github.com/user-attachments/assets/6e138767-f29b-492d-a30b-40279dd4c326)

<br />
<br />  
MITRE ATT&CK challenge prompt.

![1) challenge prompt](https://github.com/user-attachments/assets/ec0aabd3-eb78-4cb9-9f46-92da21932412)

<br />
<br />  
Finding the sub-technique id for an Nmap Scripting Engine named vulnerability scanning under active scanning for the reconnaissance tactic.  
    
![2) q1 2](https://github.com/user-attachments/assets/757af97e-1ce6-41f0-ba89-9295f18b4610)

<br />
<br />
The SQL injection for the attacker's initial access is T1190 Exploit Public-Facing Application. 
    
![3) q3](https://github.com/user-attachments/assets/cc134d7b-6119-4a92-8ef8-8fe59c3c8ba0)

<br />
<br />  
The MITRE ID pertaining to zqlmap tool is S0225.
    
![4) q4](https://github.com/user-attachments/assets/6f120a9e-f3d4-4c99-88ba-8675a132d211)

<br />
<br />  
The creation of a reverse shell using the cmd.exe by the attacker is using the Etnerprise Command and Scripting Interpreter > Windows Command Shell T1059.003.
    
![5) q5](https://github.com/user-attachments/assets/16f9be07-0352-450e-b4e8-de0b1db918bb)

<br />
<br />
The attacker escalated privileges using the API calls ImpersonateLoggedUser token impersonation. 
    
![6) q6](https://github.com/user-attachments/assets/2488b110-e0c4-4d4d-b2e0-437bcb68722b)

<br />
<br />  
Modifying an existing Windows service image path by the attacker uses ID: T1543.003 Create or Modify System Process: Windows Service. 

![7) Q7](https://github.com/user-attachments/assets/00ca212a-782e-4e4f-b1d1-2710af350ff8)

<br />
<br />
Disabiling the endpoint EDR by the attacker uses T1562.001 Impair Defenses: Disable or Modify Tools.

![8) Q8](https://github.com/user-attachments/assets/2021ea52-4f16-47c9-b3b9-85d471737e75)

<br />
<br />
Using the ccf32 tool is part of the colleciton tactic by the attacker.

![9) q9](https://github.com/user-attachments/assets/3c9a441e-e2d9-496e-b966-e337afbaa706)

<br />
<br />
The organization should use Mitigation technique M1021 to Restrict Web-Based Content.

![10) q10](https://github.com/user-attachments/assets/7c6e23e0-9da6-4344-b225-8141b11715d3)

<br />
<br />  
External Defacement T1491.002 is the sub-technique the attacker used. 

![11) q11](https://github.com/user-attachments/assets/75915adc-aaf4-491c-9638-ed406a2df954)

<br />
<br />  
