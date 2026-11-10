DatSecure Limited – Network Simulation and Security Implementation
This project documents the design, configuration, and security implementation of a virtual office network for DatSecure Limited, a Luxembourg-based data processing company specializing in sensitive healthcare information. Using Cisco Packet Tracer, the project simulates a segmented departmental network and implements Access Control Lists (ACLs) to control communication and protect sensitive resources. The project demonstrates practical networking, connectivity testing, and network access control.
Table of Contents
- Project Overview
- Network Topology
- Tools and Technologies
- Configuration Steps
- Results and Findings
- Author
Project Overview
DatSecure Limited is a data processing company that handles sensitive information, particularly within the healthcare sector. As part of its North American development, the company required a secure, scalable, and efficient network infrastructure for its new headquarters.

The objective of this project was to design and simulate a virtual office network using Cisco Packet Tracer to test network configurations, verify connectivity, identify security weaknesses, and implement appropriate security controls before real-world deployment.

In this project, I assumed the role of a Junior Network Engineer and Cybersecurity Analyst, with responsibilities covering:
- Network design and configuration.
- Departmental network connectivity.
- IP address configuration.
- Connectivity verification.
- Implementation of Access Control Lists (ACLs).
- Network traffic management and access restrictions.
The primary objectives were to:
- Create a departmental network using switches and a router.
- Configure IP addresses for departmental devices.
- Verify network connectivity using ping.
- Implement ACLs to manage and restrict network traffic.
- Test server availability and departmental access permissions.
Network Topology
The simulated office network consists of three organizational departments: Administration, Sales, and Human Resources (HR).

Each department has its own switch and two PCs. All departmental networks connect through a central router named DatSecure Router.

A server is also connected to the Administration network to represent a centralized organizational resource.
Network Components
- Router: One central DatSecure router connecting all departmental networks.
- Switches: Three switches, with one dedicated to each department.
- PCs: Six PCs, with two devices assigned to each department.
- Server: One server located within the Administration network.
Departmental Network Structure
Department	Devices	Access Level
Administration (Admin)	2 PCs	Full access
Sales	2 PCs	Limited access
Human Resources (HR)	2 PCs	Restricted access (internet only)

Network Security and Access Control
The network was segmented to improve departmental control and protect sensitive organizational resources.

The server was placed within the Administration network, and ACLs were configured on the router to control access to it.

The access requirements were:
- Administration: Full access to the server.
- Sales: Permitted access to the server.
- HR: Denied access to the server, including HTTP access.
This configuration ensured that only authorized departments could communicate with the server while restricting access from HR.
Tools and Technologies
- Cisco Packet Tracer: Used to design, simulate, and configure the virtual office network.
- Cisco Router: Used to connect departmental networks and implement traffic control.
- Network Switches: Used to connect PCs within each department.
- End Devices (PCs): Used to simulate departmental workstations.
- Server: Used to represent a centralized organizational resource.
- Access Control Lists (ACLs): Used to restrict and manage network traffic based on departmental access requirements.
- Ping: Used to test connectivity between network devices and verify server accessibility.
Configuration Steps
1. Designed the Network Topology
   - Created a virtual office network in Cisco Packet Tracer.
   - Established three departmental networks: Administration, Sales, and HR.
   - Added a central router, three departmental switches, six PCs, and one server.
2. Connected Network Devices
   - Connected each department's two PCs to its dedicated switch.
   - Connected the departmental switches to the central DatSecure router.
   - Connected the server to the Administration network.
3. Configured Departmental IP Addresses
   - Assigned IP addresses to the departmental devices.
   - Configured the network to support communication between the different departmental networks.
4. Configured Network Routing
   - Used the DatSecure router to connect the three departmental networks.
   - Established inter-network communication to enable devices across departments to communicate according to their access permissions.
5. Implemented Access Control Lists (ACLs)
   - Configured ACLs on the router to manage access to the Administration server.
   - Allowed Administration PCs full access to the server.
   - Permitted Sales PCs to access the server.
   - Restricted HR PCs from accessing the server, including through HTTP.
   - Applied access restrictions to enforce the organization's departmental security requirements.
6. Performed Connectivity Testing
   - Used ping commands to verify communication between devices.
   - Tested connectivity within departmental networks.
   - Conducted inter-network connectivity tests.
   - Verified server accessibility from Administration and Sales PCs.
7. Verified Access Control and Security
   - Confirmed that Administration and Sales PCs could successfully reach the server.
   - Tested HR access to the server and confirmed that connections were unsuccessful.
   - Verified that the configured ACLs enforced the intended departmental access restrictions.
Results and Findings
The network simulation successfully achieved the project's primary objectives by establishing departmental connectivity and implementing access restrictions to protect sensitive organizational resources.
1. Successful Network Segmentation
- Successfully created three departmental networks: Administration, Sales, and HR.
- Connected all departmental networks through the central router.
- Established communication between devices within their respective networks.
2. Successful Connectivity Verification
- Used ping tests to verify inter-network communication.
- Confirmed that Administration and Sales PCs could successfully communicate with the server.
- Verified that HR PCs could not successfully connect to the server.
3. Successful ACL Implementation
- Implemented ACLs on the router to control departmental access to the server.
- Granted Administration and Sales access to the server.
- Restricted HR access to the server, including HTTP access.
- Demonstrated how ACLs can enforce organizational security requirements and prevent unauthorized access.
4. Improved Network Security
- Demonstrated how network segmentation supports departmental access control.
- Protected sensitive server resources by limiting access to authorized departments.
- Improved control over network traffic and departmental communication.
Key Learning Outcomes
This project provided practical experience in:
- Designing and simulating a departmental office network.
- Understanding network segmentation and device connectivity.
- Configuring routers and switches in Cisco Packet Tracer.
- Implementing Access Control Lists (ACLs).
- Performing network connectivity tests using ping.
- Applying access restrictions to protect sensitive organizational resources.
Conclusion:

The project successfully demonstrated how network design, segmentation, and Access Control Lists can work together to improve network security. For organizations such as DatSecure Limited that handle sensitive healthcare information, controlling access to critical resources is essential for protecting data and maintaining secure network operations.
Author
Moyinoluwa
- Role: Junior Network Engineer and Cybersecurity Analyst (Project Simulation)
- Field: Governance, Risk & Compliance (GRC) and Cybersecurity
- Location: Ottawa, Ontario, Canada
- Training: 10alytics GRC – June 2026 Cohort
