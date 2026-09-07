# ITSM-LAB

# ITSM Implementation Lab

A comprehensive, hands-on demonstration of IT Service Management (ITSM) system configuration, administration, and workflow automation.

---

## 📌 Overview

This repository documents the step-by-step configuration and deployment of core ITSM processes using an enterprise platform (ServiceNow). The lab covers end-to-end setups across major modules including Incident, Problem, Change Management, and the Service Catalog.

---

## 🛠️ Key Modules & Configurations

### 1. Foundational Setup & Governance
* **User & Access Management:** User creation, group mappings, and role-based access control (RBAC).
* **Security & Compliance:** Configured Access Control Lists (ACLs) and security rules to secure sensitive records and fields.

### 2. Incident Management
* **Form & Field Customization:** Configured mandatory fields, category/subcategory drop-downs with dependent values, and state choice behavior.
* **Prioritization & SLAs:** Set up automated Priority Matrices (Impact vs. Urgency) and Response/Resolution SLAs.
* **Routing & Automation:** Established assignment rules, automated notifications, post-resolution customer surveys, and auto-closure rules.

### 3. Problem Management
* **Integration Workflows:** Created field mappings to auto-populate Problem records directly from Incidents.
* **Automation:** Configured auto-assignment rules for incoming problem records and integrated Change Request generation.

### 4. Change Management
* **Risk & Approvals:** Defined Change models, approval policies, risk conditions, and blackout/maintenance schedules.
* **Change Operations:** Configured standard change templates, emergency change workflows, and attribute copy rules for streamlined processing.

### 5. Service Catalog
* **Taxonomy & Portal:** Designed user-facing catalog hierarchies.
* **Item Design:** Built catalog item templates and custom request items with fulfillment workflows.

---

## 🚀 How to Use This Lab

1. **Review Documentation:** Check module-specific configuration guides and screenshot artifacts in the repository.
2. **Replicate Setup:** Follow the configuration checklists to recreate workflows in a Developer Instance (PDI).

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
