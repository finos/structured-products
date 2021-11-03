[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-incubating.svg)](https://finosfoundation.atlassian.net/wiki/display/FINOS/Incubating)

# Structured Products

# Overview
The FINOS Structured Products project, led by Goldman Sachs and FragmosChain, aims to accelerate the build and support of structured products in the [ISDA Common Domain Model (CDM)](https://www.isda.org/2019/10/14/isda-common-domain-model/).

For background on the Structured Products project, see [github.com/finos/financial-objects/issues/66](https://github.com/finos/financial-objects/issues/66) and [github.com/finos/community/issues/133](https://github.com/finos/community/issues/133), as well as the [FINOS Legend Pilot Case Study](https://www.finos.org/hubfs/FINOS/assets/FINOS%20Legend%20Case%20Study%202021.pdf). 

## Business Problem

1. As part of Phase 2 of the [Legend Studio FX Options pilot](https://www.finos.org/hubfs/FINOS/assets/FINOS%20Legend%20Case%20Study%202021.pdf), participants designed a CDM event function for `Knock In` (KI) lifecycle events (see [Minutes 9Jul20](https://github.com/finos/legend/issues/179) for details). At the time, the Studio feature for creating functions was to be built and submission was pending, but now the feature is ready for use. The following [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/) primitives formed the proposed `Knock In` function: `ObservationPrimitive` and `ExercisePrimitive`. However the CDM event model has since evolved and these primitives are deprecated.
 
2. Today the [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/) has representation for vanilla products across the five key derivative asset classes but is yet to define more complex payouts. As the industry progresses to adopt the [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/) in trade processing, more complex products will need to be supported and will offer the industry well defined standards that haven't been available to date.

## Proposed Solution

1. The proposed `Knock In` function will need further review and update, and ask is to collaborate on creating a new `Knock In` function solution for the [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/).

2. Project leads believe most of the building blocks are already available in the current state of the [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/). Expected work would mainly consist of moving/replicating existing items with some selective amendments, rather than creating many new items. Project participants will work together to validate this and build the code to define specific structured products of interest.

# Roadmap

Project participants will begin by looking at the representation of the event function `Knock-In` and then progress to the representation of equity baskets. The proposal is to continue the work post completion of these two initial focus areas as the industry requires.

Modeling is being done in the [FINOS hosted instance of Legend Studio](https://legend.finos.org/studio), and a copy of the [CDM](https://www.isda.org/2019/10/14/isda-common-domain-model/) in Legend Studio can be accessed at https://legend.finos.org/studio/viewer/UAT-38. 

Please note that you will need to have an account on the [FINOS hosted instance of Legend Studio](https://legend.finos.org/studio) in order to access it. You can request an account at [finos.org/legend](finos.org/legend).

# Contributing: Get Involved
There are several ways to contribute to the Structured Products project:

* **Join the next meeting**: participants of the Structured Products project meet every second Wednesday at 9am ET / 2pm GMT. Find the next meeting on the [FINOS Community calendar](https://calendar.google.com/calendar/u/0/embed?src=finos.org_fac8mo1rfc6ehscg0d80fi8jig@group.calendar.google.com&ctz=America/New_York) and browse [past meeting minutes in GitHub](https://github.com/finos/structured-products/issues). Email [help@finos.org](mailto:help@finos.org) to be added to the recurring calendar invite.
* **Join the mailing list**: Communications for the Structured Products project are conducted through the **structured-products@lists.finos.org** mailing list. Please email [help@finos.org](mailto:help@finos.org) to be added to the mailing list.
* **Propose changes to the model**: request an account on the FINOS Legend Studio hosted instance at [finos.org/legend](https://www.finos.org/legend) in order to access the model at https://legend.finos.org/studio/-/setup/UAT-28793838. 
* **Raise an issue**: if you have any questions or suggestions, please [raise an issue](https://github.com/finos/structured-products/issues)

_NOTE:_ Commits and pull requests to FINOS repositories will only be accepted from those contributors with an active, executed Individual Contributor License Agreement (ICLA) with FINOS OR who are covered under an existing and active Corporate Contribution License Agreement (CCLA) executed with FINOS. Commits from individuals not covered under an ICLA or CCLA will be flagged and blocked by the FINOS Clabot tool (or [EasyCLA](https://github.com/finos/community/blob/master/governance/Software-Projects/EasyCLA.md)). Please note that some CCLAs require individuals/employees to be explicitly named on the CCLA.

*Need an ICLA? Unsure if you are covered under an existing CCLA? Email [help@finos.org](mailto:help@finos.org)*

## License

Copyright 2021 FINOS

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
