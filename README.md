# Securing-a-Cloud-based-Healthcare-Application

# Scenario Overview: 
Your group has been assigned a project to assess the security vulnerabilities in a healthcare company's cloud infrastructure. The application is designed to store and manage sensitive patient data, including medical records, personal information, and billing details. Your task is to ensure the confidentiality, integrity, and availability of the application and its data, as well as to identify and mitigate potential security risks. The project will involve various aspects of cloud security, including identity and access management, data encryption, network security, and vulnerability management.

The company relies on the cloud to store and manage sensitive patient data, conduct telemedicine consultations, and host critical healthcare applications. However, due to various security oversights and misconfigurations, the infrastructure is highly vulnerable to potential attacks. Your task is to identify and exploit these vulnerabilities to highlight the risks associated with the insecure cloud infrastructure and provide recommendations for remediation. 

The application stack consists of the following components:

Web servers: These serve the frontend of the website and handle user requests.
Application servers: These handle the business logic and process user requests.
Database servers: These store product information, user details, and medical history.
 

# Infrastructure Details: 
1. Cloud Provider: The healthcare company uses a popular cloud service provider (e.g., AWS, Azure, Google Cloud) for hosting its infrastructure.
2. Data Storage: Patient records, medical images, and other sensitive healthcare data are stored in cloud-based databases and file storage systems.
3. Virtual Machines (VMs): The company utilizes VMs for hosting healthcare applications and databases.
4. Network Configuration: The cloud infrastructure has several virtual networks and subnets for different departments and services within the company.
5. Identity and Access Management (IAM): The healthcare company employs IAM policies and access controls for managing user access to cloud resources.
6. The IT department requires full access to both frontend and backend instances for management purposes.
7. All instances should be automatically assigned public and private IP addresses where necessary
8. The VPC should be designed to accommodate future growth and scalability.
 

# Insecure Infrastructure Issues:
1. Weak Access Controls: The IAM policies and access controls have been misconfigured, resulting in excessive permissions and unauthorized access to critical resources. IAM policies are available in the Midterm section under the Modules tab.
2. Unencrypted Data: Sensitive patient data stored in databases and file storage systems is not adequately encrypted, making it susceptible to unauthorized access.
3. Vulnerable Virtual Machines: The VMs running healthcare applications and databases have outdated software and unpatched vulnerabilities.
4. Inadequate Network Security: Network security groups and firewall rules have not been properly configured, allowing unrestricted access to sensitive resources.
5. Lack of Logging and Monitoring: The infrastructure lacks robust logging and monitoring mechanisms, making it difficult to detect and respond to security incidents.
6. Insufficient Disaster Recovery: There is no comprehensive backup and disaster recovery plan in place, making the infrastructure susceptible to data loss and extended downtime.
 

# Project Tasks:
1. Assess the IAM policies and access controls, identifying vulnerabilities and excessive permissions.
2. Exploit weak access controls to gain unauthorized access to critical resources and demonstrate the potential impact.
3. Perform a security assessment of the databases and file storage systems, highlighting the risks associated with unencrypted data.
4. Exploit vulnerabilities in the virtual machines to gain unauthorized access or demonstrate the potential impact of an attack.
5. Evaluate the network security configuration, identifying vulnerabilities and demonstrating the consequences of unrestricted access.
6. Analyze the logging and monitoring capabilities, identifying weaknesses and proposing improvements for detecting and responding to security incidents.
7. Assess the disaster recovery plan, highlighting the risks of data loss and extended downtime due to insufficient backup mechanisms.
 

# Deliverables:
1. Vulnerability assessment report, detailing the identified weaknesses and their potential impact on the healthcare company's cloud infrastructure.
2. Data security assessment report, highlighting the risks associated with unencrypted patient data and providing recommendations for secure data storage and encryption.
3. Virtual machine vulnerability assessment report, outlining the vulnerabilities in the VMs and recommending patching and vulnerability management measures.
4. Network security assessment report, identifying vulnerabilities in network security and proposing improvements for secure access control..
5. Disaster recovery assessment report, highlighting the risks of data loss and extended downtime and proposing a comprehensive backup and disaster recovery plan.

Vulnerability assessment report, detailing the identified weaknesses and their potential impact on the healthcare company's cloud infrastructure.
Data security assessment report, highlighting the risks associated with unencrypted patient data and providing recommendations for secure data storage and encryption.
Virtual machine vulnerability assessment report, outlining the vulnerabilities in the VMs and recommending patching and vulnerability management measures.
Network security assessment report, identifying vulnerabilities in network security and proposing improvements for secure access control..
Disaster recovery assessment report, highlighting the risks of data loss and extended downtime and proposing a comprehensive backup and disaster recovery plan.
