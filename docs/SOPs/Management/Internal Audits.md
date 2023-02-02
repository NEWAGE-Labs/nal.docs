# Standard Operation Procedure - Internal Audits

>Most recently edited by: *Paul VanderWeele*  
>Most recent edit date: *May 20, 2022*  
>Edits were authorized by: *Paul VanderWeele*

## Table of Contents

[Related Procedures](#related-procedures)  
[Purpose and Scope](#purpose-and-scope)  
[Terms and Definitions](#terms-and-definitions)  
[Internal Audit Program Details](#internal-audit-program-details)  
[Completing an Internal Audit](#completing-an-internal-audit)
[Training and Authorization](#training-and-authorization)  
[Additional Information](#additional-information)  

## Related Procedures  

#### Required Procedures  

[QSP - Audits](../../QSPs/Audits.md)  

#### Related QSPs

[QSP - Control of Nonconforming Work](../../QSPs/Control of Nonconforming Work.md)  
[QSP - Technical Records](../../QSPs/Technical Records.md)  
[QSP - Document Control and Management](../../QSPs/Document Control and Management.md)  
[QSP - Management Review](../../QSPs/Management Review.md)  

#### Related SOPs

[External Audits](./External Audits.md)  
[Git](../Software and Computers/Git.md)
[GitHub](../Software and Computers/GitHub.md)  

## Purpose and Scope

The goal of this procedure is to provide understand and guidance on performing, training on, and understanding the internal auditing process at NAL. Internal audits are one of the most powerful management system tools that we can utilize to help identify risks, discover opportunities for improvement, and verify conformity across the vast and complex structure of NAL. Internal audits are voluntary and are planned ahead of time according to the [NAL Internal Audit Program](#internal-audit-program).

Like all NAL audits, this procedure is based upon [ISO 19011: 2018](../../parent_pdfs/ISO-19011-2018.pdf).

## Terms and Definitions

###### Audit

>A systematic, independent and documented process for obtaining [objective evidence](#objective-evidence) and evaluating it objectively to determine the extent to which the [audit criteria](#audit-criteria) are fulfilled.  

> see: [QSP - Audits; Definition: 'Audit'](../../QSPs/Audits.md#audit)

###### Internal Audit

>An [audit](#audit) conducted by NAL on behalf of itself. Also known as a 'First Party Audit'.  

> see: [QSP - Audits; Defintion: 'Internal Audit'](../../QSPs/Audits.md#internal-audit)

###### Internal Audit Plan

>A description of the activities and arrangements for an individual [internal audit](#internal-audit), including details such as attending personnel, itineraries, and technical considerations.  

###### Internal Audit Program

> The list of all planned [internal audits](#internal-audit) for NAL.

###### Internal Audit Scope

>The extent of a [management system](#management-system) to which an individual [internal audit](#internal-audit) will cover, including details such as location, organizations involved, [processes](#process) covered, and time frame.  

###### Internal Audit Objective

>A functional goal or purpose in performing an [internal audit](#internal-audit). Objectives can include reviewing documentation, re-evaluating uncertainty, identifying [risks](#risk), discovering [opportunity](#opportunity) for improvement, following up on a previous corrective action to ensure compliance, or something else relevant to the quality or operation of a [mangement system](#management-system).

###### Internal Audit Team

>One or more persons conducting an [internal audit](#internal-audit), supported if needed by [technical experts](#technical-expert). One [internal auditor](#internal-auditor) of the internal audit team is appointed as the [internal audit team leader](#internal-audit-team-leader).

###### Internal Auditor

>A person who conducts an [internal audit](#internal-audit) on the [internal audit team](#internal-audit-team). Internal auditors should be chosen based on the guidance in ISO 19011:2018.

###### Technical Expert

>A person who provides specific knowledge or expertise to the [internal audit team](#internal-audit-team), but is not themselves an [internal-auditor](#internal-auditor). This knowledge or expertise can relate to the organization, an activity, a process, a product, a service, a discipline, a language, or a culture.

###### Internal Audit Team Leader

>The [internal auditor](#internal-auditor) holding responsibility and leadership of the [internal audit](#internal-audit). The internal audit team leader is accountable for the accomplishment of the [internal audit plan](#internal-audit-plan) and the completion of the [internal audit report](#internal-audit-report).

###### Internal Audit Sampling

> Internal audit sampling takes place when it is not practical or cost effective to examine all available information during an [internal audit](#internal-audit). When records are too numerous or too complexly dispersed to justify examining every item in the population, conventional sampling methods are utilized impartially to represent the population and to achieve [internal audit objectives](#internal-audit-objective).

###### Management System

>A set of interrelated or interacting elements of an organization to establish policies and objectives, as well as [processes](#process) to achieve those objectives. A management system can address a single discipline or several disciplines, e.g. quality management, financial management or environmental management. The management system elements establish the organization’s structure, roles and responsibilities, planning, operation, policies, practices, rules, beliefs, objectives and processes to achieve those objectives. The scope of a management system can include the whole of the organization, specific and identified functions of the organization, specific and identified sections of the organization, or one or more functions across a group of organizations.

###### Requirement

>Need or expectation that is stated, implied, or obligatory.

###### Process

>A set of interrelated or interacting activities that use inputs to deliver an intended result.

###### Risk

>An effect of uncertainty deviating from the expected. Risk can be positive or negative, is often characterized by reference to potential events, and is often expressed in terms of a combination of:
*the consequences of an event
*the likelihood of it occurring.

###### Opportunity

>A set of circumstances that makes it possible to do something, particularly something with a positive effect on the quality and success of a person or organization.  

## Internal Audit Program Details

The [NAL Internal Audit Program](#internal-audit-program) is an [audit program](../../QSPs/Audits.md#audit-program) hosted on the [NAL GitHub Organization Page](https://github.com/NEWAGE-Labs), and is implemented using a [GitHub Project](../Software and Computers/GitHub.md#project).

#### Internal Audit Program Requirements:

This program should include, at minimum, internal audit plans scheduled within the next 6 months and should include:  

- Objectives for the audit program;  
- [Risks](../../QSPs/Audits.md#risk) and [opportunities](../../QSPs/Audits.md#opportunity) associated with the audit program and the actions to address them;  
- Scope (extent, boundaries, locations) of each audit within the audit program;  
- Schedule (number/duration/frequency) of the audits;  
- [Audit Criteria](../../QSPs/Audits.md#audit-criteria) used to evaluate evidence against;  
- [Audit Methods](../../QSPs/Audits.md#audit-method) to be employed;  
- Criteria for selecting [internal audit team](#internal-audit-team) members and [leader](#internal-audit-team-leader);  
- Relevant documented information.  

#### Management of the Internal Audit Program

The [Quality Mangement Team](../../index.md#quality-management-team) is responsible for the maintenance of the [Internal Audit Program](#internal-audit-program). This includes implementing audits that are scheduled during their schedule time frames, and updating the audit plan based on [Management Reviews](../../QSPs/Management Review.md), in response to [Nonconformities](../../QSPs/Audits.md#nonconformity), and in accordance with new risks and opportunities identified.

#### Controlling Internal Audit Program Records

[Internal Audit Program](#internal-audit-program) records are stored and maintained in accordance with the [Quality System Manual](../../index.md) and [QSP - Technical Records](../../QSPs/Technical Records.md), and changes are preserved via [Git](../Software and Computers/Git.md) and controlled according to [QSP - Document Control and Management](../../QSPs/Document Control and Management.md).

Records are typically stored using branching, commits, pull requests, projects, issues, and merges on [GitHub](../Software and Computers/GitHub.md). The majority of records are stored within the [NAL Internal Audit Program GitHub project](https://github.com/orgs/NEWAGE-Labs/projects/6) and inside [repositories](../Software and Computers/GitHub.md#repository) on the [NAL GitHub Organization Page](https://github.com/NEWAGE-Labs).

While [Issues](../Software and Computers/GitHub.md#issue) are not directly stored within [the Git tree](../Software and Computers/Git.md#the-git-tree), their number and reference is stored inside the commit message of the pull request. By locating the issue ID in the commit message, and pairing it with the issue ID for that respective repository, all records are able to be recreated outside of the [GitHub](https://github.com) web service.

#### Updating the Internal Audit Program

Updates to the [Internal Audit Program](#internal-audit-program) are made directly by the [Quality Mangement Team](../../index.md#quality-management-team), or someone else with [authorization to update the internal audit program](#training-and-authorization). Updates should be made promptly in response to [Nonconformities](../../QSPs/Audits.md#nonconformity), as a result of [Management Reviews](../../QSPs/Management Review.md), or based on newly identified [Risk](../../QSPs/Audits.md#risk) and opportunities for improvement.

#### Internal Audit Program Review

The [Internal Audit Program](#internal-audit-program) is reviewed by the [Quality Management Team](../../index.md#quality-management-team) and any other internal auditors to ensure the Internal Audit Program is being monitored and controlled to evolve with changing needs, methods, risks, opportunities, confidentiality, and objectives. This review is done periodically, and records are documented in accordance with [QSP - Technical Records](../../QSPs/Technical Records.md).

## Completing an Internal Audit  

The steps involved in successfully completing an [internal audit](#internal-audit) are:

1. [Initiating the Internal Audit](#initiating-internal-audit)  
2. [Preparing the Internal Audit](#preparing-internal-audit)  
3. [Conducting the Internal Audit itself](#conducting-internal-audit)  
4. [Completing the Internal Audit Report](#completing-internal-audit-report)  
5. [Finalizing the Internal Audit](#finalizing-internal-audit)  

### Initiating Internal Audit  

The first step in [completing an internal audit](#completing-an-internal-audit) is to begin initiation. The person who leads this initiation, or the person designated as the leader is assigned the role of [Internal Audit Team Leader](#internal-audit-team-leader). Without an internal audit team leader, and [internal audit](#internal-audit) cannot be initiated.

#### Establishing Contact

Before an [internal audit](#internal-audit) can occur, all relevant parties must establish communication and confirm the authority conducting the internal audit. The [Internal Audit Team Leader](#internal-audit-team-leader) is responsible for making sure this coordination happens and is also responsible for providing:

- Information on the internal audit [objectives](#internal-audit-objectives), [scope](#internal-audit-scope), [criteria](../../QSPs/Audits.md#audit-criteria), [methods](../../QSPs/Audits.md#audit-method), and [team](#internal-audit-team) composition.  
- Information relevant to [risks](#risk) and [opportunities](#opportunity) that NEW AGE has identified that will be addressed during the internal audit.  
- Applicable statutory, regulatory, and other [requirements](#requirement) to the [processes](#process) relevant to the internal audit.  
- The extent to which confidential information will be disclosed.  
- Requested observers and [technical experts](#technical-expert).

#### Determining Feasibility

[Internal audits](#internal-audit) that are not feasible are not effective, and therefore it is important to determine the feasibility of an internal audit before preparations can occur.

Determining whether an internal audit is feasible should be done by the [internal audit team](#internal-audit-team), who should ensure there is adequate information and time for [preparing](#preparing-internal-audit) and [conducting](#conducting-internal-audit) the internal audit.

### Preparing Internal Audit  

Prior to [conducting an internal audit](#conducting-internal-audit), it is important to ensure preparations are successfully performed.

#### Performing Review of Documented Information

Relevant [documents](../../QSPs/Document Control and Management.md) and [records](../../QSPs/Technical Records.md) should be gathered to determine the extent of [conformity](../../QSPs/Audits.md#conformity) and possible areas of [nonconformity](../../QSPs/Audits.md#nonconformity), an [internal audit plan](#internal-audit-plan) should be made by the [internal audit team leader](#internal-audit-team-leader), and all information relevant to proceeding with [internal audit](#internal-audit) should be [documented](../../QSPs/Document Control and Management.md) and [recorded](../../QSPs/Technical Records.md).

#### Internal Audit Planning

The [internal audit team leader](#internal-audit-team-leader) should adopt a [risk](#risk)-based approach to planning the audit based on the information in the [internal audit program](#internal-audit-program) and the gathered [documents](../../QSPs/Document Control and Management.md) and [records](../../QSPs/Technical Records.md).

In planning the [internal audit](#internal-audit), the [internal audit team leader](#internal-audit-team-leader) should consider the following:

- The composition of the [internal audit team](#internal-audit-team) and its overall competences;  
- The appropriate [internal audit sampling](#internal-audit-sampling) techniques;  
- [Opportunies](#opportunity) to improve the effectiveness and efficiency of the [internal audit](#internal-audit) activities.  
- [Risks](#risk) to achieving the [internal audit objectives](#internal-audit-objective) created by ineffective [internal audit planning](#internal-audit-planning).  
- [Risks](#risk) to NEW AGE created by performing the [internal audit](#internal-audit).  

The scale and content of the internal audit planning can differ depending on the [management system](#management-system) being audited, whether it is an initial or subsequent internal audit, and if the internal audit is being used for training or monitoring purposes.  

The [internal audit plan](#internal-audit-plan) should address or reference the following in some way:

1. The [internal audit objectives](#internal-audit-objective);  
2. The [internal audit scope](#internal-audit-scope) as well as the [processes](#process) and their functions to be audited.  
3. The internal [audit criteria](../../QSPs/Audits.md#audit-criteria) and any reference documented information.  
4. The locations, dates, expected start times, and durations of the internal audit activities to be conducted, including meetings.  
5. The internal [audit methods](../../QSPs/Audits.md#audit-method) to be used, including the extent to which [internal audit sampling](#internal-audit-sampling) is needed to obtain sufficient internal [audit evidence](../../QSPs/Audits.md#audit-evidence).  
6. Any logistics or matters related to transportation, confidentiality, information security, health, or safety.  
7. Any follow-up information from previous [audits](#audits).  
8. Any coordination needed with other audit activities, in the case of a [combined audit](../../QSPs/Audits.md#combined-audit) or [joint audit](../../QSPs/Audits.md#joint-audit).  

#### Assigning Work to the Internal Audit Team

The [internal audit team leader](#internal-audit-team-leader) should conduct meetings as appropriate with the [internal audit team](#internal-audit-team) to allocate work and responsibilities. These assignments should take into account the impartiality, objectivity, and competence of [internal auditors](#internal-auditor) and the effective use of resources.

#### Preparing Documented Information for Internal Audit

[Internal audit team](#internal-audit-team) members should collect and review the information relevant to their allocated responsibilities. Information designated for the audit needs to be documented in a way that can be stored as a [technical record](../../QSPs/Technical Records.md).

### Conducting Internal Audit  

#### Observers and Technical Experts

[Observers](../../QSPs/Audits.md#observer) and [Technical Experts](#technical-expert) may accompany the [internal audit team](#internal-audit-team) with the approval of the [internal audit team leader](#internal-audit-team-leader).

Observers may observe for their own education and insight, or as a witness or source of subjective information where appropriate.

Technical Experts may assist the internal audit team in scheduling, providing clarification or information, accessing restricted locations, ensuring health and safety, and navigating complex technology.

#### Opening Meeting

The purpose of the opening meeting is to:

1. Confirm the agreement of all participants to the [internal audit plan](#internal-audit-plan).
2. Introduce the [internal audit team](#internal-audit-team) and their roles and responsibilities.
3. Ensure all planned [internal audit](#internal-audit) activities can be performed.

#### Communication During an Internal Audit

The [internal audit team leader](#internal-audit-team-leader) should periodically communicate the progress of the [internal audit](#internal-audit) to the [internal audit team](#internal-audit-team), and should allow arrangements for communication to occur within the internal audit team.

#### Reviewing Internal Audit Documents

Relevant documented information should be reviewed to determine the [conformity](../../QSPs/Audits.md#conformity) of the system with the internal [audit criteria](../../QSPs/Audits.md#audit-criteria). Gaps in expected documented should be noted for the [Internal Audit Report](#completing-internal-audit-report).

### Completing Internal Audit Report  

###### Audit Date  
###### Audit Criteria  
###### Audit Client  
###### Auditors and Team Leader  
###### Source of Information  
###### Sampling  
###### Evidence  
###### Findings  
###### Reviewing  
###### Conclusions  
###### Follow-Up  
###### Report  

### Finalizing Internal Audit  

## Training and Authorization  

Confidence in the internal audit process depends on the competence of those involved in performing internal audits. [Internal Auditors](#internal-auditor) and [Internal Audit Team Leaders](#internal-audit-team-leader) should be evaluated for competence via a process that is planned, implemented, and documented to provide and outcome that is objective, consistent, fair, and reliable. Additional guidance for accomplishing this can be found in [ISO 19011:2018](../../parent_pdfs/ISO-19011-2018.pdf).

Training for competence in [internal audits](#internal-audit) requires the completion of an entire internal audit on at least one process by the training personnel. Supervision and authorization can be performed by any personnel with competence in internal audits, and is indicated on both the [internal audit plan](#internal-audit-plan) and the [internal audit report](#completing-internal-audit-report).

Monitoring of competence is done through the repeated completion of at least 1 internal audit plan and internal audit report throughout the year. Evidence of monitoring is the documented plan and report.

## Additional Information  
