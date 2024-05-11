Ethical Hacking Technical Report
Client: Carpo’s Sex Toys Inc.
Date: 05/11/2024
Prepared By: John Francis C. Carpo and Florence Kyle D. Felices 
Executive Summary: This report presents the technical findings of the ethical hacking assessment conducted for Carpo’s Sex Toys Inc. The assessment aimed to identify vulnerabilities within the organization's network infrastructure, applications, systems and etc. Through various testing methodologies, including penetration testing and vulnerability scanning, critical and high-risk issues were discovered. This report provides detailed descriptions of these findings, along with actionable recommendations for remediation.
Vulnerability Summary:
Network Infrastructure
1. Vulnerability: Outdated Router Firmware
   - Description: The company's routers are running outdated firmware (e.g., Firmware version 1.0.3), exposing them to known security vulnerabilities.
   - Risk: Critical

2. Vulnerability: Lack of Intrusion Detection System (IDS)
   - Description: The absence of an IDS leaves the network susceptible to advanced persistent threats and zero-day attacks.
   - Risk: High

3. Vulnerability: Weak Encryption Protocols
   - Description: Usage of outdated encryption protocols (e.g., WEP, TKIP) in wireless network configurations.
   - Risk: Critical

Web Applications
4. Vulnerability: Cross-Site Scripting (XSS) in E-commerce Platform
   - Description: The E-commerce website (Version 2.1.0) is vulnerable to XSS attacks, allowing malicious scripts to be injected into web pages viewed by other users.
   - Risk: Critical

5. Vulnerability: SQL Injection in Product Search Functionality
   - Description: The product search functionality of the website (Version 2.1.0) is susceptible to SQL injection attacks, potentially leading to unauthorized access to the database.
   - Risk: High

Operating Systems
6. Vulnerability: Unpatched Operating System (OS) on Servers
   - Description: Servers running on outdated operating systems (e.g., Windows Server 2008 R2) without security patches and updates.
   - Risk: Critical

7. Vulnerability: Weak Password Policy on Employee Workstations
   - Description: Lack of a comprehensive password policy for employee workstations leading to weak passwords and susceptibility to brute force attacks.
   - Risk: High

Databases
8. Vulnerability: Unsecured MongoDB Database
   - Description: Company's MongoDB database (Version 4.2.3) is exposed to the internet without proper access controls, making it vulnerable to unauthorized access and data exfiltration.
   - Risk: Critical

Wireless Networks
9. Vulnerability: Unauthorized Access Points
   - Description: Presence of unauthorized and unsecured wireless access points within the company's premises, potentially facilitating unauthorized network access.
   - Risk: High

Physical Security
10. Vulnerability: Lack of Surveillance Cameras in Server Room
   - Description: Absence of surveillance cameras in the server room, posing a risk of unauthorized physical access to critical infrastructure.
   - Risk: High

Social Engineering
11. Vulnerability: Lack of Employee Awareness on Phishing Attacks
   - Description: Employees are not sufficiently trained to recognize and report phishing attempts, increasing the risk of data breaches through social engineering tactics.
   - Risk: High

Cloud Services
12. Vulnerability: Insecure Configuration of AWS S3 Bucket
   - Description: Improperly configured AWS S3 bucket (e.g., Bucket name: xyz-toys-inc) leading to potential exposure of sensitive data to unauthorized users.
   - Risk: Critical

IoT Devices
13. Vulnerability: Lack of Regular Firmware Updates for Smart Toys
   - Description: IoT devices, such as smart toys, are not receiving regular firmware updates, leaving them vulnerable to exploitation and compromise.
   - Risk: High

Mobile Applications
14. Vulnerability: Insecure Data Storage in Mobile App
   - Description: The company's mobile app (Version 3.0.2) stores sensitive data insecurely on users' devices, making it susceptible to unauthorized access.
   - Risk: Critical

APIs (Application Programming Interfaces)
15. Vulnerability: Insufficient API Authentication Mechanism
   - Description: APIs used for internal and external integrations lack robust authentication mechanisms, potentially leading to unauthorized access and data breaches.
   - Risk: High

Recommendations
Network Infrastructure
- Implement regular firmware updates for routers and network devices.
- Deploy and configure a robust Intrusion Detection System (IDS).
- Upgrade wireless network encryption to modern protocols (e.g., WPA3).

Web Applications
- Conduct regular security assessments and code reviews for the E-commerce platform.
- Implement parameterized queries to mitigate SQL injection vulnerabilities.

Operating Systems
- Apply critical security patches and updates to all servers.
- Enforce strong password policies for employee workstations.

Databases
- Secure the MongoDB database with proper access controls and encryption.
- Regularly assess and monitor database security configurations.

Wireless Networks
- Conduct regular scanning to detect and remove unauthorized access points.
- Implement strong authentication mechanisms for wireless access.

Physical Security
- Install surveillance cameras in critical areas like server rooms.
- Restrict physical access to sensitive areas through access control systems.

Social Engineering
- Conduct regular security awareness training to educate employees on identifying and reporting phishing attempts.
- Implement email authentication mechanisms to mitigate phishing attacks.

Cloud Services
- Review and enhance the security configuration of AWS S3 buckets.
- Implement encryption and access control policies for sensitive data stored in the cloud.

IoT Devices
- Establish a process for regular firmware updates and security patches for IoT devices.
- Implement network segmentation to isolate IoT devices from critical systems.

Mobile Applications
- Encrypt sensitive data stored in the mobile app and utilize secure storage mechanisms.
- Implement secure coding practices and regular security assessments for the mobile app.

APIs (Application Programming Interfaces)
- Enforce strong authentication and access controls for all APIs.
- Implement API security best practices, such as OAuth 2.0 and JWT token validation.

Conclusion
The findings of the ethical hacking assessment reveal critical vulnerabilities across various domains, posing significant risks to the security and integrity of Carpo’s Sex Toys Inc.'s operations. It is imperative for the organization to promptly address these vulnerabilities by implementing the recommended remediation measures. By doing so, Carpo’s Sex Toys Inc. can significantly enhance its security posture, mitigate potential threats, and safeguard sensitive data and assets from exploitation and unauthorized access.
This concludes the technical report, aligning with the specified requirements for vulnerability identification and actionable recommendations for remediation. If there is anything else you would like to add or modify, please feel free to let us know!  

Signature: 


John Francis C. Carpo
1st Ethical Hacker


Florence Kyle D. Felices
2nd Ethical Hacker
