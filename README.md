# SERVICENOW-DISCOVERY

# Horizontal Discovery

Discovery uses horizontal discovery as a technique to scan your network, find computers and devices, and then populate the CMDB with discovered CIs. Horizontal discovery create direct relationship between computer CIs and application CIs.

Note: Runs on Relationship is created between these two CIs. Horizontal discovery doesn't know about services and doesn't create relationship between CI based services.

Let us get a clear picture about both of the CIs in detail

List of Computer CIs:

1. Laptop
2. Printer
3. Scanner
4. Network device
5. Workstation
6. Server
7. Mobile device
8. Storage device

List of Application CIs:

1. Web application
2. Database application
3. Human Resource application
4. Enterprise Resource Planning(ERP) application
5. Customer Relationship management(CRM) application
6. Financial application
7. Security application


# Top-Down Discovery

Top-Down discovery is a type of discovery that serivce mapping uses. Top-Down discovery finds the CIs and map them which are related to services.
Service mapping first uses horizontal discovery to find the physical and virtual devices(CIs) and then It proceeds with top-down discovery to establish the relationship between CIs which are related to services.


# Phases of Discovery

When the discovery is initiated, a probe called Shazzam is launced to detect, what ports are open on the particular device in the network. The data which is returned back is analyzed by the Shazzam probe sensors to identify activities on this open port.

Note: UNIX-based OS communicates with SSH portocol over port 22.
 
