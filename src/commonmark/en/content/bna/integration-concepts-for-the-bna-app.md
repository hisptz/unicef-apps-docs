# Integration Concepts for the BNA App.

DHIS2 is an open source platform and its implementers are active
contributors to interoperability initiatives, such as openHIE. The DHIS2
application database is designed with flexibility in mind. Data
structures such as data elements, organisation units, forms and user
roles can be defined completely freely through the application user
interface.

When implementing BNA it is important to review and identify data
sources for selected indicators. Some common sources in MoH instances
include, DHIS2, openMRS, iHRIS, Supply chain and logistics systems,
inventory etc. Other data sources may include baseline studies and
surveys. For example, the Uganda Demographic Health Survey, Population
Census reports, etc.   These sources will quite often dedicate the mode
for data integration.  

## Integration vs Interoperability

Detailed information on DHIS2 Interoperability and
Integration can be found [here](https://docs.dhis2.org/master/en/implementer/html/dhis2_implementation_guide_full.html)

## Steps for a successful data integration

The purpose of this step-by-step BNA Implementation Guide is to provide
a methodology for implementers to create and support a DHIS2 integration
scenario. The guide is based on the best practices and lessons learned.
The guide advocates for a country driven, iterative, and agile approach
that begins with collecting user stories and functional requirements.

The guide is intended as a framework that can be adapted to the specific
context of each country. The content describes specific examples for
each step detailing user stories, data specifications, job aids and
checklists to guide the use of the reference implementation software.
The basic structure, including the 6 steps, are based on the [OpenHIE
implementation
methodology](https://wiki.ohie.org/display/documents/OpenHIE%2BPlanning%2Band%2BImplementation%2BGuides):

Step 1 : Identify stakeholders and motivations for improved facility
Data

Step 2 : Document bottleneck specifications and user Stories

  - Collect existing metadata
  - Document data specifications
  - Document user stories

Step 3 : Set up Initial Instance

  - Implement the specifications
  - Identify and prioritize incomplete user stories

Step 4 : Identify Gaps & Iterative Development via User Testing

  - Agile and iterative development
  - User testing
  - Collect, reconcile and upload data

Step 5 : Scaling the BNA Implementation

  - Confirm user roles and responsibilities
  - User training
  - Critical integrations

Step 6 : Provide Ongoing Support

During the implementation phase a temporary support structure should be
available, afterwards a permanent support structure needs to be set-up.
The main challenge is to have clear responsibilities for example
management of metadata.

In addition to these steps related to interoperability, it is also
interesting to reference back to some of the general DHIS2
implementation experiences and best practices given in the sections on
[Recommendations for National HIS Implementations](https://docs.dhis2.org/master/en/implementer/html/dhis2_implementation_guide_full.html) and
[Setting Up a New Database](https://docs.dhis2.org/master/en/implementer/html/dhis2_implementation_guide_full.html).
A typical DHIS2 implementation approach which is also vital for
interoperability projects is a participatory approach.

