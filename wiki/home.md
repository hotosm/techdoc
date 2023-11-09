# HOT Technical Documentation Wiki
This is the Wiki for the HOT Documentation project. Here you will find guidance on creating documentation for any of the HOT projects.

Don't want to learn, just eager to dive in. Here is how you [get started](getting_started_tech_docs.md).

The landscape of documentation for HIT can be divided into two broad categories:
* [**Functional Design Documentation**](#functional-design-documentation): Describes what a solution does. 
* [**Technical Design Documentation**](#technical-design-documentation): Describes how the solution does it. Technical design documentation can be broken down into [Architecture Design Documentation](#architecture-design-documentation), [Design Documentation](#design-documentation), and [Code-Level Design-Documentation](code-level-documentation)

## Functional Design Documentation
| Area | Description | Example Types of Documentation |
|------|-------------|------------------------|
| Scoping | High-level overview of the functionality for a solution, component, or change | - Features |
| Functionality | Narrative descriptions of functionality to be delivered | - Stories<br> - Use Cases
| Interface Design | Visual assistance to ensure solution matches intent | - Wireframes<br> - "Camera Ready" Art<br> - Annotated Screenshots |
| Acceptance | Details for ensuring intent of functionality is implemented | - Requirements<br> - Acceptance Criteria |


## Technical Design Documentation

### Architecture Design Documentation
You can select the links below to learn more about each documentation type, or follow our [architecture documentation walkthrough](architecture_docs_walkthrough.md) for a step by step.
| Area | Description | Example Visual Documentation | Example Narrative Documentation |
|------|-------------|------------------------------|---------------------------------|
| Ecosystem Architecture | High-level overview of all the solutions within the HOT architecture ecosystem | - Block Diagram<br> - [Information Flow](https://wittij.com/information-flow-diagram/)| - Overlay Narrative |
| Solution Scope | Conceptual level architecture of a specific solution (e.g. Tasking Manager) | - [Solution User View](https://wittij.com/solution-user-diagram-for-rapid-scoping/)<br> - [Conceptual Architecture](https://wittij.com/conceptual-solution-architecture-diagram/)| |
| Solution Design | Logical level architecture of a specific solution (e.g. Tasking Manager) | - [Solution User View](https://wittij.com/solution-user-diagram-for-rapid-scoping/)<br> - [Conceptual Architecture](https://wittij.com/conceptual-solution-architecture-diagram/)<br> - [Information Flow](https://wittij.com/information-flow-diagram/)<br> - [Component Model](https://wittij.com/uml-component-diagram/) |- [Risks](https://wittij.com/solution-architecture-risk-register/)<br> - Assumptions<br> - [Decisions](https://wittij.com/solution-architecture-decisions/)|

### Design Documentation
| Area | Description | Example Visual Documentation | Example Narrative Documentation |
|------|-------------|------------------------------|---------------------------------|
| Data Design | Design for the data stored by a solution | - Conceptual Data Model<br> - Logical Data Model | - Data Dictionary |
| Integration Design | Designs for the integration between components of the solution | - Sequence Diagrams<br> - [Information Flow](https://wittij.com/information-flow-diagram/) | - Interface Specifications|
| Component Design | Designs for the components of the solution | - [Activity/Flow Diagrams](https://wittij.com/uml-activity-diagram/)<br> - Class Diagrams<br> - Data Design | - “Fit-for-purpose” Design |

### Code-Level Documentation
TBD
