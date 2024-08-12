# Cybersecurity_ElasticSIEM

# Simple Elastic SIEM Lab

## Overview
This guide provides step-by-step instructions to set up a home lab for Elastic Stack Security Information and Event Management (SIEM) using the Elastic Cloud portal and a Kali Linux VM. It will guide you through generating security events, setting up an Elastic Agent to forward data, and querying and analyzing logs within the SIEM. This project can be a valuable addition to your resume and a topic to discuss in interviews.

## Prerequisites
- VirtualBox or VMware
- Basic knowledge of Linux and virtualization software

## Tasks Overview
1. Set up a free Elastic account.
2. Install the Kali Linux VM.
3. Configure the Elastic Agent on the Kali VM to collect logs and forward them to the SIEM.
4. Generate security events on the Kali VM.
5. Query and analyze security events in the Elastic SIEM.
6. Create a Dashboard to visualize security events.
7. Create alerts for security events.

## Task 1: Set Up an Elastic Account
1. Sign up for a free trial at [Elastic Cloud](https://cloud.elastic.co/registration).
2. Log in and create a new Elasticsearch deployment.
3. Choose your preferred region and deployment size.

## Task 2: Set Up the Linux VM
1. Download the Kali Linux VM from the [official Kali website](https://www.kali.org/get-kali/#kali-virtual-machines).
2. Create and start the VM using VirtualBox or VMware.
3. Log in with the default credentials (`kali`/`kali`).

## Task 3: Set Up the Agent to Collect Logs
1. Navigate to the Integrations page in the Elastic SIEM instance.
2. Search for "Elastic Defend" and install it.
3. Copy the command to install the Elastic Agent on your Kali VM and run it in the terminal.

## Task 4: Generate Security Events on the Kali VM
1. Ensure Nmap is installed (`sudo apt-get install nmap`).
2. Run various Nmap scans on the Kali VM or your host machine.

## Task 5: Query Security Events in Elastic SIEM
1. Navigate to the "Logs" tab under "Observability" in your Elastic Deployment.
2. Enter queries to search for Nmap-related events, such as `event.action:"nmap_scan"`.

## Task 6: Create a Dashboard to Visualize Events
1. In the Elastic web portal, navigate to "Dashboards" under "Analytics."
2. Create a new dashboard and add visualizations for security events over time.

## Task 7: Create an Alert
1. Navigate to "Alerts" under "Security" in the Elastic web portal.
2. Create a custom query-based rule to detect Nmap scans and set up notifications.

## Conclusion
This lab provides a hands-on environment for learning and practicing security monitoring and incident response using Elastic SIEM. You can explore different security events, create dashboards, and set up alerts to enhance your skills as a security analyst or engineer.

## Next Steps
- Experiment with different security events on your Kali VM.
- Test and refine the alerts you created.
- Explore various analysis and visualization tools in Elastic SIEM.
- Integrate Elastic SIEM with other data sources like AWS, Azure, Windows event logs, or syslog.

## Acknowledgments
- Written by Abdullahi Ali, Cybersecurity Trainer with a Master's in Cybersecurity.

---


