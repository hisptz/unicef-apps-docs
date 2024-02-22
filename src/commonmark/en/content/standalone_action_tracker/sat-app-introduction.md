
# Introduction to the Standalone Action Tracker App

Action tracking is a key concept to support follow-ups on planning done by implementers at different levels in the health system. The standalone action tracker app is built on the work done on the linked action tracker app which supported and was linked with the Bottleneck Analysis (BNA) App.

The Standalone Action Tracker App is developed and maintained by the HISP Community (UiO, HISP-Tanzania, and HISP Uganda) in collaboration with UNICEF. The Standalone Action Tracker app is available [here](https://apps.dhis2.org/app/0efc14dc-bf0b-474d-8a02-82c27d891b23) for download.  It is currently compatible with DHIS2 versions 2.38 and above.  

![Figure 1.1-A: Standard layout of the Standalone Action Tracker App landing page](resources/images/image200.png){ .center width=80%}

# Advantages of the Standalone Action Tracker App

The Standalone Action Tracker app allows planners to document actions that need to be tracked and track changes of status during the implementation period. Be it in the health or other sectors, the Standalone Action Tracker App provides the flexibility for users to define the type of actions they want to track, potential status to be tracked (e.g., ongoing, canceled, finalized), and the frequency of tracking the status of the actions documented.

# Rationale for the standalone action tracker App

The initial Linked Action Tracker tracker was directly associated with the Bottleneck Analysis app to allow issues identified through the BNA app to have corresponding actions documented and tracked. The reality on the ground is not all planners use the BNA approach to identify issues. Regardless of the methodology used to find bottlenecks or issues during planning, it is crucial for planners to have a tool to allow them to document and track actions. This necessitated the need to have a standalone action tracker that allows action documentation and tracking regardless of the method used to identify the bottlenecks.

Project managers have competing demands resulting in limited time, resources, and training to conduct data analysis. Collecting data from multiple sources and preparing it for analysis themselves can be a barrier to effectively using data for planning. While the growing trend of building dashboards into DHIS2 is encouraging, too often the information displayed in dashboards is a collection of related (or sometimes unrelated) indicators rather than a well-thought-out process (or framework) of how a workflow or intervention works.  The Standalone Action Tracker app helps address these issues by automating data gathering and presentation within DHIS2 and displaying it in a manner that facilitates systematic analysis for programming and action tracking. 

Effective and timely use of data by stakeholders at all levels of the system is critical for service delivery. DHIS2 dashboards have the potential to enhance the use of data for decision-making and planning by displaying information for managers in an accessible and actionable manner. 

# Demo server and the Standalone Action Tracker App meta-data

The Standalone Action Tracker app demo server is set up to support development, testing, training, and ensuring the quality of features and functions of the demo server. Additionally, the demo server is also set up to host both demo data and metadata across various interventions to give chances to users of the system to explore and learn system features and functions. The current demo server can be accessed at: [https://hisp.apps.dhis2.org/training](https://hisp.apps.dhis2.org/training)

The server is hosted in the cloud and can be accessed on the internet via a browser from anywhere as long as there is availability of the internet. 

## Using DHIS2 demo server

To use the Standalone app demo server you will have to login into the server, you can use the login credentials that are displayed on the login page to login and explore the features of the Standalone Action Tracker app.
![Figure 1.5-A: Logging and accessing the Standalone Action Tracker App demo server](resources/images/image201.png){ .center width=80%}

## Standalone Action Tracker App meta-data

The Standalone Action Tracker app borrows its meta-data from the general DHIS2 data source and uses this to create a data store for ease of tracking and analysis. Standalone Action Tracker App metadata such as indicators and indicator groups are managed using the DHIS2 Indicator maintenance App.

![Figure 1.6.-A: Indicator maintenance App](resources/images/image202.png){ .center width=80%}