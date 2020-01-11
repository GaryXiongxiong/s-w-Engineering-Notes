# The Charactor of software

## Abstraction

-   The process of eliminating details that is not relevant to the analysis in hand.
    
-   From Low Level to High Level.
    
-   In practice, achieving good abstraction is key to mastering complexity of software design.
    
-   Machine Code --> Assembler --> High-level Languages
    

### High-level Languages (HHL)

-   The natural successors of autocodes.
    
-   Use interpreter, compiler and virtual machine to be executed.
    
-   Emphasize what to be computed, not how it is be achieved on a specific processor.
    

## Design and Specification language

-   higher-level languages than HHL, is used to abstract and specificate system models at early development stages. It is purely for design and specification, irrelevant with how the program should be implemented.

## Software Quality

-   Fitness for purpose

### Correctness

-   The most obvious and fundamental quality, with respect to a specification.
    
-   Under the specified conditions, given the specified inputs, it should always return the specified output.
    

#### Error

-   An error is a system state that may lead to a failure. Happens at run-time.

#### Failure

-   A failure is a deviation of the delivered service from the specification. Happens at run-time.

#### Fault

-   Is the assumed cause of an error, the fault could be in the h/w, s/w or even in development process.

#### Defect

-   Refer to a characteristic of product that makes an error liable to occur.

### Reliability

-   About the probability of s/w failure occurring.
    
-   Measured by MTBF. (Mean Time Between Failures)
    
-   $MTBF = MTTF(Mean Time To Failure) + MTTR(Mean Time To Repair)$
    
-   Also can be meansured by POFOD (Probability of Failure on Demand)
    

### Safety

-   About the Consequences of such a failure.
    
-   Failure of s/w could lead to serious consequences for other part of system.
    
-   Safety is about to analyses the system hazards - states that can lead to a catastrophic failure.
    
-   Safety Kernel - Privilege only few functions to do the critical operations that affects safety. Everything else could only do these opreations through these functions.
    

# Managing Development Process

## Project Management

-   Concerned with activities involved in ensuring that software is delivered on time and on budget and in accordance with the requirements of the organisations developing and procuring the software.
    
-   Needed because the software is always subject to budget and schedule constraints that are set by the organisation developing the software
    
-   Focus on 4P:
    
    -   People
        
    -   Product
        
    -   Process
        
    -   Project
        

## Software Process and Project Metrics

-   Why Measure?
    
    -   To characterize, to understand current situation and use baseline to compare with future assessment.
        
    -   To evaluate, to determine status with respect to plans.
        
    -   To predict, to build relationship among processes and products for future planning.
        
    -   To improve, to identify problem areas and measure improvement.
        
-   What can we measure?
    
    -   Processes
        
    -   Products
        
    -   Resources
        

### Process Metrics

-   Gain insight into efficacy of existing process
    
-   Metrics collected across all projects (Based on outcome from the process)
    
    -   Errors uncovered at different stages Defects reported by users
        
    -   Human effort
        
    -   Time expanded
        
    -   Schedule Conformance
        
-   Lead to process improvement
    
    -   Understand existing process
        
    -   Introduce process changes to achieve organisational objectives
        
    -   Check efforts of changes
        
    -   Adjust process changes
        
    -   Revisit organisational objectives
        

### Projects Metrics

-   Assess status of on-going project
    
    -   Use metrics from past projects to make estimations for on-going project
-   Track potential risks
    
-   Uncover problem areas
    
-   Adjust plans
    

### Product Metrics

-   Gain insight of quality of product
    
-   Metrics collected across various parts
    
    -   Quality, Depends on:
        
        -   The requirements produced for it
            
        -   The design that models the solution
            
        -   The code that leads to its executable
            
        -   The tests applied to uncover errors
            
    -   Complexity
        
    -   Efficiency
        
    -   Reliability
        
    -   Maintainability
        
-   Support risk analysis and various decisions
    
    -   Used to derive further project metrics

## Software Project Planning

-   Estimation to be made before project start:
    
    -   Work to be done
        
    -   Resources that will be required
        
    -   Time that will elapse from start to finish
        
-   Process and project metrics provide historical data
    
-   Techniques for time and effort estimation exist
    

### Software scope

-   First activity in software planning
    
-   Describes:
    
    -   Functions to be delivered to user
        
    -   Data to be processed
        
    -   Bounds of the system
        
-   Based on information gathered during initial interview
    
-   Defined as narrative description or a set of use cases
    

### Estimation of Resources

-   Second activity in software planning
    
-   Reusable assets can reduce cost and schedule, and improve quality
    
-   Each resource specified by:
    
    -   Description
        
    -   Statement of availability
        
    -   When the resource will be required
        
    -   Duration that the resource will be required for
        
-   Options to achieve reliable estimates:
    
    -   Delay estimation
        
    -   Base on similar project that have been completed
        
    -   Use Decomposition techniques (e.g. Sizing)
        
    -   Use empirical models (Calculated by size)
        

## Risk Analysis and Management

### Main Concerns

-   The future: What risks might cause problems to the project?
    
-   Changes: How will changes affect timeliness, quality and overall success?
    
-   Dealing with choices: What methods and tools should we use? How many peorple should be involved? What solutions are best?
    

### Reactive risk strategies

### Proactive risk strategies

-   Begins before the technical work
    
-   Potential risks are identified
    
-   Risk's probability and impact are assessed
    
-   Plan for managing risks
    
-   Monitor risks
    
-   Continuously reassess for potential risks
    

### Risk Identification

-   Systematic attempt to specify threats to the project plan
    
-   Generic risks
    
    -   Potential threat to every software project
        
    -   Supported by standard check lists
        
-   Product-specific risks
    

### Sample Generic risks check list:

-   Have top software and customer managers formally committed to support the project?
    
-   Are end-user enthusiastically committed to the project and the system/product to be built?
    
-   Are requirements fully understood by the software engineering team?
    
-   Have customers been involved fully in definition of requirements?
    
-   Do end-user have realistic expectations?
    
-   Is the project scope stable?
    
-   Does the software engineer team have the right mix of skills?
    
-   Are the project requirements stable?
    
-   Does the project team have experience with the technology to be implemented?
    
-   Is the number of people on the project team adequate to do the job?
    
-   Do all customer/user constituencies agree on the importance of the project and on the requirements for the system/product to be built?
    

### Risk estimation

-   Rate each risk with respect to:
    
    -   Probability
        
    -   Impact
        

### Risk Table

-   Simple technique to support risk management
    
-   Steps:
    
    -   For each risk associate its probability of the occurrence and impact
        
    -   Sort the table by probability and impact
        
    -   Define cut-off line for risk management
        
    -   Re-evaluate risks below the cut-off line promoting items as needed
        
    -   Everything above the cut-off line will be given attention
        

### Risk Mitigation

-   Strategy for avoiding avoidable risks

### Risk Monitoring

-   Monitor factor that may provide an indication of whether the risk is becoming more or less likely

### Risk Management and Contingency Plan

-   Assumes that mitigation efforts failed and that the risk has become reality
    
-   Proposes a set of actions to be taken
    

## Configuration Management

Software development process produces 3 categories of output:

-   Software (source or executable)
    
-   Items which describe the software (Technical and user documentation)
    
-   Data (Internal and external to program)
    

All these outputs form the software configuration

### Baselines and change control

-   Change need to be controlled, without impeding justifiable change
    
-   A **baseline** is:
    
    -   A specification or product that has been formally reviewed and agreed upon, that thereafter serves as the basis for further development, and can be changed only through formal change control procedures
-   Changes can be made to software configuration item easily before they have become base-lined
    

## Project Scheduling and Tracking

### Basic project scheduling principles

-   Compartmentalisation - define distinct and manageable tasks
    
-   Interdependency - determine what task must occur in sequence, what may be done in parallel
    
-   Time allocation - allocate person days to each task, with start and end date
    
-   Effort validation - check that sufficient resource is allocated for the effort required
    
-   Defined responsibilities - allocated each task to specific person
    
-   Defined outcomes - ensure that every task scheduled has defined outcome
    
-   Defined milestones - every task should be associate with a mile stone
    

### Task network

-   Graphic representation of task flow for the project
    
-   Identify those tasks that can be undertaken in parallel, intertask dependecies.
    
-   Critical path: tasks on the critical path must be completed on schedule if the whole project is to be completed on schedule.
    

# Development Activities & Process Model

## Stages of software development

### Requirements Analysis

-   Requirements: what end user/customer actually wants
    
-   Often imprecisely stated in non-computing terms
    
-   Role of system analyst to understand these requirements, to evolve them, and prepare to translate requirements into specification
    
-   Involve investigating and describing the problem domain and requirements
    

### Software Specification

-   Used to direct creation of software
    
-   Is about to describing the new system-to-be
    
-   States exactly what the system to be delivered must do
    
-   Uses computer-related terminology
    
-   Can be a document, set of models, formal mathematical model, collection of usage scenarios, prototype...
    
-   Should be agreed upon by customer and developer, documented, and ideally frozen before development starts
    
-   Involves the characteristic for a solution system that will meet the requirements
    
-   Sometimes viewed as a separate phase of the developments process, but often merged with requirements engineering
    

### Software Design

-   Translate specification into solutions
    
-   First breakdown of specification moving towards implementable pieces
    
-   Provide "Blueprints" for subsequent implementation
    

### Implementation

-   Translates design blueprints into programs
    
-   Translates design into a program and remove errors from that program
    
-   Could also be called programming and debugging
    
-   Programming and debugging are usually interleaved activities
    

### Testing

-   Checking all of the parts of the software system together to make sure they work individually and together, and satisfy the specification
    
-   Involves executing the system with test cases that are derived from the specification of the real data to be processed by the system
    
-   Tests are normally planned out in advance, with carefully selected test data
    

### Quality Assurance

-   Quality assurance: an on-going process
    
-   Ensures that the processes and products meet their quality expectations
    

### Documentation

-   Should be on-going process
    
-   User manual, training material, maintenance manuals, ...
    

### Acceptance Test and Delivery

-   Customer test of delivered system
    
-   If acceptable, you may get final payment for the work
    
-   Not end of the project
    

### Maintenance and Evolution

-   Rarely is a system delivered, paid for and then left alone
    
-   Usually accounts for major portion of a system's lifecycle costs
    
-   Activities:
    
    -   Fixes bugs
    -   Adds features
    -   Adapts to changes
    -   May require changes to more than on type of asset
    -   Does eventually lead into the retirement of the system
    -   Software Releases are the mechanism by which supplier get new versions of a software system to customers
        -   Minor releases
            -   1.0-1.1
        -   Major releases
            -   1.1-2.0
-   Why cost so high?
    
    -   Fixing and refactoring existing system

### Throw It Away

-   When no longer economic to maintain the system have huge impact on time
-   New features and requirements may be added, that will involve a whole engineer process
-   Original development team may leave of be changed

## Software Decay

-   Caused by:
    
    -   User fault when using system
        
    -   Maintained by new development team
        
    -   Increased complexity when evolution
        
    -   New bugs created when fix existing bugs
        
-   Refactoring can resolve the problem
    
-   Refactoring involves re-imposing a new, useful design on the new version of code
    

## The Software Process

-   All activities a project may need to complete
    
-   Activities vary depending on the organisation and the type of system being developed
    
-   Must be explicitly modeled if it is to be managed well
    

## Software Process Models

-   A simplified representation of software process, presented from a specific perspective:
    
    -   Workflow perspective - sequence of activities
        
    -   Data-flow perspective - information flow
        
    -   Role/action perspective - who does what?
        

### Waterfall Model

Document-driven

-   Stages proceed in well-defined order. Next stage not commenced until previous stage completed.
    
-   Feedback generally only to previous stage, except for maintenance and evolution
    
-   Documentation usually required to evaluate a stage's completion
    
-   Advantages:
    
    -   Easy for team to understand with clear documentation
        
    -   Easy for management, it is clear that which stage the project is at, and what should be the next stage
        
    -   Requirements are agreed upon in the first stage, so planning and scheduling is simple and clear
        
    -   Easy to measure the progress by using phases and milestone
        
-   Disadvantages:
    
    -   Sometimes clients don't know what they really want
        
    -   Heavy emphasis on documentation, which would cost much time
        
    -   Clients can only understand the product through document indirectly, so that the final product may not be what the clients want
        
    -   Ignores mid-process User/Client feedback or Requirements changes
        
    -   Delayed testing period
        
-   Type of projects:
    
    -   Requirements are very clear and Client exactly know what they want

### Throw-Away Prototyping Model

-   A prototype is a working model of part or all of the final system
    
-   A prototype may be:
    
    -   Inefficient
        
    -   Not secure
        
    -   Less functionality
        
-   Throw-Away prototyping model:
    
    -   Use to elicit and clarify the system requirements
        
    -   Start with poorly understood requirements
        
-   Advantages:
    
    -   Helpful to gather requirements from user when they don't exactly know what they want
        
    -   User can provide feedback based on prototyping before project is developed
        
    -   High amount of users involvement
        
-   Disadvantages:
    
    -   Prototyping will cost much effort
        
    -   User may be satisfied with the prototype and misunderstand that it is the final product
        
-   Types of projects:
    
    -   poorly understood requirements
        
    -   Small and medium project
        

### Evolutionary Prototyping Model

-   A prototype is a working model of part or all of the final system
    
-   A prototype may be:
    
    -   Inefficient
        
    -   Not secure
        
    -   Less functionality
        
-   Evolutionary prototyping model:
    
    -   Work with customers and evolve a final system from an initial outline specification
        
    -   Start with well understood requirements
        
    -   Specification and development is interleaved
        
    -   Prototype typically the user interface, but may be any high-risk area of system
        
-   Advantages:
    
    -   High amount of user involvement
        
    -   Specification and development is interleave so that user could give feedback to improve the project during the development progress
        
    -   Prototyping high-risk area could identify risks at an early stage of process
        
-   Disadvantages:
    
    -   High time cost for client involvement
        
    -   Prototyping may cost much effort
        
-   Types of projects:
    
    -   Well understood requirements
        
    -   Small and medium project
        

### Spiral Model

Risk-driven

-   Process is represent by a spiral rather than a sequence of activities with backtracking
    
-   Each loop in the spiral represents a phase in the process
    
-   No fixed phases - loop in the spiral are chosen depending on what is required
    
-   Doesn't necessarily end with code delivery
    
-   Risk are explicitly assessed and resolved throughout the process
    
-   Sectors:
    
    -   Objective setting
        
    -   Risk assessment and reduction
        
    -   Development and validation
        
    -   Planning
        
-   Advantages:
    
    -   It is flexible that this model can be combined with other models
        
    -   Risk can be identify throughout the process so that it would be assessed and resolved on time
        
    -   It will get feedback in each phase so the feedback will be plenty
        
    -   Requirements can be captured more accurately
        
-   Disadvantages:
    
    -   There will be a lot of planning and management to do
        
    -   It will combine with other models so that may involve in disadvantages of other models
        
    -   High time cost to communicate with client
        
-   Types of projects:
    
    -   Client aren't sure what they want
        
    -   Developers don't know which model to use
        

### Agile Process Model

-   Focus on simplicity
    
-   Emphasise early and frequent delivery of software
    
-   Accept changing requirements, even in late development
    
-   Daily interaction with users
    
-   Reflect on product performance regularly and make improvements
    
-   eXtreme Programming(XP):
    
    -   Incremental development
        
    -   Four activities: Planning, Design, coding, testing
        
    -   Very short development cycles (Sprints)
        
    -   Sprints start with user stories. Each story describes functionality to be added in this Sprint.
        
    -   Each sprint should take <=3 weeks to complete
        
    -   Stories are ranked by users and developers and some are chosen at the start of each sprint
        
    -   A sprint starts with test cases written for the stories
        
    -   The sprint ends with a code delivery to clients
        
    -   The team track project velocity
        
    -   Very little documentation produced
        
    -   Design is seen as mutable
        
-   Advantages:
    
    -   Adequate involvement with client
        
    -   Acceptance of requirement changing even in late development
        
    -   Client can directly see produced product after each sprint
        
    -   Flexibility
        
    -   Suitable for mutable requirements
        
-   Disadvantages:
    
    -   Lack of documentation - a very high individual dependency
        
    -   Transfer of project to new team or new developer could be tough without adequate documentation
        
    -   Lack of long-term planning
        
    -   High time cost on customer interaction
        
-   Types of projects:
    
    -   Unstable requirements
        
    -   Ambiguous requirements - customers don't know what they really want
        
    -   Small and simple project
        

### Formal System Development

Specialist process model

-   Based on the transformation of a mathematical specification through different representations to an executable program
    
-   Transformations are 'Correctness-preserving' so it is straightforward to show that the program conform to its specification
    
-   Embodied in the 'Cleanroom' approach to software development
    
-   Advantages:
    
    -   High degree of quality assurance
        
    -   Test is straight forward
        
-   Disadvantages:
    
    -   If requirements are vague, that will make specification vary hard
-   Types of projects:
    
    -   Project with critical component

### Component-based Development

-   Based on systematic reuse where system are integrated from existing components or COTS systems
    
-   Process stages:
    
    -   Components analysis
        
    -   Requirements modification
        
    -   System design with reuse
        
    -   Development and integration
        
-   Advantages:
    
    -   Cost saving with reuse of existing components
        
    -   Inherit qualities from reused components
        
-   Disadvantages:
    
    -   Cost of COTS may be out of control
        
    -   Components which fits requirements may not be found
        
-   Types of projects:
    
    -   Project which could use COTS to simplify

### Software Product Line Development

-   Based on systematic reuse where planning and development for more than one system takes place while sharing consideration amount of assets
    
-   Types of lifecycles
    
    -   Infrastructure
        
    -   Individual products
        
-   Main processes
    
    -   Infrastructure
        
    -   Individual products
        
    -   Planning and management
        
-   Deployment phases
    
    -   Creation
        
    -   Exploitation
        
    -   Evolution
        
-   Advantages:
    
    -   Cost-saving with reuse of existing components
        
    -   Inherit qualities from reused components
        
    -   Existing components were wrote by same group so they know how they work
        
-   Disadvantages:
    
    -   High degree of management and coordination is needed
        
    -   There may not be suitable reusable component
        
-   Types of projects:
    
    -   Organisation who has big database of existing models

# Requirements Engineering and Analysis

The process of finding out, analysing, documenting and checking the needs and conditions to meet for a new or altered product.

## Activities

### Elicitation/domain understanding

-   The strengths and weaknesses of the system-as-is; stakeholders; glossary of terms
    
-   Opportunities for improvment in system-to-be; system boundaries; domain properties and assumptions; constraints; requirements for software-to-be
    
-   Techniques:
    
    -   Interview stakeholders
        
    -   Study documents
        
    -   Observe System-as-is
        
    -   Conduct scenarios
        
    -   Build prototype
        

### Evaluation/aggreement

-   Conflicts between multiple viewpoints and expectations; risk assessment
    
-   Techniques:
    
    -   Prioritise requirements to resolve conflicts
        
    -   Draw up risk checklists
        
    -   Assess likelihood and impact of risks
        
    -   Identify countermeasures
        

### Specification/documentation

-   Draw up Requirements Document
    
-   Define objectives, requirements (system and software), domain properties, assumptions
    
-   Techniques:
    
    -   Structured natural language
        
    -   Structral and behavioural models
        

### Quality Assurance/Consolidation

-   Analyse and validate Requirements Document; verify internal consistency; Identify and remove errors
    
-   Produce consolidated requirements document, protoytypes, test data, development plan
    
-   Used as contract with customer, developer and other stakeholders: must be comprehensible
    
-   Techniques:
    
    -   Validation via prototype or mock-up (to check correct understanding of stakeholder needs)
        
    -   Verification by inspection
        
    -   Model simulation
        

## Different types of requirements

### System requirement

-   A prescriptive statement to be enforced by the software-to-be, often with other system components
    
-   Must be understood by all stakeholders, described in shared vocabulary
    

### Software requirement

-   A precriptive statement to be enforced by the software-to-be alone
    
-   Must be understood by developers, described in terms of software variables
    

### Domain property

-   A descriptive statement about the problem world, regardless of how the system behaves
    

### Assumption

-   A (normally prescriptive) statement about the environment
    

### Definition

-   A precise, unambiguous and agreed meaning for concepts
    

## Requirements categories

### Functional requirements

The services the software-to-be will provide, address "WHAT" questions. May refer to external environment. Should be complete and consistent.

### Non-Functional Requirements

Typically address "HOW WELL" questions. Constraints on the way the software should satisfy functional requirements, or how it should be developed.

Types of Non-Functional requirements:

-   Quality
    
-   Interface
    
-   Compliance
    
-   Architectural constraints
    
-   Development constraints
    

# Universal Modelling Language

## Object Oriented Modeling

A system model is termed object-oriented if:

1.  It is composed of objects;
    
2.  Objects may be grouped into classes on the basis of common characteristics;
    
3.  Characteristics may be inherited by all the objects of a class;
    
4.  Objects may communicate with other objects by invoking operations
    

### Objects

An object is an encapsulated structural unit consisting of local data and operations that can access and modify attributes.

-   Encapsulations means that access to internal data can only be accomplished through the published operations
    
-   Attributes traits which make up an item
    
-   Operations actions which can be done
    

### Classes

-   A class defines a collection of objects sharing common data and operations
    
-   Class descriptions serve as templates for building new objects of each class
    
-   Objects are sometimes referred to as instances of specific classes
    

### Inheritance

-   Sub-class attributes are the same as those of the super-class with additions
    
-   Sub-class operations are the same as the super-class operations with additions
    
-   Objects in the sub-class are also in the super-class
    

## Use cases

Use cases are used to model the agents and interactions with the proposed system: helps to determine the range of service that the system must supply

-   Actor: anything that communicates with the system needs help from to achieve the goal
    
-   Primary actor: who has a goal for the system to satisfy
    
-   Secondary actors: these are actors that system needs help from to achieve the goal.
    

## Class Diagrams

Class diagrams are used to model the units of data and functionality in system, Class diagrams show:

-   Data and functionality
    
-   The architectural elements are the classes and the two kind of static relationship: Associations and subtypes
    

### Associations

Represent relationships between instances of classes. Each associations has two roles, each from source to target

### Attributes

The properties of objects in a particular class

### Operations

The processes that objects in a particular class can carry out

## Activity Diagrams

Are used to model control flow

### Sequence Diagrams

Are used to model particular scenarios for use cases

# Validation & Verification

## Validation

The process of comparing two results

In this process, we need to compare the representation of a conceptual model to the real system. If the comparison is true, then it is valid, else invalid.

## Verification

The process of comparing two or more results to ensure its accuracy.

In this process, we have to compare the model's implementation and its associated data with the developer's conceptual description and specifications.

## Testing Process

```flowchart
U=>operation: Unit TestM=>operation: Module TestSS=>operation: Subsystem TestS=>operation: System TestA=>operation: Acceptance TestU->M->SS->S->A

```

## White-box Testing

-   Structural Testing
    
-   Use partitioning criteria based on the module's internal structure
    
-   Tests what the program does
    
-   Implementation-based testing
    
-   The specification is ignored
    
-   Assertions should be used abundantly by the s/w developer to express their expectations in the code
    
-   Code instrumentation automatically adds assertions for common error types
    
-   Dynamic program analyser are used to add monitoring code to a program- they can identify the parts of the code that have been exercised by the test set
    
-   Common partitioning criteria:
    
    -   Statement coverage
        
    -   Edge coverage
        
    -   Path coverage
        

## Black-box Testing

-   Functional Testing
    
-   Use partitioning criteria based on the module's specification
    
-   Tests what the program is supposed to do
    
-   Specification-based testing
    
-   Domain is partitioned accroding to the specification.
