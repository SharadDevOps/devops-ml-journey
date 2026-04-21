# Cloud Architecture Methods — Learning & Resume Tracker

> Identified from job platform skill assessment. These are high-demand skills
> recruiters filter for in Australia/NZ Cloud Architect roles.

---

## Status Key
- ✅ Already know — add to resume now
- 🔄 Partial knowledge — strengthen + add to resume
- 📚 Need to learn — add to study plan

---

## 1. Landing Zone Design ✅ → Resume Ready
**What it is:** Designing a secure, scalable multi-account/subscription Azure environment as a foundation for all workloads.

**Azure equivalent:** Azure Landing Zone (CAF — Cloud Adoption Framework)

**Already know:** Azure subscriptions, management groups, policy, blueprints

**Study resource:**
- [Azure Landing Zone Docs](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/)
- [John Savill — Azure Landing Zones](https://www.youtube.com/watch?v=eza9sOqQpUg)

**Resume line:**
> Designed and implemented Azure Landing Zones following CAF best practices, including management group hierarchy, policy governance, and network topology.

---

## 2. Event-Driven Design 🔄 → Strengthen
**What it is:** Architecture where services communicate via events (messages) rather than direct calls. Loosely coupled, async systems.

**Azure tools:** Event Grid, Event Hub, Service Bus, Azure Functions

**Study plan (Week 3–4):**
- Azure Event Grid vs Event Hub vs Service Bus — differences
- Build a simple event-driven pipeline on Azure
- [Microsoft Learn — Event-driven architecture](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/event-driven)

**Resume line:**
> Architected event-driven solutions using Azure Event Grid and Service Bus for decoupled, scalable microservices communication.

---

## 3. Microservices Design ✅ → Resume Ready
**What it is:** Breaking applications into small, independently deployable services. Each service owns its data and communicates via APIs or events.

**Azure tools:** AKS, API Management, Service Mesh (Istio), Azure Container Apps

**Resume line:**
> Designed and deployed microservices architectures on AKS with Istio service mesh, API Gateway, and independent CI/CD pipelines per service.

---

## 4. Multi-Region Design 🔄 → Strengthen
**What it is:** Deploying workloads across multiple Azure regions for high availability, disaster recovery, and low latency.

**Patterns:** Active-Active, Active-Passive, Traffic Manager, Front Door, geo-replication

**Study plan (Week 2–3):**
- Azure Traffic Manager vs Front Door vs Load Balancer
- RPO/RTO concepts, failover strategies
- [Azure Well-Architected — Reliability](https://learn.microsoft.com/en-us/azure/well-architected/reliability/)

**Resume line:**
> Designed multi-region Azure architectures with Azure Front Door and Traffic Manager achieving 99.99% availability SLA.

---

## 5. Serverless Design 🔄 → Strengthen
**What it is:** Building apps without managing servers. Auto-scaling, pay-per-use. Functions, Logic Apps, Event-driven triggers.

**Azure tools:** Azure Functions, Logic Apps, Azure Container Apps, Durable Functions

**Study plan (Week 4):**
- Azure Functions triggers, bindings, Durable Functions patterns
- When to use serverless vs containers
- [Azure Serverless community library](https://serverlessland.com/)

**Resume line:**
> Built serverless data processing pipelines using Azure Functions and Logic Apps, reducing infrastructure costs by 40%.

---

## 6. Well-Architected Reviews ✅ → Resume Ready
**What it is:** Microsoft's framework to assess and improve cloud workloads across 5 pillars — Reliability, Security, Cost Optimization, Operational Excellence, Performance Efficiency.

**Tool:** Azure Well-Architected Review assessment tool

**Resume line:**
> Conducted Azure Well-Architected Framework reviews across enterprise workloads, identifying cost savings and reliability improvements.

---

## 7. Zero Trust Architecture 📚 → Study & Add
**What it is:** Security model of "never trust, always verify." Every access request is authenticated, authorized, and continuously validated regardless of network location.

**Azure tools:** Azure AD / Entra ID, Conditional Access, PIM, Defender for Cloud, Private Endpoints

**Study plan (Month 2):**
- Zero Trust principles: verify explicitly, least privilege, assume breach
- Microsoft Zero Trust deployment guide
- [Microsoft Zero Trust Guidance](https://learn.microsoft.com/en-us/security/zero-trust/)
- [John Savill — Zero Trust](https://www.youtube.com/watch?v=tBPSXGFSFKk)

**Resume line:**
> Implemented Zero Trust security architecture using Azure Entra ID Conditional Access, PIM, and Private Endpoints across hybrid environments.

---

## Resume Section to Add

```
Cloud Architecture Methods
• Landing Zone Design (Azure CAF)    • Microservices Design (AKS + Istio)
• Well-Architected Reviews            • Multi-Region HA Design
• Event-Driven Architecture           • Serverless Design (Azure Functions)
• Zero Trust Architecture             
```

---

## Study Priority Order
1. Zero Trust Architecture (highest demand, gap in profile)
2. Multi-Region Design patterns (strengthen)
3. Event-Driven Design (strengthen + build project)
4. Serverless Design (strengthen)

---

*Last updated: April 2026*
*Source: Indeed Australia job platform skill assessment*
