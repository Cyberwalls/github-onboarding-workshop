# My Notes — Idowu Abdulganeey Olawale

---

## Key Concepts I Learned

* Microsoft Entra ID authentication can be used with Azure SQL Database and SQL Managed Instance to provide identity-based database access. Managed identities can also be used by applications and AI workloads without storing database credentials.

* Private endpoints and firewall rules can be used to control how Azure SQL resources are reached and reduce unnecessary network exposure.

* Transparent Data Encryption (TDE protects data stored in the database by encrypting data at rest. Customer-managed keys can also be used where additional control over encryption keys is required.

* Dynamic Data Masking helps hide sensitive information from users who do not need to see the actual values, while **Row-Level Security** controls which rows a user is allowed to access.

* Azure SQL auditing records database activities and can send audit information to destinations such as Azure Monitor, Event Hubs, and immutable storage for compliance and investigation purposes.

* Microsoft Defender for Databases can identify threats such as SQL injection, unusual query activity, and database vulnerabilities.

* Vulnerability assessment can be used to identify security weaknesses and establish security baselines for Azure SQL environments.

---

## Lab / Hands-On Work

### What I did

I followed the instructor's demonstration of Azure SQL security configurations and observed how different security features are implemented.

The class demonstration covered:

* Configuring Microsoft Entra ID authentication and managed identity access.
* Using private endpoints and firewall rules for network isolation.
* Applying encryption to protect database information.
* Demonstrating Dynamic Data Masking and Row-Level Security.
* Configuring auditing and reviewing available audit destinations.
* Enabling Microsoft Defender for Databases.
* Reviewing vulnerability assessment and security alert capabilities.

### What happened / Result

Although I did not perform the configurations myself, the demonstration helped me understand how the different Azure SQL security features are applied in a real Azure environment.

It also helped me connect the concepts from the Microsoft Learn modules with practical configurations, particularly around **database authentication, network isolation, data protection, auditing, and threat detection**.

### Challenges I faced

The main challenge was understanding how the different database protection features address different requirements.

In particular, I needed to distinguish between **encryption, data masking, Row-Level Security, auditing, and Defender for Databases**, since each serves a different purpose within an Azure SQL environment.

---

## My Takeaways

One of my biggest takeaways was that protecting a database involves more than simply controlling who can connect to it.

Azure SQL provides separate capabilities for **authentication, network connectivity, data protection, activity monitoring, and threat detection**, allowing organizations to address different security and compliance requirements.

I also found the use of **managed identities for applications and AI workloads** particularly interesting because it reduces the need to manage database credentials within applications.

---

## Questions I Still Have

* In what situations would an organization choose **customer-managed keys** instead of the default encryption options for Azure SQL?

* How should vulnerability assessment findings be prioritized when managing a large number of Azure SQL databases?

---

## Resources I Found Useful

* Microsoft Learn — Implement Security for Azure SQL Databases
  https://learn.microsoft.com/en-us/training/paths/implement-azure-sql-database-security/

* Microsoft Learn — Configure Platform-Level Security for Azure SQL
  https://learn.microsoft.com/en-us/training/modules/configure-azure-sql-platform-security/

* Microsoft Learn — Implement Microsoft Defender for Databases
  https://learn.microsoft.com/en-us/training/modules/implement-defender-databases/

* Microsoft Learn — Secure a Database in Azure SQL Database
  https://learn.microsoft.com/en-us/azure/azure-sql/database/secure-database-tutorial

---

*Submitted by: Idowu Abdulganeey Olawale · Cyberwalls*
