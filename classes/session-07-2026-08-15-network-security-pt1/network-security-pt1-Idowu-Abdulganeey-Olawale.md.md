# My Notes — Idowu Abdulganeey Olawale

---

## Key Concepts I Learned

* Network Security Groups (NSGs) can control inbound and outbound traffic to Azure resources using rules based on source, destination, port, and protocol.

* Application Security Groups (ASGs) allow resources with similar application roles to be grouped together, making it easier to apply network security rules without managing individual IP addresses.

* Azure Virtual Network security involves controlling communication between resources and defining which traffic should be allowed or denied.

* Network security rules are evaluated based on their priority, with higher-priority rules taking precedence over lower-priority rules.

* Service tags can simplify NSG rules by representing groups of Azure services instead of requiring individual IP addresses.

* Network security controls can be used to restrict unnecessary communication and reduce the attack surface of workloads hosted within an Azure Virtual Network.

---

## Lab / Hands-On Work

### What I did

I followed the instructor's demonstration of the first two modules and observed how network security controls are configured within Azure.

The demonstration covered:

* Creating and configuring Network Security Groups.
* Creating inbound and outbound security rules.
* Controlling traffic based on IP addresses, ports, and protocols.
* Understanding how rule priorities affect traffic.
* Using Application Security Groups to organize resources.
* Reviewing service tags and how they can simplify security rules.

### What happened / Result

Although I did not perform the configurations myself, the demonstration helped me understand how NSGs are used to control communication between Azure resources.

I was also able to see how **ASGs and service tags** can make network security rules easier to manage, particularly as an Azure environment grows.

### Challenges I faced

The main challenge was understanding how **NSG rules, priorities, ASGs, and service tags** work together when determining whether network traffic is allowed or denied.

---

## My Takeaways

My main takeaway from these modules was the importance of being intentional about **which network traffic is allowed between Azure resources**.

I also learned that using tools such as **Application Security Groups and service tags** can make network security configurations more organized and easier to maintain compared with creating individual rules for every resource or IP address.

---

## Questions I Still Have

* How should NSG rules be structured in a large Azure environment to avoid having too many complex rules?

* What are the best practices for managing NSGs when applications have multiple tiers, such as web, application, and database servers?

---

## Resources I Found Useful

* Microsoft Learn — Implement Network Security Controls on Azure
  https://learn.microsoft.com/en-us/training/paths/implement-network-security-controls-azure/

* Microsoft Learn — Network Security Groups
  https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview

---

*Submitted by: Idowu Abdulganeey Olawale · Cyberwalls*
