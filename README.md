Task 1: Cybersecurity Risk Assessment

Sample network or System setup:

For the internet connection in a small business environment, you would typically want a reliable and high-speed connection to support the needs of your organization. Here's how you might set it up:
Choose an ISP:  Select a reputable Internet Service Provider (ISP) that offers business-grade services. Consider factors such as reliability, speed, customer support, and pricing.
Internet Connection: Start with a reliable internet service provider (ISP) offering sufficient bandwidth for your needs.

 
Firewall /Router: Install a business-grade firewall/router to protect your network from external threats. This device should have features like VPN support, intrusion detection/prevention, and content filtering.
Switches: Use managed switches to connect all devices within your network. Managed switches offer better control and security compared to unmanaged switches.
Wireless Access Point (WAPs): Deploy one or more WAPs strategically throughout your workspace to provide reliable Wi-Fi coverage. Ensure they support the latest encryption standards and have features for guest network segregation.
Server(s): Depending on your needs, you may have one or more servers for various purposes such as file storage, email hosting, application hosting, or domain services (Active Directory).
Workstation: Provide individual workstations for employees, each equipped with necessary software applications and security measures like antivirus software and firewalls. 
Printers/Scanners: Install networked printers and scanners accessible to all employees as needed. Ensure they're properly secured to prevent unauthorized access.
Backup Solution: Implement a robust backup solution to regularly back up critical data. This could involve onsite backups to a dedicated server or network-attached storage (NAS), as well as offsite backups to a cloud service provider.
Email and Collaboration Tools: Set up email accounts for employees using a business email service provider. Additionally, consider collaboration tools such as Slack or Microsoft Teams for internal communication and project management.
Security Measures: Enforce strong password policies, implement multi-factor authentication where possible, and regularly update software and firmware to patch security vulnerabilities. Consider implementing a security information and event management (SIEM) system for advanced threat detection and response.
VPN (Virtual Private Network): Set up a VPN to allow secure remote access to your network for employees working offsite. This ensures that data transmitted between remote locations and the main office is encrypted and secure.
Monitoring and Management Tools: Utilize network monitoring and management tools to keep track of network performance, security threats, and device health. This allows for proactive maintenance and troubleshooting.
Documentation and Training: Maintain detailed documentation of your network/system setup and provide training for employees on security best practices and proper use of company resources.
Regular Audits and Updates: Conduct regular security audits and updates to ensure that your network/system remains secure and compliant with relevant regulations.

Networking Environment: A medium-sized corporate network with servers, workstations, network device.
Assets: File servers, Email servers, Employee workstations, Routers, Switches, Firewalls.
Software: windows server 2019, Microsoft office 365, cisco routers, Palo Alto firewalls.

Threats and Vulnerabilities

Hardware Infrastructure:
Server: Depending on your needs, consider having a dedicated server for hosting essential services like file sharing, email, or applications. This server could be a physical machine or a virtual server.
Workstations: Equip each employee with a desktop or laptop computer with sufficient processing power, memory, and storage to perform their tasks efficiently.
Networking Equipment: Install switches, routers, and wireless access points to connect all devices within the network. Consider using managed switches for better control and security.
Printers and Scanners: Set up networked printers and scanners accessible to all employees as needed.
Operating Systems and Software:
Server OS: Choose an appropriate server operating system such as Windows Server, Linux distributions like Ubuntu Server or CentOS, or macOS Server. 
Workstation OS: Install operating systems like Windows 10 Pro, macOS, or Linux distributions like Ubuntu Desktop on employee workstations.


Productivity Software: Provide employees with essential productivity software such as Microsoft Office Suite or Google Workspace for word processing, spreadsheets, and presentations.
Security Software: Install antivirus and anti-malware software on all devices to protect against security threats.
Backup Software: Implement backup software to regularly back up critical data stored on servers and workstations.

1.	Network Services:

o	Domain Controller: If applicable, set up a domain controller using Active Directory (Windows) or LDAP (Linux) for centralized user authentication and management.
o	File Sharing: Configure file sharing services to allow employees to access and collaborate on shared documents and files securely.
o	Email sharing: Set up email hosting either on-premises using Microsoft Exchange or a similar solution, or consider cloud-based email services like Microsoft 365 or Google Workspace.
o	Remote Access: Enable remote access to the network using VPN (Virtual Private Network) for secure connections from outside the office.

2.	Security Measures:

o	Firewall: Implement a firewall to protect the network from unauthorized access and malicious traffic. Configure firewall rules to allow only necessary inbound and outbound traffic.
o	Encryption: Use encryption protocols such as SSL/TLS for secure communication over the network and encrypt sensitive data stored on servers and workstations.
o	User Authentication: Enforce strong password policies and consider implementing multi-factor authentication for an added layer of security.
o	Regular Updates and Patches: Keep all software and firmware up to date with the latest security patches to protect against known vulnerabilities.

3.	Monitoring and Management:

o	Network monitoring: Utilize network monitoring tools to keep track of network performance, detect issues, and ensure optimal operation.
o	Asset Management: Maintain an inventory of all hardware and software assets, including serial numbers, licenses, and warranty information.
o	Incident Response: Develop and document incident response procedures to address security incidents and minimize their impact on business operations. 

4.	Documentation and Training:

o	Documentation: Keep detailed documentation of the system setup, network configuration, and security policies for reference and troubleshooting.
o	Training: Provide training to employees on how to use the system effectively and adhere to security best practices.



Threats and Vulnerabilities Identification
   Router: 
•	Threats: Someone getting into the router and messing with settings. 
•	Vulnerabilities: Easy-to-guess passwords or not updating the router's security. 
  Switch: 
•	Threats: Someone sneaking into the network by tricking the switch. 
•	Vulnerabilities: Weak passwords or not setting up the switch's security features properly. 
Departments:
•	Threats: Employees accidentally or purposely causing trouble with the network.
•	Vulnerabilities: Using easy passwords or not updating software, making it easier for             attackers to get in.
 Firewall: 
•	Threats: Employees accidentally or purposely causing trouble with the network. 
•	Vulnerabilities: Using easy passwords or not updating software, making it easier for attackers to get in.
File server 
•	Threats: Someone breaking into the file server and stealing or messing with files.
•	Vulnerabilities: Letting too many people access the files or not protecting them well enough. 
 Printer   
•	Threats: Hackers targeting the printer to cause problems or steal data. 
•	Vulnerabilities: Keeping default passwords or not updating the printer's security. 
Internet Connection
•	Threats: Cyberattacks from outside, like viruses or hackers trying to break in.
•	Vulnerabilities: Weak spots in the connection could let attackers in, like if the     firewall isn't set up right.
Vulnerability Scanning:
External Scans: These scans focus on identifying vulnerabilities present in systems and services accessible from outside the organization's network, such as web servers, email servers, and remote access services.
Internal Scans: Internal scans target vulnerabilities within the organization's internal network, including servers, workstations, and other devices. They help identify security issues that may be exploited by malicious insiders or compromised systems.
Authenticated Scans: Authenticated scans, also known as credentialed scans, involve using valid credentials to access systems and perform more in-depth scans. Authenticated scans can identify vulnerabilities that are only visible to authenticated users and provide a more accurate assessment of the system's security posture.
Unauthenticated Scans: Unauthenticated scans do not require valid credentials and focus on identifying vulnerabilities visible from the network perimeter. While unauthenticated scans are less intrusive, they may not provide a complete picture of the system's security posture.
Tools: There are numerous vulnerability scanning tools available, ranging from open-source to commercial solutions. Popular vulnerability scanning tools include Nessus, OpenVAS, Qualys, Rapid7 Nexpose, and Nmap. 


Risk Analysis:
High-risk vulnerabilities 
•	Unpatched servers pose a significant risk as they can be exploited remotely.
•	Weak passwords increase the likelihood of unauthorized access.
•	Lask of network segmentation can lead to lateral movement during a breach.

Priority:
•	Patching critical vulnerabilities on servers.
•	Strengthening password policies.
•	Implementing network segmentation measures.
Mitigation Strategies
•	Implement the principle of least privilege. 
•	Grant users only the minimum access permissions required for their job functions. 
•	Conduct regular reviews of user access privileges and revoke unnecessary permissions.
•	Review and enhance network segmentation.
•	Deploy intrusion detection and prevention systems.




Task 2
Incident Response Simulation
1.	Scenario Creation:
You are part of the IT security team at a medium-sized financial services company. Over the past few weeks, there have been reports of increased phishing activity targeting employees. Despite ongoing security awareness training, some employees have fallen victim to these phishing attempts, leading to potential security breaches and data loss.

Goals of the Simulation:

Test employees' ability to recognize and report phishing attempts.
Assess the effectiveness of the organization's email filtering and security awareness training programs.
Evaluate the incident response procedures for handling suspected phishing incidents, including communication protocols, investigation techniques, and remediation steps.
Identify areas for improvement in security controls, employee training, and incident response capabilities.

Simulation:

Send out simulated phishing emails to a select group of employees, monitoring their   responses and actions.
Track the number of employees who clicked on the phishing link, entered their credentials, or reported the suspicious email to the IT/security team.

2.	Incident Detection:

 Role:
	Incident Response Team Lead
	Network Analyst
	System Administrator
	Forensic Analyst

Simulation:
	The interns can be given access to simulated logs generated by various systems, including email servers, firewalls, antivirus software, and network devices.
	The interns can use monitoring tools provided by the organization to analyze network traffic, monitor system logs, and review security alerts.
	These tools may include SIEM platforms, packet analyzers, and threat intelligence feeds.
	The interns will then use the monitoring tools and provided logs to detect and investigate these simulated incidents.

3.	Response Plan Execution:

Role and Procedures:
	Team lead will coordinate the incident response.
	Network Analyst and system administrator will work on isolating affected systems and blocking malicious activity. 
Simulation:
	Under the Response Plan incident, the Incident Coordinator deploys tasks for the members of the team to help contain the phishing.
	Technical Support disables the compromised email accounts and resets their passwords to refrain from further unauthorized access.
	A communication Liaison sends a company-wide email on the issue of phishing attack and reminders with reference to cybersecurity practices. to all employees.
4.	Forensic Analysis:
            Role:
                           Forensic Analysis
              Root cause:
                     Performing forensic analysis on affected systems or data is crucial for understanding the root cause of the incident and gathering evidence for post-incident analysis.
Gather evidence and logs for post-incident analysis:
	Collect logs from affected systems, including servers, workstations, and network devices. This may include event logs, security logs, application logs, and firewall logs.
	Analyze SMTP logs, message tracking logs, and mailbox audit logs to identify any unauthorized email activity or unusual patterns.
	Collect firewall logs and IDPS logs to monitor inbound and outbound network traffic. Look for signs of unauthorized access attempts, malware communication, or exploitation attempts.
	Use memory forensics tools to extract artifacts such as running processes, open network connections, and loaded DLLs for further analysis.

5.	Post-Incident Assessment:

	A post-incident meeting will be held to review the effectiveness of the response plan.
	Lessons learned and areas for improvement will be discussed.






