# Software Architecture: WHY - Architecture Conditions Overview

## Lecture Overview

The focus of this lecture is on the architectural drivers and forces,
collectively known as **architecture conditions**. These conditions encompass
requirements, constraints, and assumptions that shape the architecture of a
system. Understanding these conditions helps ensure that the architecture aligns
with organizational needs and adapts to the forces acting upon it.

## Learning Objectives

By the end of this lecture, you should:

- Understand the role of conditions in the development process.
- Recognize the importance of different types of conditions and how they are
  captured.
- Assess the significance of architecture conditions.
- Understand architecture approaches and how conditions are tracked.

## Key Topics Covered

1. **Architecture Conditions**

   - **Architecture Conditions** are the motivating factors behind the design of
     a system. These conditions include **requirements**, **constraints**, and
     **assumptions** that form the basis for architectural decisions.
   - The architecture of a system is shaped by a combination of these
     conditions, balancing and responding to each as needed. To ensure that
     architecture conditions are effective, they must be:
     - **Correct**: Stakeholders must validate that conditions are accurate.
     - **Feasible**: Conditions must be achievable given the available
       resources.
     - **Unambiguous**: Conditions must be clearly formulated, leaving no room
       for multiple interpretations.
     - **Verifiable**: Conditions must be measurable and testable to confirm
       they are met.

2. **Types of Conditions**

   - **Requirements**: These represent the needs of the organization and are
     divided into two categories:
     - **Functional Requirements**: Existential needs that define what the
       system should do, such as specific features or behaviors.
     - **Non-functional Requirements**: Define how the system should operate,
       covering aspects like performance, reliability, and usability.
   - **Constraints**: Represent factors that cannot be ignored and must be
     adhered to, such as budget limitations, time constraints, or specific
     technology requirements.
   - **Assumptions**: Reflect uncertainties that may or may not occur but are
     taken into account for planning purposes. These are often considered "known
     unknowns" that require monitoring as the project progresses.

3. **Capturing Conditions**

   - **Use Cases** are used to capture **functional requirements**, detailing
     the needs that the system must fulfill in response to a problem.
   - **Quality Attribute Scenarios** capture **non-functional requirements**,
     **constraints**, and **assumptions**. These scenarios describe the desired
     qualities of the system, such as response times or security levels.

4. **Architecture-Significance**

   - Not all conditions are equally significant from an architectural
     perspective. Understanding which conditions have a major impact on the
     system's design is crucial.
   - **Grady Booch** defined architecture as “the set of significant design
     decisions that shape a system, where significance is measured by the cost
     of change.”
   - **Heuristics for Determining Architecture-Significance** include:
     - **Number of Impacts**: The greater the number of decisions influenced by
       a condition, the more significant it is.
     - **Stakeholder Importance**: Conditions presented by key stakeholders,
       especially business stakeholders, are often highly significant.
     - **Non-functional Nature**: Non-functional conditions like performance,
       security, or availability are usually highly significant.
     - **Novelty**: Unusual or new conditions are more likely to be significant.
     - **Volatility**: Conditions that are expected to change frequently place
       high demands on system flexibility and are therefore significant.
     - **Degree of Conflict**: Conditions that require compromises or trade-offs
       are more architecturally significant.
     - **Strategic Orientation**: Conditions contributing directly to achieving
       strategic enterprise goals are highly significant.

5. **Architecture Approaches**

   - An **architecture approach** represents a part of the solution
     architecture, addressing a subset of the conditions identified. These
     approaches are designed to handle specific requirements, constraints, or
     assumptions.
   - Architecture approaches are also known as **solution design segments** or
     **microarchitectures** and can be described as **partial solutions** that,
     when combined, contribute to the overall system architecture.
   - Architecture approaches provide traceability between architecture
     conditions and design decisions, ensuring that all conditions are addressed
     systematically.

6. **Examples of Architecture Approaches**
   - Consider a web application requiring user authentication. The architecture
     approach may specify the use of an LDAP-based authentication provider
     integrated into an application server. This approach would include static
     and dynamic designs, defining how users interact with the system and how
     authentication is performed.

## Summary

Architecture WHY focuses on understanding the underlying conditions that drive
architectural decisions. These conditions include requirements, constraints, and
assumptions, each playing a crucial role in shaping the system. By understanding
the significance of these conditions, architects can design solutions that meet
organizational needs while maintaining alignment with business objectives.
Architecture approaches help ensure that all these conditions are systematically
addressed, providing traceability and ensuring the completeness of the
architecture.
