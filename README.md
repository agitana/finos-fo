[![FINOS - Incubating](https://cdn.rawgit.com/finos/contrib-toolbox/master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# FINOS Financial Objects project

Welcome to the Financial Objects project, led by Goldman Sachs and hosted by FINOS, The Fintech Open Source Foundation. 

All Financial Objects collaboration activities, including meeting minutes, are hosted on this [Financial Objects GitHub repository](https://github.com/finos/finos-fo), and in this [GitLab project](https://gitlab.legend.finos.org/legend-pilot/cdm). Activities prior to July 2020 can be found in the [Financial Objects project archive](https://fo.finos.org). 

For more information about FINOS project materials and communication, please review the [FINOS Governance](https://github.com/finos/community/blob/master/governance/Collaborative-Principles.md).

### Background 

The Financial Objects project was led by Johan Sandersson (Factset) and Hammad Akbar (Citi) until July 2020, when they expressed their intention to step down as project leads. See this GitHub issue _[Choose new project leads for FO](https://github.com/finos/finos-fo/issues/36)_ for context.

Between July 2020 and February 2021, the FINOS Community engaged with a [Request for Comment on the Future of the Financial Objects project](https://github.com/finos/finos-fo/issues/38), and in February 2021, Ffion Acland from Goldman Sachs [stepped forward](https://groups.google.com/a/finos.org/g/community/c/7U3uS0GJ0QQ) to lead the Financial Objects project. Following a ten day period during which this proposal received support and no objections from the FINOS Community, Ffion Acland became the project lead on February 19th 2021. 

The FINOS Financial Objects project currently has two work streams: Commodities Payout and Product Control Common Template.

## Commodities Payout Workstream

The Commodities Payout Workstream was [proposed](https://github.com/finos/community/issues/102) and is led by Goldman Sachs.

### Business Problem
The ISDA CDM recently introduced its first instance of Commodities representation & looked to capture Payout terms of a vanilla swap. There are many other iterations of Commodities contracts that would benefit from a industry standard being created and the driver of this group is to continue to build the CDM and look to capture payouts associated with Commodity Options in the first instance.

### Proposed Solution
Looking to tackle the Commodity Option payout first, the proposed solution will look to build on the existing generic option component with any additional terms that are relevant to commodities but not necessarily captured.

### Roadmap
_Coming soon_

### Contribute to the Commodities Payout workstream

There are several ways to contribute to the Commodities Payout workstream:

- **Join the next meeting**: participants of the Commodities Payout workstream meet every Thursday at 11am ET / 4pm GMT. Find the next meeting on the [FINOS project meetings calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York) and browse past meeting minutes in [GitHub](https://github.com/finos/finos-fo/issues?q=label%3Ameeting) 
- **Join the mailing list**: Communications for the Commodities Payout workstream are conducted through the commodities-payout@finos.org mailing list. Please email commodities-payout+subscribe@finos.org to join the mailing list.
- **Raise an issue**: if you have any questions or suggestions, please raise an issue at https://github.com/finos/finos-fo/issues/new/choose
- **Contribute to building the Commodities Payout model**: reach out to commodities-payout@finos.org expressing your interest in contributing.

#### Legend Studio
Please note that modeling is being done in the FINOS hosted instance of [Legend Studio](https://github.com/finos/legend-studio), and a copy of the ISDA CDM in the FINOS hosted instance of Legend Studio can be accessed at https://legend.finos.org/studio/viewer/UAT-34. Please note that you will need to have an account on the FINOS hosted instance of Legend Studio in order to access it. You can request an account at [finos.org/legend](https://www.finos.org/legend). 


## Product Control Common Template Workstream

The Product Control Common Template Workstream was [proposed](https://github.com/finos/community/issues/97) and is led by Goldman Sachs.

### Business Problem
There are multiple vendors currently providing consensus based pricing services and each vendor have their own template requirements. The different submission and consensus templates have increased the onboarding cost for participants to switch between / subscribe for multiple vendors. 

### Proposed Solution
To overcome this inconsistency, we are aiming to create an industry standard common template for submitting to and getting data back from vendors. This would help to streamline the submission process by applying a consistent approved format for this submission. This removes the dependence on template naming conventions and the cost when these are changed.

### Approach
- Construct a common template data model using Legend Studio.
- This common template data model will become a candidate for inclusion to the CDM and will include all the attributes that each vendor is required to run their valuation process and return the consensus data to the banks.
- Banks can connect their daily pricing data to the industry approved model for submission and vendor can leverage the same model to provide the consensus data. Thereby, both the banks and vendor will communicate in the same common model language.

### Roadmap
_Coming soon_

### Contribute to the Product Control Common Template Workstream

There are several ways to contribute to the Product Control Common Template Workstream:

- **Join the next meeting**: participants of the Product Control Common Template Workstream meet every Monday at 10am ET / 3pm GMT. Find the next meeting on the [FINOS project meetings calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York) and browse past meeting minutes in [GitHub](https://github.com/finos/finos-fo/issues?q=label%3Ameeting) 
- **Join the mailing list**: Communications for the Product Control Common Template workstream are conducted through the product-control-common-template@finos.org mailing list. Please email product-control-common-template+subscribe@finos.org to join the mailing list.
- **Raise an issue**: if you have any questions or suggestions, please raise an issue at https://github.com/finos/finos-fo/issues/new/choose
- **Contribute  to building the common template**: reach out to product-control-common-template@finos.org expressing your interest in contributing.

#### Legend Studio
Please note that modeling is being done in the FINOS hosted instance of [Legend Studio](https://github.com/finos/legend-studio), and a copy of the ISDA CDM in the FINOS hosted instance of Legend Studio can be accessed at https://legend.finos.org/studio/viewer/UAT-34. Please note that you will need to have an account on the FINOS hosted instance of Legend Studio in order to access it. You can request an account at [finos.org/legend](https://www.finos.org/legend). 

# Governance

The Financial Objects project is reviewing changes to the default governance, for more information see this GitHub issue: _[Adopt Governance model for the FINOS Financial Objects project](https://github.com/finos/finos-fo/issues/48)_. 


# Contributing

Commits and pull requests to FINOS repositories will only be accepted from those contributors with an active, executed [Individual Contributor License Agreement (ICLA)](https://www.finos.org/hubfs/FINOS/governance/FINOS%20ICLA.pdf) with FINOS OR who are covered under an existing and active [Corporate Contribution License Agreement (CCLA)](https://www.finos.org/hubfs/FINOS/governance/FINOS%20CCLA.pdf) executed with FINOS. Commits from individuals not covered under an ICLA or CCLA will be flagged and blocked by the FINOS Clabot tool. Please note that some CCLAs require individuals/employees to be explicitly named on the CCLA.

*Need an ICLA? Unsure if you are covered under an existing CCLA? Email [help@finos.org](mailto:help@finos.org)*

If you're interested in contributing to Financial Objects data models on the FINOS hosted instance of [Legend Studio](https://github.com/finos/legend-studio), please submit your interest at [finos.org/legend](https://www.finos.org/legend) and you will be granted "read-only" access to **view** models.

**Editing and creating** models in the FINOS hosted instance of Legend Studio is considered an open source contribution, and contributions to FINOS open source projects must be covered by a [Contributor License Agreement (CLA)](https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/75530375/Contribution+Compliance+Requirements#ContributionComplianceRequirements-ContributorLicenseAgreement). If you would like to get access to edit and create models (i.e. "write" access) on the FINOS hosted instance of Legend Studio, your employer will need to sign a [Contributor License Agreement (CLA)](https://www.finos.org/hubfs/FINOS/governance/FINOS%20CCLA.pdf) with the Foundation. Please see the [Contribution Compliance Requirements](https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/75530375/Contribution+Compliance+Requirements) and email help@finos.org with questions. 

## License

Copyright 2019 FINOS The Fintech Open Source Foundation

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
