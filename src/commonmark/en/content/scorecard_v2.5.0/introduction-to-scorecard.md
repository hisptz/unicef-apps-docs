# Introduction to the Scorecard App

## Intended audience

This guide is intended for program implementers, who are aimed to configure the program (such as RMNCH) scorecard at national or organizational level for the rest of the users to use to measure the performance of agreed indicators at their levels. In most implementations, a program used to have one national scorecard with a list of agreed indicators, and configured at national level while other users at national and subnational levels are shared with read only access to limit them to make any changes.

In this guide, we are going to refer to Implementers and normal users in respect to the national Apart from setting up the scorecard, users with administrative privilege should share the scorecard with users or user groups. Users with privilege access can use the scorecard as normal users, with the privilege to access scorecards configured, access and download outputs, and share with others. To access as normal users, visit https://docs.google.com/document/d/1CI4A6MPr9Gr-KyuEnOFosfrdAG8Qdm1B/edit. for end user manual.

## Background of scorecard App

In public health settings such as the Ministries of Health, a scorecard offers a useful and standardized method for analysis with traffic lights color codes, combining related indicators into one table. A scorecard can give an overall view of the performance of a health program such as a vaccination program, highlighting successes, weaknesses, and areas for improvement.

In DHIS2 system, the scorecard can be created in two different ways as explained in dhis 2 website http://www.dhis2.org

- Pivot table
- Scorecard Application

This guide focuses mainly on the scorecard application. The advantage of the scorecard app is that it is tuned for advanced scorecard analysis and is developed and maintained by HISP Community, that uses vast and different use cases from different implementations to come up with solution, in contrast to the Pivot Table App that is used for basic scorecard analysis and is developed and maintained by the Dhis2 core team.
While both scorecard app and pivot table app gives the user option to download and use the scorecard offline and share it on the DHIS2 dashboard, the Scorecard app gives more advanced control and power to easily create and analyse multiple elements and dimensions of the data.

Additionally, the scorecard app gives an opportunity to cascade the analysis by including bottleneck indicators in the scorecard dashboard as well as analyses the data with a broad spectrum of visualization tools, such as pivot table, charts and maps.
This version of the scorecard is aimed to address limitations encountered in the scorecard version 2.4.1 by including functionalities such as ability of accommodating national and district targets for the same indicator, ability to sort the indicator while maintaining the parent organization unit, ability to change the layout of the scorecards listing, ability to filter the scorecard per specific facility type, ownership and periods, ranking the good or poor performers etc. The revised scorecard app has considered users’ feedback and new use cases over five years of the scorecard Implementation.

## Users of the Scorecard

The Scorecard app can be used by any one with access to the DHIS2 system. Scorecard creation can be done by anyone with access to DHIS2. If someone creates a scorecard, it will only be accessed by the creator/owner unless sharing access to other users within the DHIS2 system. Most organizations and countries prefer to have one scorecard for each of the particular programs, where a list of indicators with their cut-off points are selected and approved for the particular program’s scorecard such as RMNCH. Then users from the program at organizational or national levels are tasked to create a scorecard and limit its access to read only to other users so that they can only visualize for evaluation of the program performance.

In this perspective, the one who creates and maintains a program scorecard are referred to as implementers, while any other users with read only access to the program scorecard are referred to as normal users.

![](resources/images/important.png)**Important**: In this guide, an Implementer is referred to as the user who creates and maintains a particular scorecard, and gives a view only access to the rest of the users; while any other users who can only view the particular program scorecard without ability of editing it are referred to as normal users.
