# Google-GirlHackathon-Ideathon-Finale-Round
The repository contains my solution for the problem statement given in Finale Round of Google Girl Hackathon 2023.

**Problem Statement:** 
Fintech applications face a number of challenges, including: 
● Data security: Fintech applications handle sensitive fi nancial data, so it is important to protect this data from unauthorized access. 
● Real-time availability: Users expect to be able to access their fi nancial data and services 24/7, so it is important to ensure that fintech applications are always available. 
To address these challenges, it is important to design a network and server infrastructure that is: 
● Secure: The network and server infrastructure should be designed to protect sensitive financial data from unauthorized access. 
● Reliable: The network and server infrastructure should be designed to minimize downtime.

**Submission:**
The solution doesn’t need coding. The solution to the problem statement is only a design. The design should involve a 3-tier architecture. The 3-tier architecture means User/Client - Frontend - Backend (example: Database) The design should focus on the server and network infrastructure required to support the fintech application. The design should address the challenges mentioned as part of the problem statement. You can use architecture and flow diagrams to explain the design. The fintech application can be of your choice. Examples: gPay, stock trading app

**Solution(In Words):**
The problem statement is to address the challenges of data security and real-time availability in fi ntech applications. Fintech applications deal with sensitive fi nancial data, and thus it is crucial to protect this data from unauthorized access. Additionally, users expect to access their financial services and data at any time, necessitating a high level of availability. 

Working of this architecture is as follows :

1. The user/client layer communicates with the frontend layer using a secure protocol called Zero Trust Architecture (ZTA), ensuring that only authenticated and authorized users can access the system.
2. Techniques such as public-key cryptography, end-to-end encryption (E2E), and role-based access control (RBAC) are implemented to encrypt sensitive data both during transit and at rest.
3. Network traffic is filtered through a fi rewall (e.g., Palo Alto Networks Next-Generation Firewall or Cisco Firepower NGFW) to block unwanted or malicious traffic and allow only authorized communication.
4. Load balancing is employed to ensure real-time availability and optimal performance. Solutions like F5 BIG-IP, Citrix ADC, or NGINX Plus distribute incoming traffi c across multiple servers.
5. Authentication and authorization mechanisms such as OAuth 2.0, OpenID Connect, or SAML are implemented to verify user and server identities. This ensures that only legitimate users and authorized entities can access the system and its resources.
6. Monitoring systems like Dynatrace or New Relic are used to keep track of servers, applications, and the network. Any anomalies or issues are promptly detected, and administrators are alerted for timely resolution, maintaining the overall health and reliability of the system.
7. Redundancy is achieved through High Availability (HA) Clustering and Database Replication.
8. Backup servers are ready to take over in case of server failure or maintenance, minimizing downtime and ensuring continuous service availability. By incorporating these measures, the architecture ensures the protection of sensitive data, uninterrupted access to fi nancial services, and a reliable infrastructure for users in the fintech domain.


