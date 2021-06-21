# Expanded InnerSource Capability Model

| Theme | Capability | Component |   Nascent (0) | Emerging (1) | Established (2) | Leading Practice | Comparable Open Source Leading Practice 
|--|--|--|--|--|--|--|--|
| Transparency | Plans & Products |--| PP-0: Individuals and teams do not regularly disclose their plans or products to multiple stakeholders. No formal actions exists at the organization.|PP-1: Individuals and teams give visibility to their plans or products to multiple stakeholders, before they are started. Shared roadmap.|PP-2: There are already shared roadmaps with clear guidelines and contribution rules where stakeholders can provide feedback. However this is not standardized across the organization and not all of the projects provide this info.|PP-3: Roadmaps are shared by default and there is a standard process and homogeneous way to do this across the organization at the level of each InnerSource project. This contains clear rules to contribute and influence in the roadmap.|
| | | _Roadmaps_ | _No project roadmap exists or roadmap is not shared publicly_  | | | | _A ROADMAP.md or similar document exists in the root of the distributed version control system (e.g., GitHub); The roadmap is also featured in a prominent place on the projects website, if one exists_|
|| Development Process & Tools | | | | | 
||| _Backlog, Scheduling, and Prioritization_
||| _CI/CD_||||| _It's common for open source repositories to be configured such that builds, using tools such as TravisCI, CircleCI, or GitHub Actions, can be triggered and/or configured to be triggered, by project maintainers. Conditions for which builds are set to be run are often related to particular forms of branch merges to the main (a.k.a., "master") branch and/or some or all accepted pull requests._
|| Decisions | | | | | 
|| Helpful Resources | | RS-0: Individuals and teams neither contribute to nor draw upon a shared repository of knowledge. | RS-1: Individuals and teams release project materials for review internally, after they've finished their work. Individuals and teams share resources, but in disconnected, fragmented, or individualized/siloed systems or repositories. Individuals and teams share resources, but there is no commonly expressed or shared understanding of the criteria used to determine whether information is sensitive or not. Do not "share thinking on others".| RS-2: Individuals and teams make project-related materials accessible to some members of project teams according to clearly defined and shared formats and/or protocols. Individuals and teams withhold sensitive data and resources, provide limited details, context, and scope. | RS-3: Individuals and teams make project-related materials broadly accessible to the organization—and possibly outside the organization as well—according to clearly defined and shared formats and/or protocols. Individuals and teams who must withhold sensitive data and resources are clear about what they're not sharing, and others understand why those materials are not available to them.
| | | 
| Collaboration | | | | 
| Documentation and Content (Helpful Resources) |
| Processes and Policies | 
| Incentives and Recognition (Rewards) | | | Participation and contribution to inner sourced projects, including and especially projects beyond one's core team, group, and/or business unit, can be accounted for in the company's performance management system and directly contribute to decisions about incentive compensation -- i.e., such "assists" are formally recognized as important work and rewarded as such |

(Items in italics are proposed adds, expansions, and drill-downs to [InnerSourcePatterns Maturity Model](https://github.com/InnerSourceCommons/InnerSourcePatterns/blob/a9e136eb57fd927c12ee27827e35cd7215226e53/patterns/2-structured/maturity-model.md))



# Corresponding Capability Checklists

The "tick-down" from each capability and its corresponding 4 stages (nascent to leading practice; numbers 0-3 in the InnerSource Commons maturity model) are checklists, composed of groups of atomic, concrete tasks an organization can and should take to further their progress along a capability axis. Something like:

## Roadmap Checklist 
| ROADMAPS - Checklist |  |
|--|--|
| Level | Items |
| Nascent -> Emerging (PP-0 -> PP-1) | Create a public roadmap for the project that at a minimum lays out the major milestones for the next 12 months on a quarterly basis, and summarizes or links to the major project artefacts, epics, and/or backlog(s) (PP-1-1) |
| Nascent -> Emerging (PP-0 -> PP-1) | Check list item 2 (PP-1-2) |
| Emerging --> Established (PP-1 -> PP-2)| Checklist item 3 (PP-2-1) |
| Emerging --> Established (PP-1 -> PP-2)|  Checklist item 4 (PP-2-2) |
| Established --> Leading Practice PP-2 -> PP-3)|  Templates for roadmaps, including examples of the templates in action, have been made widely available to the organization (PP-3-1) |
| Established --> Leading Practice PP-2 -> PP-3)|  A process for sharing roadmaps has been established, and a canonical place (e.g., as a ROADMAP.md at the root of, say, a BitBucket repo) identified such that there is consistency from project to of where roadmaps can be found, and the information they'll include (PP-2-2)

## Documentation and Content Checklist 
| DOCUMENTATION and CONTENT  |  |
|--|--|
| Level | Items |
| Nascent -> Emerging (HF-0 -> HF-1) | (HF-1-1) |
| Nascent -> Emerging (PP-0 -> PP-1) | Check list item 2 (PP-1-2) |
| Emerging --> Established (PP-1 -> PP-2)| Checklist item 3 (PP-2-1) |
| Emerging --> Established (PP-1 -> PP-2)|  Checklist item 4 (PP-2-2) |
| Established --> Leading Practice PP-2 -> PP-3)|  (PP-3-1) |
| Established --> Leading Practice PP-2 -> PP-3)|   (PP-2-2)



# InnerSource Training Topics and Readings
## Open Source Roots
### Open Source -- What is it?
* Open source: A licensing model
* Open source: A set of development practices
* Open source: An ethos, set of values, and cultural framework for building software

#### Licensing Models
##### Permissive Models
##### GPL Family
##### Evolving Landscape, Different Perspectives, and Controversies
* Amazon and Elastic
* Startup Concerns
* Open Data / Big Data
    * _(From Snowflake) [Striking a balance with ‘open’ at Snowflake](https://www.infoworld.com/article/3617938/striking-a-balance-with-open-at-snowflake.html)_
    * _(A Response from Alex Woodie) [Do Customers Want Open Data Platforms?](https://www.datanami.com/2021/05/24/do-customers-want-open-data-platforms/)_
* Commons Tools and Platforms
    * Git
        * _[Git Documentation](https://git-scm.com/)_
        * What is it?
        * How does it work?
            * [Understanding Merkle Trees](https://medium.com/geekculture/understanding-merkle-trees-f48732772199)

## InnerSource: Background, Context, History



# InnerSource and Open Sourcing Decision Framework
Below are some questions organiztions may face when considering choices around inner and open sourcing any of their "home-grown" internal projects within their portfolio:
* Should we "just" inner source or open source the project? Options include:
    * Inner source only (no foreseeable plans to open source)
    * Inner source first, then open source
        * ... open source into organization's own GitHub org (Self-manage/curate/market)
        * ... open source as contribution to a foundation such as FINOS
    * Open source now
        * ... open source into organization's own GitHub org (Self-manage/curate/market)
        * ... open source as contribution to a foundation such as FINOS
    * Do nothing (neither inner source or open source)

* Considerations & Key Questions
    * Does the software produced from the project confer some form of competitive advantage or strategic market power to the organization? Does the code itself represent a trade secret demonstrably worthy of on-going confidentiality?
        * If the answer to these questions is 'yes', and the software is a form of competitive advantage, then inner sourcing may be more appropriate than outright open sourcing in order to retain the competitive advantage
    * 


# Preparing a Project for Inner and Open Source
| Theme | Preparation for Inner Source | Additional Work for Open Source |
|--|--|--|
| Code Modularity |
| Abstration & Generalization | | Remove any and all references to any names, brand symbols, trademarks, etc of the contributing organization within the 

