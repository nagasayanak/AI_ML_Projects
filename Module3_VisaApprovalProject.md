+-------------------------------------------------------------+
|                        Salesforce UI                        |
|       (Unified Front-End for Loan Officers & CRM)           |
+-------------------------------------------------------------+

        ↓                          ↓                          ↓

+----------------+     +---------------------+     +----------------+
| Legacy System  | ←→ | Integration Layer    | ←→ | nCino Platform |
| (Loan Types A) |     | (Routing, Sync, API) |     | (Loan Types B)|
+----------------+     +---------------------+     +----------------+

        ↑                          ↑                          ↑

+-------------------------------------------------------------+
|                Shared Services (Green Layer)                |
| CRM (Salesforce) | Document Mgmt | Reference Data | Audit Log |
+-------------------------------------------------------------+

        ↓                          ↓                          ↓

+-------------------------------------------------------------+
|         Workflow & Routing Engine (Decision Logic)          |
|  - Loan Type Rules                                           |
|  - Phase Deployment Logic                                   |
|  - Exception Handling                                        |
+-------------------------------------------------------------+
