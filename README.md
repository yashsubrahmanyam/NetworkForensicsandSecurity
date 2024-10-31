# Network Forensics and Security

# Web Application Detection Building with Sumo Logic![image](https://github.com/user-attachments/assets/e5ea5abf-a7da-460b-be52-6029d6c53a6a)

The detection aims to detect Server-Side Request Forgery (SSRF) incidents. SSRFs are web vulnerabilities that an attacker can exploit to read or update internal resources. The attacker may supply or modify a URL, which the code running on our server then supplies data to (owasp.org). After selecting the URLs, the attacker may gain access to server configuration, such as AWS metadata, or connect to internal services, such as HTTP-enabled databases. 
SSRF attacks may cause chaos within an organization’s infrastructure. Many attacks result in the server connecting to internal-only services, but SSRFs may also force the server to connect to erratic external systems. 
In the typical SSRF attack against a server, the attacker triggers the application to make an HTTP request back to the server, where the application is hosted through its loopback network interface. This generally involves supplying a URL with a hostname such as 127.0.0.1, a reserved IP address pointing to the loopback adapter, or localhost, a commonly used name for the same adapter.
![image](https://github.com/user-attachments/assets/6955b675-d6d2-4e62-a62a-595b969b8ce0)
