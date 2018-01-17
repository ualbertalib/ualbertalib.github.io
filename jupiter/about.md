# Project Principles
### UX Research
User experience is at the centre of our design and development work. Our design decisions are based on defined user requirements that are clearly documented in the feature backlog prior to development work beginning.
### Accessibility Assessment
We commit to [WCAG](https://www.w3.org/WAI/WCAG20/quickref/) 2.0 level A compliance for this application. Proper setup for internationalization of the application is also accounted for in the development of the application, to ensure it will work well for (or can be easily adapted for) users from any region or language as the need arises. 
### Security Review
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eget aliquet enim, non venenatis nisi. Praesent ac egestas quam, non lobortis erat. Cras venenatis tincidunt orci a eleifend. Quisque id orci purus. Vestibulum tincidunt leo id risus tristique, sed auctor purus hendrerit. Aenean ultricies justo ac leo interdum, et dictum orci interdum. Vestibulum non tortor a tortor fringilla consequat at dapibus dolor. Curabitur dolor diam, accumsan ut euismod ut, consectetur non mauris. Sed eget nulla ac odio imperdiet luctus non id nibh. Aenean tempor at mauris venenatis molestie. Morbi tincidunt, nibh nec egestas semper, tellus arcu imperdiet ligula, vel consequat tellus mauris sit amet ex. Cras viverra laoreet elit, nec consequat risus porttitor at. Donec blandit euismod felis non condimentum. Vivamus enim odio, vehicula et pulvinar quis, malesuada quis urna.
## Data Modeling
The Jupiter data model plays a critical role in our organization’s ability to create repositories and DAMS that organize data in an interoperable way, thus establishing a common understanding of how digital objects are conceived and represented across repositories, making it easier to support object migration unrestricted by application domain profiles, and creating a framework of consistent data structure for APIs.
## Metadata
Discovery and access (e.g., searching, browsing, faceting, visualization) are driven by good metadata. Good metadata is defined as being sufficient to meet the needs of users and stakeholders. We will always strive for good metadata.
Metadata in the project will be driven by UX work and service needs identified by the Product Owner and stakeholders. 
Linked data is a set of best practices for exposing, sharing, and connecting pieces of data on the web in support of more sophisticated use of that data.The application (as defined above) is linked data ready and we will explore the potential for leveraging linked data principles in support of good metadata. 
# Development
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
### Code Review
### Unit/Integration/Performance Testing
### Proper Deployment and Production Monitoring
## Continuous Integration
Our desired workflow of rapid development, testing, user testing, and revision requires a CI environment. We will also require a more clearly and properly defined staging environment and sufficient error tracking and analysis for robust production testing and monitoring. 
### Release & Feature Documentation
## Rails
The project will use standard Rails conventions and will resist custom Rails implementations. This is necessary to ensure for effective onboarding, more sustainable future data migrations, and to reduce/mitigate technical debt inside the project. As with accessibility, if we deviate from standard Rails conversions, we will have a justified reason for doing so and the decision will be clearly documented and approved.
# Team
# FAQ 
#### What is the Relationship to Samvera Community
We are Samvera partners and will participate in and review community efforts in domains that relate to our implementation. For example, the Analytics Working Group is defining common use cases and principles for repository analytics, and this is likely to be helpful to us. We will be sharing our work on Jupiter as an implementation of Samvera components (and our code) with the community, emphasizing the philosophy and principles of our work and how this helps us meet our service, program and development goals as well as our timelines. 
