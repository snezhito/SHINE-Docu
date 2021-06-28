## Overview of SHINE for SAP HANA Extended Application Services Advanced Model (SHINE for XSA)
SAP HANA Interactive Education, or SHINE, is a demo application that makes it easy to learn how to build applications on SAP HANA Extended Application Services Advanced Model. This demo application is delivered as a package that contains sample data and design-time developer objects for the applications database tables, views, OData and user interface.

The application consists of the following packages:

|Package|Description|
| :- | :- |
|core-db|This package contains the SAP HANA Deployment Infrastructure (HDI) artifacts and the database artifacts required to create the tables and other database artifacts (for example, hdbcds, hdbsequence, and so on) for Data Generator, Purchase Order Worklist and Sales Dashboard and Spatial Scenario.|
|user-db|This package contains the SAP HANA Deployment Infrastructure (HDI) artifacts and the database artifacts required to create the tables and other database artifacts (for example, hdbcds, hdbsequence, and so on) for User CRUD and Job Scheduling.|
|core-node|This package has the *Node.js*-based server-side implementation of Data Generator and job scheduler.|
|core-xsjs|This package has the *xsjs*-based server-side implementation of Purchase Order Worklist, Sales Dashboard and Spatial scenario.|
|user-xsjs|This package contains the *xsjs*-based server-side implementation for User creation, User CRUD.|
|Web|This package contains the user interface for the SHINE Launchpad, Data Generator, Purchase Order Worklist Job Scheduler, Spatial scenario and User CRUD applications implemented in SAP UI5.|
|site-content|This package contains site configuration files required for Fiori Launchpad.|
|site-web|This package contains the user interface for the SHINE Fiori Launchpad, Data Generator, Purchase Order Worklist, Job Scheduler, Sales dashboard, Spatial and User CRUD implemented in SAP UI5.|

