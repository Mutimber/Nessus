# Nessus
## Objective 
This lab guides users through setting up Nessus Essentials, a free version of the Nessus vulnerability scanning platform, for personal use. It covers installation, activation, and basic usage within a Kali Linux environment.
## Skills
1. Installation and configuration of software packages (Nessus Essentials) on a Linux system.
2. Understanding of vulnerability scanning concepts and tools.
3. Familiarity with navigating web-based graphical user interfaces for security tools.
4. Ability to customize scan settings and templates for specific scanning tasks.
5. Interpretation of scan results and identification of vulnerabilities.
6. Knowledge of best practices for addressing security issues identified by vulnerability scanners.
7. Experience in using Nessus for vulnerability assessment and management purposes.
8. Practical understanding of security scanning methodologies and workflows.

## Steps
1. Download the Nessus Essentials .deb file from Tenable's website.
2. Install Nessus using the sudo dpkg -i command in the terminal.
3. Start the Nessus service with service nessusd start and access the web GUI at https://kali:8834/.
4. Register for Nessus Essentials or input the activation code received via email.
5. Create a username and password for accessing Nessus locally within the VM.
6. Wait for Nessus to download plugins and essential files.
7. Explore the Nessus dashboard, launching scans, and creating policies.
8. Customize scan settings and select the Basic Network Scan template.
9. Enter the target (e.g., localhost) and save the scan settings.
10. Launch the scan and review the results, identifying vulnerabilities and potential security issues.
11. Investigate specific vulnerabilities, accessing descriptions, risk information, and solutions provided by Nessus.
