**title:** The Digital Trust Imperative: The Need for Multicloud 
**source:** K. Brian Kelley, ISACA Journal, 1 March 2026 
**description:** An analysis of multicloud and multiregion architectures as strategic business decisions for maintaining digital trust, availability, and cost-efficiency in the wake of major 2025 cloud outages. 
**tags:** #CloudComputing #DigitalTrust #Multicloud #BusinessContinuity #CyberSecurity

---

## Summary

In the aftermath of significant cloud outages in late 2025, organizations are increasingly questioning the necessity of multicloud deployments. This article argues that moving to a multicloud or multiregion architecture is not merely a technical choice but a calculated business decision. The primary drivers are the cost of downtime—which includes both immediate financial loss and long-term reputational damage—and the pursuit of "digital trust." While major Cloud Service Providers (CSPs) offer multiregion options for mission-critical workloads, these come at a high price and may still be vulnerable to "central control plane" failures that can trigger global outages.

The author distinguishes between using multicloud for resiliency versus using it for cost savings. While the former is often only justifiable for organizations with extreme availability requirements (e.g., 99.99%), the latter is a "shopping around" strategy to leverage the best pricing for specific services across different providers. Ultimately, the article emphasizes that no architecture is immune to failure, making robust and tested business continuity plans essential regardless of the underlying cloud strategy.

## Key Takeaways

- **Business vs. Technical Decision:** Architecture choices should be based on the cost of downtime relative to the cost of the redundancy solution.
    
- **The Central Control Plane Problem:** Multiregion deployments within a single CSP can still fail if core global services (like DNS or identity management) suffer a cascade failure.
    
- **Cost of Digital Trust:** Beyond lost transactions, outages impact long-term customer relationships and brand reputation, which are harder to quantify but vital to include in risk assessments.
    
- **Multiregion Constraints:** CSPs typically recommend multiregion architecture only for mission-critical workloads requiring 99.99% availability or higher due to significant cost increases.
    
- **Multicloud for Cost Optimization:** Similar to comparison shopping at grocery stores, organizations can use multiple CSPs to select the best-priced services for specific tasks (e.g., AWS for infrastructure, Google Cloud for analytics).
    
- **Reputation Shielding:** Organizations may suffer less reputational damage if an outage is clearly the fault of a major provider (like the 2025 AWS or 2024 CrowdStrike events) rather than their own internal failure.
    
- **Business Continuity is Mandatory:** Technical resilience does not replace the need for a business continuity plan that accounts for total outages and manual workarounds.
    

## Notable Quotes

> "If the solution to mitigate a security risk costs more than the asset being protected, then it’s a bad business decision to implement the solution."

> "Assuming the network is reliable is the first fallacy of distributed computing. If one expects that because of a resilient architecture there will never be an outage, then one has committed that fallacy."

> "While a multicloud strategy might not make sense from an availability/resiliency perspective, it is a serious strategy for being competitive in a digital trust ecosystem."