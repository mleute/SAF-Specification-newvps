![System Architecture Framework](../diagrams/Banner_SAF.png)
# SAF User Documentation : **O4_OCXI** Operational Context Interaction Viewpoint
|**Domain**|**Aspect**|**Maturity**|
| --- | --- | --- |
|[Operational](../domains.md#Domain-Operational)|[Interaction & Collaboration](../aspects.md#Aspect-Interaction-&-Collaboration)|![Under Construction](../diagrams/Under_construction_icon-yellow.svg )[under construction](../using-saf/maturity.md#under-construction)|
## Example
*none*
## Purpose
The Operational Interaction Viewpoint describes single threads of interaction between Operational Performers in an Operational Context on an operational domain level. 
Note: The Operational Interaction Viewpoint may refine an Operational Story.
## Applicability
The Operational Interaction Viewpoint supports the "Business or Mission Analysis Process" and the "Stakeholder Needs and Requirements Definition Process" activities of the INCOSE SYSTEMS ENGINEERING HANDBOOK 2023 [§ 2.3.5.1 § 2.3.5.2] and contributes to the definition of operational scenarios and identification of interface boundaries and interfacing systems.
## Presentation
A sequence diagram featuring the flow of control between Operational Performers of an Operational Context to achieve one outcome of an Operational Story. 
Note: This diagram depicts the sending and receiving of messages between the interacting entities called lifelines where time is represented along the vertical axis. The lifelines representatives are part properties typed by Operational Performers.

## Stakeholder
* [Acquirer](../stakeholders.md#Acquirer)
* [Customer](../stakeholders.md#Customer)
* [System Architect](../stakeholders.md#System-Architect)
## Concern
* [What possible threads of operational process activities have to be carried out to achieve the operational story main and alternative goals?](../concerns.md#_2021x_2_8710274_1674576759199_457359_23612)
## Profile Model Reference
The following Stereotypes / Model Elements are used in the Viewpoint:
* Interaction [UML_Standard_Profile]
* Lifeline [UML_Standard_Profile]
* Message [UML_Standard_Profile]
* [SAF_O4_OCXI](../stereotypes.md#SAF_O4_OCXI)
* [SAF_OperationalContextRole](../stereotypes.md#SAF_OperationalContextRole)
## Input from other Viewpoints
### Required Viewpoints
* [Operational Context Definition Viewpoint](Operational-Context-Definition-Viewpoint.md)
### Recommended Viewpoints
*none*
