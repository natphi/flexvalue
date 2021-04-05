# Technical Charter (the "Charter") for the FLEXvalue engine

Adopted <date>

This charter (the "Charter") sets forth the responsibilities and procedures for technical contribution to, and oversight of, the [FLEXvalue] project.. All Contributors to the Project must comply with the terms of this Charter.
Mission and Scope of the Project

    a) The mission of the Project is to develop an open source project with the following goals:
        i) Build and maintain an open source engine for calculating the value of changes in energy consumption attributable to specific interventions at the utility meter and enable the rapid diffusion of distributed energy resources;
        ii) Maintain a production-ready project to provide consistent transactional information on value for distributed energy resources consistent with regulatory and market requirements. ;
        iii) Ensure transparency and trust by providing open source code that enables reliable validation and mutual accountability in regulatory environments and energy markets;
        iv) Provide reusable components with documented APIs and consistent security practices; and
        v) Develop an ecosystem of developers, suppliers, OEMs, systems integrators, regulators, and customers all using this common platform as the basis to define common transactional units for distributed energy resources in the market.
    b) The scope of the Project includes software development under OSI-approved open source licenses supporting the mission, documentation, testing, integration and the creation of other artifacts that aid the development, deployment, operation or adoption of the open source software project.

# Technical Steering Committee

    a) The Technical Steering Committee (the "TSC") will be responsible for all technical oversight of the open source Project.
    b) Composition
    "Startup Period": During the initial twelve (12) months after project launch or for such time period as the TSC may otherwise approve, the TSC voting members will be determined by the Project’s Committers at the time of Project creation.
    "Steady State": After the Startup Period, there will be a nomination and election period for electing Contributors or Committers to the TSC. The TSC voting members will consist of elected Contributors or Committers chosen by the Committers, as defined herein. The TSC will approve the process and timing for nominations and elections held on an annual basis, and will decide the long-term size of the TSC.
    c) At an appropriate time (e.g., after the first release), the TSC shall approve a transition plan to transition the TSC from the Startup Period to Steady State.
    d) The list of current TSC voting members shall be maintained with the MAINTAINERS file within the Project’s code repository. The TSC may choose an alternative approach for determining the voting members of the TSC, and any such alternative approach will be documented in the MAINTAINERS file. Any meetings of the Technical Steering Committee are intended to be open to the public, and can be conducted electronically, via teleconference, or in person.
    e) TSC projects generally will involve Contributors and Committers. The TSC may adopt or modify roles so long as the roles are documented in the CONTRIBUTING file. Unless otherwise documented:
        i) Contributors include anyone in the technical community that contributes code, documentation, or other technical artifacts to the Project;
        ii) Committers are Contributors to whom the Project has granted the privilege of modifying ("committing") source code, documentation or other technical artifacts directly in a Project repository; and ..
        iii) A Contributor may become a Committer by a three-quarter majority of the existing Committers. A Committer may be removed by a majority approval of the other existing Committers.
    f) Participation in the Project through becoming a Contributor and Committer is open to anyone so long as they abide by the terms of this Charter and abide by the Project's Code of Conduct.
    g) The TSC may (1) establish work flow procedures for the prioritization, submission, approval, and closure/archiving of projects, (2) set requirements for the promotion of Contributors to Committer status, as applicable, and (3) amend, adjust, refine and/or eliminate the roles of Contributors, and Committers, and create new roles, and publicly document any TSC roles, as it sees fit.
    h) The TSC may elect a TSC Chair, who will preside over meetings of the TSC and will serve until their resignation or replacement by the TSC. The TSC Chair, or any other TSC member so designated by the TSC, will serve as the primary communication contact between the Project and LF Energy as the Project's representative to the TAC.
    i) Responsibilities: The TSC will be responsible for all aspects of oversight relating to the Project, which may include:
    i) coordinating the technical direction of the Project;
    ii) approving project or system proposals (including, but not limited to, incubation, deprecation, and changes to a sub-project’s scope);
    iii) organizing sub-projects and removing sub-projects;
    iv) creating sub-committees or working groups to focus on cross-project technical issues and requirements;
    v) appointing representatives to work with other open source or open standards communities;
    vi) establishing community norms, workflows, issuing releases, and security issue reporting policies;
    vii) approving and implementing policies and processes for contributing (to be published in the project repository) and coordinating with the Series Manager to resolve matters or concerns that may arise as set forth in Section 7 of this Charter;
    viii) discussions, seeking consensus, and where necessary, voting on technical matters relating to the code base that affect multiple projects; and
    ix) coordinating any marketing, events, or communications regarding the Project.
TSC Voting

    a) While the Project aims to operate as a consensus-based community, if any TSC decision requires a vote to move the Project forward, the voting members of the TSC will vote using the Approval Voting method.
    b) Quorum for TSC meetings requires at least fifty percent of all voting members of the TSC to be present. The TSC may continue to meet if quorum is not met, but will be prevented from making any decisions at the meeting.
    c) Except as provided in Section 7.c. and 8.a, decisions by vote at a meeting require a majority vote of those in attendance, provided quorum is met.
    d) Decisions made by electronic vote without a meeting require a majority vote of all voting members of the TSC.
    e) In the event a vote cannot be resolved by the TSC, any voting member of the TSC may refer the matter to the Series Manager for assistance in reaching a resolution.
    Compliance with Policies

    a) This Charter, adopts by reference and will comply with the Series Agreement for the Project and the Operating Agreement of LF Projects. Contributors will comply with the policies of LF Projects as may be adopted and amended by LF Projects, including, without limitation the policies listed at https://lfprojects.org/policies/.
    b) The TSC may adopt a code of conduct ("CoC") for the Project. Contributors to the Project will comply with the CoC or, in the event that a Project-specific CoC has not been approved, the LF Projects Code of Conduct listed at https://lfprojects.org/policies/.
    c) All participants must allow open participation from any individual or organization meeting the requirements for contributing under this Charter and any policies adopted for all participants by the TSC, regardless of competitive interests. Put another way, the Project community must not seek to exclude any participant based on any criteria, requirement, or reason other than those that are reasonable and applied on a non-discriminatory basis to all participants in the Project community.
    d) The Project will operate in a transparent, open, collaborative, and ethical manner at all times. All official Project discussions, proposals, timelines, decisions, and status should be made open and easily accessible to all; while private discussions may happen, the basis for decisions should be publicly documented and accessible.

# General Rules and Operations

    a) The Project will:
        i) engage in the work of the project in a professional manner consistent with maintaining a cohesive community, while also maintaining the goodwill and esteem of other partner organizations in the open source software community; and
        ii) respect the rights of all trademark owners, including any branding and trademark usage guidelines.
 
# Intellectual Property Policy

    a) Participants acknowledge that the copyright in all new contributions will be retained by the copyright holder as independent works of authorship and that no contributor or copyright holder will be required to assign copyrights to the Project.
    b) Except as described in Section 7.c., all contributions to the Project are subject to the following:
        i) All new inbound code contributions to the Project must be made using an OSI-approved open source license specified for the Project within the "LICENSE" file within the Project’s code repository (the "Project License").
        ii) All new inbound code contributions must also be accompanied by a Developer Certificate of Origin (http://developercertificate.org) sign-off in the source code system that is submitted through a TSC-approved contribution process which will bind the authorized contributor, and, if not self-employed, their employer to the applicable license(s);
        iii) All outbound code will be made available under the Project License.
        iv) Documentation will be received and made available by the Project under the Creative Commons Attribution 4.0 International License (available at http://creativecommons.org/licenses/by/4.0/).
        v) The Project may seek to integrate and contribute back to other open source projects ("Upstream Projects"). In such cases, the Project will conform to all license requirements of the Upstream Projects, including dependencies, leveraged by the Project. Upstream Project code contributions will comply with the contribution process and license terms for the applicable Upstream Project.
    a) The TSC may approve the use of an alternative license or licenses for inbound or outbound contributions on an exception basis. To request an exception, please describe the contribution, the alternative open source license(s), and the justification for using an alternative open source license in the Project. License exceptions must be approved by a two-thirds vote of the entire TSC.
    b) Contributed files should contain license information, such as SPDX short form identifiers, indicating the open source license or licenses pertaining to the file.
Amendments

This charter may be amended by a two-thirds vote of the entire TSC. 
