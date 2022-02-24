# Extend SAP S/4HANA Business Processes on SAP BTP by Leveraging DevOps

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/s4hana-btp-extension-devops)](https://api.reuse.software/info/github.com/SAP-samples/s4hana-btp-extension-devops)

## Description

The main intent of this scenario is to complement an existing business process in an SAP solution – currently SAP S/4HANA with additional business process steps. This involves adding major logic and/or additional data and goes beyond simple UI changes. All of this is achieved by using DevOps tools and services provided by SAP BTP.

This application showcases:

- Building applications on SAP Business Technology Platform (BTP) using [SAP Cloud Application Programming Model(CAP)](https://cap.cloud.sap/docs/)
- Consuming events from SAP S/4HANA on premise using [SAP Event Mesh](https://help.sap.com/viewer/bf82e6b26456494cbdd197057c09979f/Cloud/en-US/df532e8735eb4322b00bfc7e42f84e8d.html)
- Utilizing SAP Workflow in SAP CAP Application.
- Consuming OData APIs from SAP S/4HANA on premise using SAP Business Technology Platform Connectivity Service
- Building a frontend for the CAP application using SAP Fiori Elements (custom fragments to show the workflow status)
- How to use the [Continous Integration and Delivery service](https://discovery-center.cloud.sap/serviceCatalog/continuous-integration-&-delivery?region=all)
- How to use [SAP Cloud Transport Management](https://discovery-center.cloud.sap/serviceCatalog/cloud-transport-management?service_plan=standard&region=all) in conjunction with the Continous Integration and Delivery service

### Implementations

#### [Basic SAP CAP Application](https://github.tools.sap/I557006/s4-hana-btp-extension-devops/tree/basic_cap_application)

Basic application utilizing SAP BTP, SAP Event Mesh, SAP Fiori Elements, SAP Continuous Integration and Delivery, SAP Cloud Transport Management.

#### [Extended SAP CAP Application](https://github.tools.sap/I557006/s4-hana-btp-extension-devops/tree/extended_cap_application)

This is an Extended Application of Basic SAP CAP Application version. Apart from all that basic verison utilizes this also utilizes SAP Workflow and also some custom enhancements in SAP Fiori Elements using Fragments.