# Exercice 1 - Definition

## What is Software Architecture?

There is no one definition to what software architecture is but the SEI (Software Engineering Institute of Carnegie Mellon University, Pittsburgh Pennsylvania) defines it as:

> The software architecture of a program or computing system is a depiction of the system that
> aids in the understanding of how the system will behave. Software architecture serves as the
> blueprint for both the system and the project developing it, defining the work assignments that
> must be carried out by design and implementation teams. 
> 
> The architecture is the primary carrier of system qualities such as performance, modifiability, 
> and security, none of which can be achieved without a unifying architectural vision. 
> 
> Architecture is an artifact for early analysis to make sure that
> a design approach will yield an acceptable system. By building effective architecture, you can
> identify design risks and mitigate them early in the development process.

TLDR:

Software architeture is the blueprint of how diffrent components interact with each other to archieve a desired goal.

Meanwhile making sure different qualiteis are archieved such as such as performance, modifiability, and security, yielding
in an acceptable system.

Effective architecture helps to identify and mitigate risks as early as possible.

## Does this contradict common agile process attitude and models?

> In most successful software projects, the expert developers working on that project have a
> shared understanding of the system design. This shared understanding is called architecture. This
> understanding includes how the system is divided into components and how the components
> interact through interfaces. These components are usually composed of smaller components, but
> the architecture only includes the components and interfaces that are understood by all the
> developers.

TLDR: 

For many projects the software architects are the expert developers working on said project.

Architecture is the shared understanding of the system design. This includes how the system is divided into
components and how they interact with each other throught interfaces. Components often are then again
divided into smaller components.

Architecture should be as simple as possible and generally understood by all developers.

## Architecture and Code

> Software architecture and coding are often seen as mutually exclusive disciplines, despite us
> referring to higher level abstractions when we talk about our software. You've probably heard
> others on your team talking about components, services and layers rather than objects when
> they're having discussions. Take a look at the codebase though. Can you clearly see these
> abstractions or does the code reflect some other structure? If so, why is there no clear mapping
> between the architecture and the code? Why do those architecture diagrams that you have on the
> wall say one thing whereas your code says another?

TLDR:

Software architecture and coding are often seen as exclusive disciplines, but when talking about
software we often reffer to "higher level abstractions" like components or services. But theese
abstractions are not always clearly visible in the codebase and sometimes eaven contradict each
other. This should not be the case, code and architecture should be mappable to each other

## Differences between traditional architecture and software architecture

> Software is not limited by physics, like buildings are. It is limited by imagination, by design, by
> organization. In short, it is limited by properties of people, not by properties of the world. We have
> met the enemy, and he is us.

TLDR:

A lot of limitations faced in traditional architecture are no limitation for software engineering.
This openes up a lot of possibilities and increases development speed, allowing you to take more risks.

## How do commitees invent?

> The basic thesis of this article is that organizations which design systems are constrained to
> produce designs which are copies of the communication structures of these organizations.

Example:

A Company with three development teams want to create a new software, there is a high chance that the
architecture of this software will have three high level components to match the structure of this
organisation and not because it makes most sense for this software.

