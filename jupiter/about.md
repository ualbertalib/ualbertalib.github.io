# Project Principles
## UI/UX
User experience is at the centre of our design and development work. We will clearly articulate our design principles guided by industry standards and best practices and will implement a new development and testing process that incorporates evidence from users, including in-person user evaluation and feedback and analysis of analytics and other quantitative measures. Our design decisions will be based on defined user requirements and will be clearly documented in the feature backlog prior to development work beginning.
## Accessibility
We commit to [WCAG](https://www.w3.org/WAI/WCAG20/quickref/) 2.0 level A compliance for this application. We will also conduct an accessibility spike to investigate the requirements of the WCAG AA standard. Ontario accessibility legislation requires AA compliance for publicly-funded institutions, and it is unlikely national legislation will differ markedly from this requirement. If we make a design decision that is not compliant with [WCAG](https://www.w3.org/WAI/WCAG20/quickref/) 2.0 level A, there must be strong documented rationale for that decision and the Product Owner will have approved it. 
Proper setup for internationalization of the application should also included in the design and development of the application, to ensure it will work well for (or ca
## Code Management
The project will have a roadmap with dated milestones and releases, listing implemented features for each release. In github, issues will be tied to epics, which will be associated with milestones mapped to a release roadmap. We require clearly defined epics with clear scope, definition, and standard epic elements. Each epic will require:
* Description (Scope and out of scope; Clear definition of done)
* Rough description of resources needed (dev, metadata, sysadmin time for deployment)
* Architecture diagram (high level) 
* Project sprintboard (Zenhub or Github Projects board)
* Workflow description for UX
* Prototypes or wireframes for UI
* Implementation details 
* Deployment details
* Potential features/out of scope
Scrum-masters will need to adhere to the template defined, and complete related activities to keep the issues, boards and documentation up-to-date. 
## Rails
The project will use standard Rails conventions and will resist custom Rails implementations. This is necessary to ensure for effective onboarding, more sustainable future data migrations, and to reduce/mitigate technical debt inside the project. As with accessibility, if we deviate from standard Rails conversions, we will have a justified reason for doing so and the decision will be clearly documented and approved.
## Data Modeling
We want to enable and participate in interoperability, integration and discovery initiatives across repositories. A data model plays a critical role in our organization’s ability to create repositories and DAMS that organize data in an interoperable way, thus establishing a common understanding of how digital objects are conceived and represented across repositories, making it easier to support object migration unrestricted by application domain profiles, and creating a framework of consistent data structure for APIs.
 
We also require a framework to describe and deliver digital images and their structural metadata over the web in a standardized way for a wide variety of material, in compliance with page viewer application requirements, and in an interoperable manner. This framework should also use standardized web technology to achieve these functionalities. Data models will integrate with the image framework. 
## Metadata
Discovery and access (e.g., searching, browsing, faceting, visualization) are driven by good metadata. Good metadata is defined as being sufficient to meet the needs of users and stakeholders. We will always strive for good metadata.
Metadata in the project will be driven by UX work and service needs identified by the Product Owner and stakeholders. 
Linked data is a set of best practices for exposing, sharing, and connecting pieces of data on the web in support of more sophisticated use of that data.The application (as defined above) is linked data ready and we will explore the potential for leveraging linked data principles in support of good metadata. 
Future considerations around linked data include greater integration of an external triplestore into the DAMS infrastructure, and modeling additional entities (e.g., people) if deemed to have potential benefit for meeting documented user, Product Owner, or stakeholder needs.
## Relationship to Samvera Community
We are Samvera partners and will participate in and review community efforts in domains that relate to our implementation. For example, the Analytics Working Group is defining common use cases and principles for repository analytics, and this is likely to be helpful to us. We will be sharing our work on Jupiter as an implementation of Samvera components (and our code) with the community, emphasizing the philosophy and principles of our work and how this helps us meet our service, program and development goals as well as our timelines. 
## Continuous Integration
Our desired workflow of rapid development, testing, user testing, and revision requires a CI environment. We will also require a more clearly and properly defined staging environment and sufficient error tracking and analysis for robust production testing and monitoring. 
# Development

# Team

# FAQ
