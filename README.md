# The Charactor of software

## Abstraction

-   The process of eliminating details that is not relevant to the analysis in hand.
    
-   From Low Level to High Level.
    
-   In practice, achieving good abstraction is key to mastering complexity of software design.
    
-   Machine Code --> Assembler --> High-leverl Languages
    

### High-level Languages (HHL)

The natural sucessors of autocodes.

Use interpreter, compiler and virtual machine to be executed.

Emphasize what to be computed, not how it is be achieved on a specific processor.

## Design and Specification language

higher-level languages than HHL, is used to abstract and specificate system models at early development stages. It is purely for design and specification, irrelevant with how the program should be implemented.

## Software Quality

Fitness for purpose

### Correctness

The most obvious and fundamental quality, with respect to a specification.

Under the specified conditions, given the specified inputs, it should always return the specified output.

#### Error

An error is a system state that may lead to a failure. Happens at run-time.

#### Failure

A failure is a deviation of the delivered service from the specification. Happens at run-time.

#### Fault

Is the assumed cause of an error, the fault could be in the h/w, s/w or even in development process.

#### Defect

Refer to a characteristic of product that makes an error liable to occur.

### Reliability

About the probability of s/w failure occuring.

Measured by MTBF. (Mean Time Between Failures)

MTBF = MTTF(Mean Time To Failure) + MTTR(Mean Time To Repair)

Also can be meansured by POFOD (Probability of Failure on Demand)

### Safety

About the Consequences of such a failure.

Failure of s/w could lead to serious consequences for other part of system.

Safety is about to analyses the system hazards - states that can lead to a catastrophic failure.

Safety Kernel - Privilege only few functions to do the critical operations that affects safety. Everything else could only do these opreations through these functions.
