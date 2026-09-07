# My Notes — Idowu Abdulganeey Olawale

---

## Key Concepts I Learned

* Azure VPN Gateway provides secure connectivity between Azure virtual networks and on-premises environments, supporting remote and hybrid network scenarios.

* VPN Gateway security can be strengthened through appropriate authentication, encryption, and configuration of secure tunnels.

* Microsoft Entra Private Access provides identity-based access to private applications without requiring users to have broad network-level VPN access.

* **Zero Trust connectivity** focuses on providing access to specific applications based on user identity and authorization rather than automatically trusting the entire network.

* **Private Endpoints** allow Azure PaaS resources to be accessed through private IP addresses within a virtual network, reducing reliance on public network access.

* **Azure Private Link** enables private connectivity to Azure services and can help keep application traffic within the Microsoft Azure network.

* **Azure Policy and Microsoft Defender for Cloud** can help organizations enforce and monitor the use of private connectivity across their Azure environment.

---

## Lab / Hands-On Work

### What I did

I followed the instructor's demonstration of Modules 3 and 4 and observed how Azure provides secure connectivity for remote users, hybrid environments, and Azure PaaS services.

The class demonstration covered:

* Reviewing Azure VPN Gateway and its role in remote and hybrid connectivity.
* Understanding how VPN connections can provide access to Azure resources.
* Exploring Microsoft Entra Private Access as an identity-aware alternative to broad VPN access.
* Understanding how Zero Trust principles can be applied to private application access.
* Reviewing how Private Endpoints provide private access to Azure services.
* Exploring Azure Private Link and how it removes the need for public connectivity to supported services.
* Looking at how Azure Policy and Defender for Cloud can support private connectivity requirements at scale.

### What happened / Result

Although I did not perform the configurations myself, the demonstration helped me understand the difference between **network-level connectivity through VPNs** and **application-level access through Microsoft Entra Private Access**.

I also gained a clearer understanding of how Private Endpoints and Azure Private Link can be used to prevent Azure PaaS resources from being directly exposed through public network access.

### Challenges I faced

The main challenge was understanding the practical difference between **VPN Gateway and Microsoft Entra Private Access**, particularly because both can provide access to private resources but operate at different levels.

I also needed to understand how Private Endpoints and Private Link change the way Azure PaaS services are accessed compared with public endpoints.

---

## My Takeaways

My main takeaway from these modules was the shift from simply securing network connectivity to providing **more targeted and identity-aware access**.

I found the concept of **Microsoft Entra Private Access and Zero Trust** particularly useful because users can be given access to the applications they need without necessarily giving them broad access to an entire private network.

I also learned that Private Endpoints can significantly reduce the public exposure of Azure PaaS services by providing private connectivity through Azure networking.

---

## Questions I Still Have

* In what situations would an organization choose **Microsoft Entra Private Access instead of a traditional VPN Gateway**?

* What are the main considerations when migrating existing Azure PaaS services from public endpoints to **Private Endpoints**?

---

## Resources I Found Useful

* Microsoft Learn — Implement Network Security Controls in Azure
  https://learn.microsoft.com/en-us/training/paths/implement-network-security-controls-azure/

* Microsoft Learn — Azure VPN Gateway
  https://learn.microsoft.com/en-us/azure/vpn-gateway/vpn-gateway-about-vpngateways

* Microsoft Learn — Microsoft Entra Private Access
  https://learn.microsoft.com/en-us/entra/global-secure-access/concept-private-access

* Microsoft Learn — Azure Private Link
  https://learn.microsoft.com/en-us/azure/private-link/private-link-overview

---

*Submitted by: Idowu Abdulganeey Olawale · Cyberwalls*
