## 1.1 SHINE XSA Architecture
The architecture for SHINE for XSA is represented on the following image:

This application contains the following micro services:
- core-node
- core-xsjs
- user-xsjs

The XS runtime platform provides several services for managing the various container instances and their application runtime. Containers are used to manage runtime and allow isolation, resource management, and shared service injection. The XS advanced application runtime contains lightweight processes that are called over HTTP and communicate remotely with the database.

The SAP HANA Deployment Infrastructure (HDI) provides a service layer that helps to deploy database development artifacts to containers. This service layer includes a family of consistent design-time artifacts for all key HANA platform database features, which describe the target (runtime) state of SAP HANA database artifacts, for example: tables, views, or procedures. These artifacts are modeled, staged (uploaded), built, and deployed on SAP HANA.
