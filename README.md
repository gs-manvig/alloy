[![Build Status](https://travis-ci.org/finos/alloy.svg?branch=master)](https://travis-ci.org/finos/alloy)
[![FINOS - Incubating](https://cdn.jsdelivr.net/gh/finos/contrib-toolbox@master/images/badge-forming.svg)](https://finosfoundation.atlassian.net/wiki/spaces/FINOS/pages/75530756/Project+Lifecycle)

# Alloy
On November 20, 2019, at FINOS' flagship conference, the [Open Source Strategy](https://opensourcestrategyforum.org/) Forum, FINOS Platinum member [Goldman Sachs](https://developer.gs.com/docs/products/) announced its intention to open source two closely related products - its internal logical modeling language internally named "PURE", and a visual modeling platform that generates PURE models known in Goldman Sachs as "Alloy" - into FINOS.

More information about this decision and announcement can be found at https://www.finos.org/alloy. 

# [Open Sourcing Roadmap](.github/ROADMAP.md)
- Phase 0 (Q4 2019): Deploy an external instance of Alloy to AWS for Phase 1 shared modeling; announce the intention to open source PURE/Alloy at the [Open Source Strategy Forum](https://opensourcestrategyforum.org/); internal code evaluation and preparation for open sourcing.

- Phase 1 (Q1 2020): Using the external instance of Alloy deployed in phase 0, with a group of bank pilot users, develop common, shared models, licensed under an Apache 2.0 license, written in PURE, likely collaborating first on a derivatives model. In this release, Studio will support the creation of data models, model-to-model mappings constraints and derivations. Continue to prepare code for open sourcing. Develop initial shared roadmap for PURE and Alloy extensions and new features for project developers to work on upon code being open sourced; identify and discuss priority areas for further collaborative model development.

- Phase 2 (Mid 2020): Complete technical and legal reviews of code for release per FINOS contribution process; make underlying PURE and Alloy code bases available as open source under an Apache 2.0 license into a FINOS GitHub repository (targetted to happen in September 2020). Begin accepting pull requests into Alloy from developers outside Goldman Sachs.

A more detailed roadmap is availabe in the [ROADMAP.md file](.github/ROADMAP.md)

And for more information about PURE/Alloy, including some of the motivations behind the decision to open source these two products, see the [Alloy press release](https://www.finos.org/press/goldman-announces-pure-alloy-contribution).

# Documentation Strategy

## [Alloy Documentation Site (alloy.finos.org)](https://alloy.finos.org/)
The [documentation site](https://alloy.finos.org) is built using Docusaurus based on the markdown files in the [`docs`](/docs/) folder. 

## [This Repository - GitHub.com (github.com/finos/alloy)](https://github.com/finos/alloy)

[This repository (github.com/finos/alloy)](github.com/finos/alloy) hosts:
* The underling files for the [Alloy Documentation site](https://alloy.finos.org) (composed in markdown file format and stored in the `docs/` folder)
* The [shared issues list](https://github.com/finos/alloy/issues) used for task management to track project activity around documentation, deployments, and the overall effort associated with open sourcing PURE and Alloy
*  These issues are organized in various kanban boards, including the [overall project kanban](https://github.com/orgs/finos/projects/5).

## [FINOS Hosted GitLab Repository (gitlab.alloy.finos.org)](https://gitlab.alloy.finos.org)
A separate [hosted Gitlab repository, gitlab.alloy.finos.org](gitlab.alloy.finos.org) hosts shared models being developed by the [Alloy project pilot team](https://groups.google.com/a/finos.org/forum/#!forum/alloy-pilot).

## [gitlab.com (https://gitlab.com/finosfoundation)](gitlab.com/finosfoundation)
Documentation specific to particular families and groups of models will be created and curated on GitLab.com at [https://gitlab.com/finosfoundation](https://gitlab.com/finosfoundation). In Phase 2, it's possible that the shared model definitions themselves may be migrated from the hosted GitLab instance to Gitlab.com. 



# Contributing
See our [CONTRIBUTING.md](.github/CONTRIBUTING.md)

# Installation
(Coming Soon; Information on running and installing your own instance of Alloy, either on premise or in a cloud provider such as AWS, Azure, OpenShift, Google, etc.)

# Usage example
(Coming Soon)

# Development setup
(Coming Soon)

# License
Copyright 2020 Goldman Sachs

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
