# Software Architecture: WITH WHAT - Architectural Means Overview

### Lecture Overview

This lecture focuses on the tools and techniques that architects use in
planning, developing, and operating software architectures. The concept of
**Architecture WITH WHAT** refers to the architect's toolbox, comprising a broad
range of architectural means, including principles, concepts, tactics, styles,
and reference architectures. This overview provides insights into what resources
architects have at their disposal and how these resources influence the
architectural design process.

### Learning Objectives

By the end of this lecture, you should:

- Have an overview of the architect's toolbox.
- Understand the classification of different architectural tools and their
  structure.
- Know some of the tools available to architects, providing orientation for
  future, in-depth lectures.

### Key Topics Covered

1. **Architecture Means**

   - **Architecture Means** are the resources that influence the development of
     an architecture, ranging from **principles** to **reference
     architectures**. The influence of these means increases as we progress from
     fundamental principles up to complex reference architectures.
   - The different types of architecture means include:
     - **Principles**: Guidelines for developing or modifying architecture.
     - **Basic Concepts**: Essential paradigms like modularity and component
       orientation.
     - **Tactics, Styles, and Patterns**: Standard approaches to solve recurring
       problems.
     - **Basic Architectures**: Foundational architectural styles used in
       various systems.
     - **Reference Architectures**: General architectural solutions for specific
       problem domains.

2. **Architecture Principles**

   - **Architecture Principles** provide proven guidelines to help design
     software architectures. They guide architects to create systems that meet
     their requirements effectively.
   - Examples of important architecture principles include:
     - **Modularity**: Breaking down a system into smaller, self-contained
       parts.
     - **Loose Coupling**: Reducing dependencies between components to
       facilitate flexibility and change.
     - **Separation of Concerns**: Dividing a system into distinct features that
       overlap as little as possible.
     - **Abstraction**: Simplifying complex systems by focusing on higher-level
       representations.

3. **Basic Architecture Concepts**

   - The **Basic Concepts** section includes foundational paradigms such as:
     - **Procedural Approaches**: Decomposing algorithms into smaller,
       repeatable procedures.
     - **Object Orientation**: Bundling data with related procedures (methods),
       following principles like information hiding and modularity.
     - **Component Orientation**: Building systems from reusable, self-contained
       components, providing modularity at a larger scale than objects.
     - **Model-Driven Development (MDD)**: Using models as central artifacts for
       system creation, allowing automation in software generation.
     - **Aspect Orientation**: Handling cross-cutting concerns like security in
       a modular manner.

4. **Architecture Tactics, Styles, and Patterns**

   - **Tactics** are guidelines that help achieve specific quality attributes
     like performance or security in a system.
   - **Architecture Styles** describe recurring structural organizations of
     systems, such as:
     - **Layered Architecture**: Grouping similar functionalities in layers
       where each layer depends on the layer beneath it.
     - **Client-Server Architecture**: A request-response model where clients
       request services from servers.
     - **Publish-Subscribe Architecture**: Decoupling event producers and
       consumers.
   - **Patterns** provide common solutions to typical design challenges, with
     examples such as:
     - **Composite Pattern**: Used for creating tree-like structures to
       represent hierarchies.
     - **Chain of Responsibility Pattern**: Used to pass requests along a chain
       of handlers.

5. **Basic Architectures**

   - **Basic Architectures** represent foundational architectural approaches
     that are widely adopted, such as:
     - **Layered Architecture**: Divides a system into distinct layers for
       better separation of responsibilities.
     - **N-tier Architecture**: Distributes system components across different
       hardware layers, often for scalability.
     - **Peer-to-Peer Architecture**: A distributed model where each node (peer)
       can both provide and consume services.
     - **Middleware**: Platforms that provide application services, facilitating
       the complexities of distributed environments.

6. **Reference Architectures**
   - **Reference Architectures** combine general architectural knowledge with
     specific domain requirements to create a coherent solution for particular
     contexts.
   - These architectures document the structure of a system, the key building
     blocks, and how they interact, providing a reusable template for future
     projects.
   - Examples include the IBM business automation and workflow management
     reference architectures.

### Summary

Architecture WITH WHAT highlights the wide range of tools and techniques
available to software architects, from fundamental principles to comprehensive
reference architectures. By understanding and leveraging these tools
effectively, architects can design well-structured, maintainable, and adaptable
systems that meet their organizational needs. The toolbox allows architects to
select appropriate means to address specific challenges and create value through
well-designed architectural solutions.
