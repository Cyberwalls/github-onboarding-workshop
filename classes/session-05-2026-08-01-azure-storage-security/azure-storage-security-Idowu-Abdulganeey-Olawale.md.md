# My Notes — Idowu Abdulganeey Olawale

---

## Key Concepts I Learned

* Azure Storage security settings can be configured at the storage-account level to control how data is accessed and transmitted.

* Microsoft Entra ID and RBAC can be used to assign specific permissions to users, applications, and managed identities without relying on shared credentials.

* Shared Access Signatures (SAS) provide temporary and limited access to specific storage resources by defining permissions, resources, and expiration times.

* Azure Policy can be used to enforce required storage configurations across an Azure environment.

* Storage network access can be restricted using firewalls, IP rules, virtual network rules, and trusted service configurations.

* Private endpoints allow Azure Storage resources to be accessed privately through an Azure Virtual Network rather than through a public endpoint.

* Microsoft Defender for Storage provides monitoring and threat detection capabilities for storage workloads, including detection of potentially malicious files and suspicious activity.

---

## Lab / Hands-On Work

### What I did

I followed along with the instructor's demonstration of Azure Storage security features. I observed how different controls can be configured and used to protect Azure Storage resources.

The class demonstration covered:

* Using Microsoft Entra ID and RBAC to manage access.
* Understanding how SAS can provide delegated access to storage resources.
* Applying Azure Policy to enforce storage requirements.
* Configuring network restrictions for storage accounts.
* Demonstrating private endpoint connectivity.
* Reviewing Microsoft Defender for Storage and its threat detection capabilities.

### What happened / Result

By observing the demonstration, I gained a practical understanding of how the different Azure Storage security features are configured and how they address different requirements.

Although I did not perform the configurations myself, seeing the process helped me connect the concepts from the Microsoft Learn modules with their implementation in an Azure environment.

### Challenges I faced

The main challenge was understanding the practical differences between the available access and connectivity options, particularly **RBAC, managed identities, SAS, firewall rules, and private endpoints**.

---

## My Takeaways

One of my main takeaways was that Azure Storage provides different controls for different use cases. The appropriate approach depends on factors such as the type of workload, how access is required, and whether the resource needs public or private connectivity.

I also gained a better understanding of how **Microsoft Defender for Storage** complements access and network controls by providing visibility into potentially suspicious activity.

---

## Questions I Still Have

* When would SAS be preferable to Microsoft Entra ID and RBAC in a production environment?

* What are the main considerations when deciding whether a storage account should use a private endpoint?

---

## Resources I Found Useful

* Microsoft Learn — Implement Security for Azure Storage
  https://learn.microsoft.com/en-us/training/paths/implement-azure-storage-security/

* Microsoft Learn — Azure Storage Security
  https://learn.microsoft.com/en-us/azure/storage/common/storage-security

* Microsoft Learn — Microsoft Defender for Storage
  https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-storage-introduction

* Microsoft Learn — Azure Private Endpoints
  https://learn.microsoft.com/en-us/azure/private-link/private-endpoint-overview

---

*Submitted by: Idowu Abdulganeey Olawale · Cyberwalls*
