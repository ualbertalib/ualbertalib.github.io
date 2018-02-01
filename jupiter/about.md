## Design and Development Workflow
![UserCenteredDesignDiagram](images/UCD.jpg?raw=true)
## UX/UI
User experience is at the centre of our design and development work. Our design decisions are based on defined user requirements that are clearly documented in the feature backlog prior to development work beginning. The following are used in our UX informed design process:
* <a href= "https://docs.google.com/document/d/1TAmiG5bof2UgLbvbJ8MVZbhec00qa-lGxMKKz98yQzI/edit?usp=sharing" target="_blank">UI Design Checklist</a>
* <a href= "https://docs.google.com/document/d/1zwoeTbd8YH0pJKWZ2XYROWkLhoQvkS6sBWPpJC5gMLY/edit?usp=sharing" target="_blank">Form Design Checklist</a>
* <a href= "https://docs.google.com/document/d/1mDmHSiBQ06baDJvYQszTuY3ejuvc5BxLAdTEYHtxQaw/edit?usp=sharing" target="_blank">Keyboard Testing Design Checklist</a>
* <a href= "https://jupiter.mybalsamiq.com" target="_blank">Wireframes (in Balsamiq)</a>. 
The image below is a wireframe for Jupiter's deposit page:

![DepositItemMockup](images/deposititem.png?raw=true)
## Accessibility
We commit to <a href= "https://www.w3.org/WAI/WCAG20/quickref/" target="_blank">WCAG 2.0 Level A</a> compliance for this application. Proper setup for internationalization of the application is also accounted for in the development of the application, to ensure it will work well for (or can be easily adapted for) users from any region or language as the need arises. A <a href= "https://docs.google.com/document/d/1tYmw3mn7vDEuI8uFMtXrTX3-SyB40II6OhQgHXH4O2I/edit?usp=sharing" target="_blank">Web Accessibility Design Checklist</a> was developed to embed accessibility in our design processes. 
## Security
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eget aliquet enim, non venenatis nisi. Praesent ac egestas quam, non lobortis erat. Cras venenatis tincidunt orci a eleifend. Quisque id orci purus. Vestibulum tincidunt leo id risus tristique, sed auctor purus hendrerit. Aenean ultricies justo ac leo interdum, et dictum orci interdum. Vestibulum non tortor a tortor fringilla consequat at dapibus dolor. Curabitur dolor diam, accumsan ut euismod ut, consectetur non mauris. Sed eget nulla ac odio imperdiet luctus non id nibh. Aenean tempor at mauris venenatis molestie. Morbi tincidunt, nibh nec egestas semper, tellus arcu imperdiet ligula, vel consequat tellus mauris sit amet ex. Cras viverra laoreet elit, nec consequat risus porttitor at. Donec blandit euismod felis non condimentum. Vivamus enim odio, vehicula et pulvinar quis, malesuada quis urna.
## Data Model
The Jupiter data model plays a critical role in our organization’s ability to create repositories and DAMS that organize data in an interoperable way, thus establishing a common understanding of how digital objects are conceived and represented across repositories, making it easier to support object migration unrestricted by application domain profiles, and creating a framework of consistent data structure for APIs.
![DraftSingleFileDataModelDiagram](images/draftsinglefile.png?raw=true)
## Metadata
Metadata in the project was driven by UX work and service needs identified by the Product Owner and stakeholders. Our approach id documented in detail below:
### Data Dictionary
The <a href= "https://github.com/ualbertalib/metadata/tree/master/data_dictionary" target="_blank">Data Dictionary's</a> primary purpose is to maintain a human/machine readable and up-to-date version of Jupiter’s metadata. It is powered by a triplestore containing all Jupiter metadata in Linked Data friendly format. An update process runs nightly, leveraging the power of github to create preservable documentation (readme files, json, xlsx and ntriples) and versioning control for changes in Jupiter metadata. A Flask powered web user interface enables developers and team members to update and modify metadata components.   
