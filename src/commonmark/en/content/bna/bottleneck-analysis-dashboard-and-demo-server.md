# Bottleneck Analysis Dashboard and Demo server

## Introduction to the BNA App

Bottleneck analysis (BNA) is a structured analysis of the determinants
of coverage for a wide range of interventions delivered through the
health sector, useful to supporting targeted operational planning. It is
a systematic, outcome-based approach to equitable health programming and
real-time monitoring that strengthens the health system, complementing
and building on what exists.

The BNA App is developed and maintained by the HISP Community (UiO,
HISP-Tanzania and HISP Uganda) in collaboration with UNICEF. The BNA app
is available
[here](https://play.dhis2.org/appstore/app/x7DbGPFXziA) for
download.  It is currently compatible with DHIS2 2.28 and above.   

![Standard layout of the BNA App dashboard](resources/images/image31.png)

## Advantages of the BNA App

The bottleneck analysis and planning approach contribute to existing
national and sub-national planning and monitoring cycles by offering a
strategic, rapid and systematic approach to analyzing key health systems
barriers to reaching intervention coverage targets.

This approach can help save time and increase the efficiency of
resources available by identifying where the greatest pockets of unmet
needs or poor service outcomes exist and, in those places, identifying
key bottlenecks, prioritizing what should be addressed immediately, what
should be deferred (prioritization of most effective actions) and
ensuring that resources are programmed to tackle priority bottlenecks
with evidence-informed solutions.

## Rationale for the BNA App

Health managers have competing demands resulting in limited time,
resources and training to conduct data analysis. Collecting data from
multiple sources and preparing it for analysis themselves can be a
barrier to effectively using data for planning.  While the growing trend
of building dashboards into DHIS2 is encouraging, too often the
information displayed in dashboards is a collection of related (or
sometimes unrelated) indicators rather than a well thought out process
(or framework) of how a workflow or intervention actually works.  The
bottleneck analysis app helps address these issues by automating data
gathering and presentation within DHIS2 and displaying it in a manner
that facilitates systematic analysis for programming.

Effective and timely use of DHIS2 data by stakeholders at all levels of
health system is critical for health service delivery. DHIS2 dashboards
have the potential to enhance the use of data for decision making and
planning by displaying information for managers in an accessible and
actionable manner. This visualization is made possible by using the
bottleneck analysis model integrated with the causality and tracking
actions/solutions to effect interventions.

## About demo server and the BNA App meta-data

The BNA demo server is setup to support both development, testing,
training and ensuring quality of features and functions of the demo
server. Additionally, the demo server is also setup to host both demo
data and metadata across various interventions to give chance to users
of the system to explore and learn system features and functions. The
current demo server can be accessed on :
[https://scorecard-dev.dhis2.org/demo/](https://www.google.com/url?q=https://scorecard-dev.dhis2.org/demo/&sa=D&ust=1571141929529000)

The server is hosted in the cloud and can be accessed on the
internet via a browser from anywhere as long as there is availability
of internet.


### Using DHIS2 demo server                                           

To use the BNA app demo server you will have to login into the server,
you can use the login credentials that are displayed on the login page
to login and explore the amazing features of the BNA app.

![Logging and accessing the BNA demo server ](resources/images/image1.png)

### Bottleneck & root cause analysis meta-data

The BNA app borrows its meta-data from the general DHIS2 data source and
uses this to create a data store for ease of analysis. Bottleneck
analysis metadata such as indicators and indicator groups are managed
using the DHIS2 Indicator maintenance App.

![Indicator maintenance App](resources/images/image28.png)

Complex indicators that require additional calculations are maintained
using the function maintenance app. These include but are not limited to
indicators on stock data, Human resources.

### Functional Maintenance App

The BNA App is also integrated with function maintenance App, used to
create custom indicators. Custom Indicators are indicators whose
definition and calculation cannot easily be created using the Indicator
maintenance app in the DHIS2. The app can be easily used by developers
to create custom codes to retrieve and  use indicators with complex
calculations. To use the app, find it
[here](https://www.google.com/url?q=https://play.dhis2.org/appstore/app/jofgGmsCFr7&sa=D&ust=1571141929532000)

![Function maintenance app](resources/images/image27.png)

