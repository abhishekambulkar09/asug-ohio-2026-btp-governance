# Governing SAP BTP Landscapes at Enterprise Scale
### ASUG Ohio Chapter 2026 — Session Resources
**Speaker:** Abhishek Ambulkar | BTP Solutions Architect  
**Session:** April 2026 | Subaccount governance, identity management, 
CI/CD pipelines, and the BTP lifecycle model

---

## Platform Architecture & Reference

### SAP Architecture Center
Official SAP reference architectures across integration, 
data, AI, and operations — 30+ blueprints, publicly accessible.  
→ [architecture.learning.sap.com](https://architecture.learning.sap.com)

### SAP BTP Reference Architecture GitHub (Official SAP Repo)
Downloadable diagram files, draw.io and PowerPoint templates.  
→ [github.com/SAP/sap-btp-reference-architectures](https://github.com/SAP/sap-btp-reference-architectures)

### SAP BTP Guidance Framework
Central access point for BTP architects — governance patterns, 
best practices, and service selection guidance.  
→ [discovery-center.cloud.sap/guidance-framework](https://discovery-center.cloud.sap/guidance-framework)

### SAP Discovery Center — Mission Catalog
Hands-on guided implementation projects by BTP service area.  
→ [discovery-center.cloud.sap/missionCatalog](https://discovery-center.cloud.sap/missionCatalog)

### SAP Discovery Center — Reference Architecture Catalog
Maps reference architectures to related missions and services.  
→ [discovery-center.cloud.sap/refArchCatalog](https://discovery-center.cloud.sap/refArchCatalog)

---

## Subaccount & Identity Governance

### Trust and Federation with Identity Providers (SAP Help)
Official BTP documentation for connecting subaccounts to 
identity providers via SAP IAS.  
→ [help.sap.com — Trust and Federation](https://help.sap.com/docs/btp/sap-business-technology-platform/trust-and-federation-with-identity-providers)

### Configure Corporate IdP Federation (SAP Cloud Identity Services)
Step-by-step configuration guide for federating your corporate 
IdP through SAP IAS.  
→ [help.sap.com — Corporate IdP Federation](https://help.sap.com/docs/cloud-identity-services/cloud-identity-services/corp-idp-configure-identity-federation)

### SAP Cloud Identity Services — SCIM Provisioning
Automated user lifecycle management: provisioning and 
deprovisioning via SCIM from your corporate directory.  
→ [help.sap.com — Cloud Identity Services](https://help.sap.com/docs/cloud-identity-services)

### BTP Audit Log API — Subaccount Retrieval
Free-tier API for retrieving platform audit events: service key 
creation, role assignments, trust configuration changes.  
Core tool for actor-attributed governance monitoring.  
→ [help.sap.com — Audit Log Retrieval API](https://help.sap.com/docs/btp/sap-business-technology-platform/audit-log-retrieval-api-usage-for-subaccounts-in-cloud-foundry-environment)

### BTP Audit Log Viewer (Cloud Foundry)
UI-based viewer for audit logs within the BTP Cockpit.  
→ [help.sap.com — Audit Log Viewer](https://help.sap.com/docs/btp/sap-business-technology-platform/audit-log-viewer-for-cloud-foundry-environment)

---

## CI/CD & Transport

### SAP Continuous Integration and Delivery Service
Native BTP CI/CD service with pre-built pipelines for CAP, 
SAPUI5, and MTA workloads. No infrastructure to manage.  
→ [help.sap.com — SAP CI/CD Service](https://help.sap.com/docs/continuous-integration-and-delivery/sap-continuous-integration-and-delivery/what-is-sap-continuous-integration-and-delivery)

### SAP Cloud Transport Management Service (cTMS)
Controlled, auditable transport of BTP artifacts across 
subaccounts and environments. Free tier available.  
→ [help.sap.com — cTMS](https://help.sap.com/docs/cloud-transport-management/sap-cloud-transport-management/what-is-sap-cloud-transport-management)

### cTMS Discovery Center Service Page
Free tier details, pricing, and service plans.  
→ [discovery-center.cloud.sap — Cloud Transport Management](https://discovery-center.cloud.sap/serviceCatalog/cloud-transport-management)

### cTMS Community FAQ
Practical Q&A on supported content types, global account 
transport, iFlow-level transport, and licensing.  
→ [community.sap.com — cTMS FAQ](https://pages.community.sap.com/topics/devops/cloud-transport-management-faq)

### DevOps with SAP BTP — Architecture Reference
How SAP CI/CD, cTMS, and Cloud ALM connect into an 
end-to-end DevOps pipeline.  
→ [architecture.learning.sap.com — DevOps Reference Architecture](https://architecture.learning.sap.com/docs/ref-arch/1c5706feb5)

### Project Piper (Open Source SAP CI/CD)
Open-source CI/CD framework underlying SAP's pipelines. 
Useful for Jenkins and GitHub Actions integrations.  
→ [sap.github.io/jenkins-library](https://sap.github.io/jenkins-library)

---

## Governance Monitoring & Alerting

### SAP Automation Pilot — Official Documentation
Event-driven operations automation on BTP. Wire it to 
the Audit Log API for actor-attributed governance monitoring.  
→ [help.sap.com — SAP Automation Pilot](https://help.sap.com/docs/automation-pilot/automation-pilot/what-is-sap-automation-pilot)

### SAP Automation Pilot — Community Hub & Roadmap
Tutorials, upcoming features, and community content.  
→ [community.sap.com — Automation Pilot](https://pages.community.sap.com/topics/automation-pilot)

### SAP Automation Pilot — Example Commands (GitHub)
Ready-to-import catalog files for common automation scenarios.  
→ [github.com/SAP-samples/automation-pilot-examples](https://github.com/SAP-samples/automation-pilot-examples)

### SAP Alert Notification Service — Official Documentation
Free-tier event alerting for BTP services. Set up before 
you need it.  
→ [help.sap.com — Alert Notification Service](https://help.sap.com/docs/alert-notification/sap-alert-notification-for-sap-btp/what-is-sap-alert-notification-service-for-sap-btp)

### Alert Notification + Automation Pilot Integration
How to wire Alert Notification to trigger Automation Pilot 
commands for automated remediation.  
→ [help.sap.com — ANS + Automation Pilot](https://help.sap.com/docs/alert-notification/sap-alert-notification-for-sap-btp/integrating-with-sap-automation-pilot)

---

## ABAP Cloud & Clean Core

### ABAP Cloud FAQ (SAP Community)
Comprehensive practitioner FAQ: ATC check setup, clean core 
levels A–D, released APIs, and transformation options.  
→ [community.sap.com — ABAP Cloud FAQ](https://pages.community.sap.com/topics/abap/abap-cloud-faq)

### ABAP Extensibility Guide — August 2025 Update
Official SAP blog introducing the clean core level concept 
and updated extensibility guidelines.  
→ [community.sap.com — ABAP Extensibility Guide](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-extensibility-guide-clean-core-for-sap-s-4hana-cloud-august-2025/ba-p/14175399)

---

## ASUG Community

### ASUG Community Alliances Hub
Entry point for all ASUG BTP programming — task forces, 
influence councils, and peer conversations.  
→ [asug.com — Community Alliances](https://www.asug.com/connect/asug-community-alliances)


---

## Session Materials

| File | Description |
|---|---|
| Handout | Coming after the session |
| Q&A follow-ups | Will be added here post-session |

---

*Last updated: April 2026*  
*Questions from the session? Open an issue in this repo 
or connect on [SAP Community](https://community.sap.com).*
