ALX Project - Web Infrastructure Design

![Image of a simple web stack](https://ibb.co/X3hmHbf)

Task 0: Definitions and Explanations
1. Server
A server is a device, virtual device, or computer program that provides functionality for other programs or devices, known as "clients." Servers respond to requests from clients, such as serving web pages, handling email, or managing network resources.

2. Domain Name
A domain name serves to identify Internet resources, such as computers, networks, and services, with a text-based label that is easier to memorize than numerical addresses (IP addresses). Domain names provide a human-readable way to access websites or other online resources.

3. DNS Record (www.foobar.com)
The DNS record for "www" in "www.foobar.com" is a 'CNAME' (Canonical Name) record. It aliases one domain to another, often pointing the "www" subdomain to the main domain.

4. Web Server
The role of a Web Server is to store, process, and display website contents (codebase) and deliver web pages to users over the HTTP protocol. Web servers handle requests from clients and serve static content like HTML and CSS.

5. Application Server
The role of the application server is to generate dynamic contents by executing server-side code such as JSP, Ajax, PHP, etc. Application servers process business logic, handle dynamic content generation, and interact with databases.

6. Database
The role of a database is to manage data systematically and efficiently in a well-organized manner, allowing data to be easily added, accessed, updated, managed, and deleted. Databases store and retrieve data for applications.

7. Server Communication with User's Computer
The server communicates with the computer of the user requesting the website through the HTTP protocol, the foundation of data communication on the World Wide Web.

Issues
A. Single Point Of Failure (SPOF)
Issue: Having a single server containing the web server, application server, and database creates a vulnerability. If any component fails, it can bring down the entire system.
Impact: Complete system failure, leading to downtime and unavailability of services.

B. Downtime during Maintenance
Issue: Restarting the web server during maintenance results in downtime. Dependency on a single code base can prolong this period.
Impact: Users cannot access the website during maintenance, leading to a poor user experience and potential loss of traffic.

C. Scalability Issues
Issue: Lack of a load balancer and direct domain pointing can hinder scalability. The system may struggle to handle increased traffic efficiently.
Impact: Poor user experience during periods of high traffic, and the website may not accommodate a large number of users simultaneously.

Note: This README provides an overview of key concepts and issues related to the ALX Project's web infrastructure design. It serves as a reference for understanding the system architecture and potential challenges.