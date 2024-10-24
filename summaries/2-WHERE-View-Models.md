# Software Architecture: WHERE - View Models Overview

## Lecture Overview
The focus of this lecture is on the representation of software architecture using various view models, including the Kruchten 4+1 View Model. The concept of "Architecture WHERE" addresses how the architecture is depicted, how different viewpoints are utilized, and how models provide different perspectives on the same system. This helps in understanding both the overall structure and the specific components of the software architecture.

## Learning Objectives
By the end of this lecture, you should:
- Understand the essential building blocks and benefits of architecture view models.
- Recognize the relationship between architecture descriptions and view models.
- Be familiar with different view models used for different insights.
- Understand Kruchten's 4+1 view model and how to apply it to your own architecture.

## Key Topics Covered
1. **Architecture View Model**
   - An **architecture view model** standardizes the representation of software architecture. It helps answer questions like "why, what, who, when, and how" architecture is manifested in different parts of a system.
   - A **view model** is a systematic collection of **viewpoints**, types of models, and relationships among them. It defines perspectives from which views are constructed, representing the architecture for different stakeholders.
   - **Viewpoints** are used to define from which perspective a view is created, while a **view** is the outcome that you see. Viewpoints specify whose interests are being served, who is responsible for the view, and how views can be navigated and evolved.

2. **Modelling in Architecture**
   - **Modeling** is a fundamental activity in architecture. A model serves as a representation of a subject of interest, providing an abstract, smaller-scale version of the subject matter to highlight relevant details.
   - Effective models suppress irrelevant details, focus on specific purposes, and serve as tools for communication, collaboration, and insight generation.

3. **Kruchten's 4+1 View Model**
   - **Kruchten's 4+1 View Model** is one of the most recognized models in software architecture. It includes:
     - **Logical View**: Represents the system from a functional perspective, focusing on the interactions between components.
     - **Development View**: Describes the system's static structure from the developer's perspective, showcasing how code and components are organized.
     - **Process View**: Focuses on the dynamic aspects of the system, such as concurrency, synchronization, and interactions among processes.
     - **Physical View**: Represents the mapping of software components to hardware, showing the overall operational structure.
     - **Scenarios (+1)**: Scenarios illustrate specific use cases or instances of the system in action, helping validate the architecture.
   - These views together provide a comprehensive understanding of the architecture from multiple perspectives, ensuring alignment between development, implementation, and operational considerations.

4. **Logical View and Low Representational Gap (LRG)**
   - The **Logical View** represents the structure and behavior of the system’s components from a functional perspective. It is designed to have a close relationship with real-world objects to reduce the **Low Representational Gap (LRG)**.
   - LRG emphasizes minimizing the gap between real-world concepts and their representation in software. This is achieved by using object-oriented models and ensuring that the data and behavior of software entities align closely with their real-world counterparts.

5. **Development View**
   - The **Development View** focuses on the design-time structure of the system, which includes classes and their relationships.
   - This view is about implementing the logical structures in a way that allows for efficient development and maintenance, while supporting scalability and reuse. It links the **logical view** (objects and their interactions) to the implementation, using classes and their methods to achieve the required functionality.

6. **Complementary Viewpoints**
   - The lecture also discusses complementary viewpoints that help refine the overall understanding of architecture. These viewpoints include:
     - **Business vs. Technical Viewpoint**: Differentiates components that contribute directly to business outcomes from those that contribute indirectly.
     - **Baseline vs. Target Viewpoint**: Distinguishes between current architecture and future state architecture.
     - **Architecture Mode Viewpoint**: Differentiates perspectives during design-time (during implementation), run-time (during execution), and manage-time (reffers to common devops practices).

7. **Architecture Artifacts and Descriptions**
   - **Architecture artifacts** are tangible representations of architecture, such as diagrams, lists, or matrices, used to document and communicate design decisions.
   - These artifacts can represent different architecture views and facilitate controlled sharing, validation, and maintenance of architecture information across teams.

## Summary
Architecture WHERE focuses on using different view models to represent software architecture effectively. Each view provides a different perspective, allowing stakeholders to understand the system comprehensively. Kruchten’s 4+1 view model integrates multiple perspectives, making it a powerful tool for capturing both static and dynamic aspects of software systems. Understanding and using different viewpoints and representations helps ensure that the system design remains consistent, aligned with stakeholder needs, and adaptable to future requirements.

