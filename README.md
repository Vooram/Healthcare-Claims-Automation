# Healthcare-Claims-Automation

Project Link:

https://apps.powerapps.com/play/e/default-7f8259c4-c491-47f5-a5e5-a99f5326b976/a/2a908ce9-79ab-43ee-92a9-185452f14a39?tenantId=7f8259c4-c491-47f5-a5e5-a99f5326b976&hint=a03362b4-dfc4-4e9d-a2d9-0bec20a52f4a&sourcetime=1771478674963



# 🏥 Healthcare Claims Processing Automation (Power Platform)

## Overview
This project demonstrates an end-to-end automation solution for healthcare claims processing using Microsoft Power Platform (Power Apps, Power Automate, and Power BI).

The solution reduces manual effort, improves processing efficiency, and enables real-time visibility into claim approvals and performance metrics.

---

## Problem Statement
Healthcare claims processing is often manual, time-consuming, and error-prone. Key challenges include:
- Manual data entry errors
- Delays in approval workflows
- Lack of real-time tracking
- Inefficient workload distribution

---

## Solution
Designed a low-code automation solution using Microsoft Power Platform:

- 📱 **Power Apps (Canvas App)** for claim submission
- ⚙️ **Power Automate** for workflow automation & approval routing
- 📊 **Power BI Dashboard** for monitoring KPIs and performance

---

## Architecture

User → Power Apps → Data Source (SharePoint/Dataverse) → Power Automate → Approval Workflow → Power BI Dashboard

---

## Tools & Technologies
- Microsoft Power Apps (Canvas)
- Power Automate (Cloud Flows)
- Power BI (DAX, Data Modeling)
- SharePoint / Dataverse (Data Storage)
- Excel (Data Validation)
- SQL Concepts (Relational Modeling)

---

## Power Apps – Claim Submission
- Designed user-friendly form interface
- Captures:
  - Patient details
  - Claim amount
  - Claim type
- Implemented validation rules:
  - Mandatory fields
  - Numeric validation
- Used formulas:
  - `If()`
  - `Patch()`
  - `Navigate()`

---

## Power Automate – Workflow Automation
- Trigger: New claim submission
- Logic:
  - If claim amount > threshold → Manager approval
  - Else → Auto-approval
- Features:
  - Conditional branching
  - Email notifications
  - Status updates
- Improved processing efficiency and reduced manual intervention

---

## Power BI Dashboard
Built interactive dashboards to track:

- Claim Processing Time
- Approval Rate
- Claim Volume Trends
- Workload Distribution

### Key Features:
- Star Schema Data Model
- DAX Measures:
  - Total Claims
  - Approval Rate
  - Average Processing Time
- Data visualization for decision-making

---

## Data Modeling
Implemented relational design:
- Unique Claim ID (Primary Key)
- Structured tables for:
  - Claims
  - Users
  - Approval Status

Ensured:
- Data integrity
- Scalability
- Efficient querying

---

##  Testing & Validation
- Input validation rules
- Workflow testing for different scenarios
- Verified approval routing logic
- Ensured accurate dashboard metrics

---

## Documentation
- Process flow diagram
- Workflow logic documentation
- Automation impact summary

---

## Business Impact
- Reduced manual processing effort
- Improved approval turnaround time
- Enhanced visibility into operations
- Minimized data entry errors

---

## Future Enhancements
- AI Builder for document processing
- Fraud detection using ML models
- Integration with external healthcare systems
- Advanced analytics using Azure/Synapse

---

## Author
**Mithun Kumar Reddy Voora**  
Stamford, CT  
📧 mkreddyv605@gmail.com  

---

## Key Learning Outcomes
- End-to-end automation design using Power Platform
- Workflow logic & conditional automation
- Data modeling & dashboard development
- Business process optimization
