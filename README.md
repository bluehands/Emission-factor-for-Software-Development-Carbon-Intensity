# Emission factor for *Software Development Carbon Intensity*

## Abstract

This document specifies an emission factor to determine the carbon intensity of software development. The total CO<sub>2</sub>e emissions for a given customer or project are calculated by multiplying the number of working hours with this factor.

> CO<sub>2</sub>e<sub>Customer</sub> = EF<sub>SD</sub> * h<sub>Customer</sub>

This specification is mainly for software development provider and consulting companies. Software development companies with a mixed business model (ISV and Consulting) may adapt this specification and assign the emissions and working hours to business units.

## Emission factor EF<sub>SD</sub>

The software development emission factor is calculated as the total CO<sub>2</sub>e emissions of the company divided by the total number of software development working hours.

> EF<sub>SD</sub> = CO<sub>2</sub>e<sub>Company</sub> / h<sub>Software development</sub>

## Calculating the total CO<sub>2</sub>e emissions

The total CO<sub>2</sub>e emissions are calculated as described by the *GHG-Protocol* and MUST include *Scope1*, *Scope2* and *Scope3* emissions. The following Scope3 emission sources MUST be included:

* Employee commuting or Remote work
* Business travel
* Purchased goods and services needed for the software development business, including:
  * Computing hardware like server, switches, etc.
  * Office & Development hardware like Desktops, Workstations, Personal computer, Notebook, Monitor, etc.
  * Cloud computing & managed service provider like Azure, AWS, etc.
  * Cloud services & SaaS like Office 356, CRM, Zoom, etc.
  * Cloud DevOps services like Azure DevOps, GitHub, GitLab, Jira, etc.
* Leased Assets as much as possible

The Scope2 emissions MUST be calculated location based and NOT market based. That means that all power consumptions are calculated with the local power grid intensity (Average or time based).

Electricity which is directly produced by solar or wind and consumed is NOT counted. Only electricity that is purchased directly must be included in the calculation.

The methodology of calculating the total CO<sub>2</sub>e emissions MUST be documented.

## Calculating total working hours

For this emission factor only working hours are considered which are directly involved in the software development process. Examples are Coding, Scrum meetings (daily, planning, refinement, review), Product owner, etc. All time efforts which may billed can be included. NOT included is Accounting, Marketing, Operating, HR, trainings, self-organization, etc.

The software development efforts must not be necessary billed. Open-Source projects, tools and spikes are also considered.  

## Contribution

Every contribution is warmly welcome.

