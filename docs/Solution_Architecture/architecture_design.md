# Software Architecture vs. Design

## Introduction
- **Controversial Topic:**
    - There is a debate whether software architecture and design are the same. This note explores the differences as understood by some experts, acknowledging that opinions vary widely.

## Definitions
- **Software Architecture:**
    - Concerned with the global scope of the software.
    - Focuses on componentization, communication, and the high-level structure and standardization of components.

- **Software Design:**
    - Deals with more localized scope.
    - Involves fine-tuning individual classes and implementing patterns to streamline strategies.

## Relationship Between Architecture and Design
- **Interconnectedness:**
    - According to Elemar, architecture-related activities always involve design, indicating that while all architecture involves design, not all design tasks are architectural.
- **Primary Objective of Software Architecture:**
    - To ensure that quality attributes, high-level constraints, and business goals are met by the system.
    - For instance, decisions about implementing logging or metrics system-wide are architectural.

## Design Scope
- **Non-Architectural Design Decisions:**
    - Decisions that do not impact the system's quality attributes or fulfill high-level business objectives might not be considered architectural.
    - Design choices that are internal to a component and not visible externally also fall into this category.

## Architecture vs. Design Clarification
- **Higher-Level vs. Lower-Level:**
    - Architecture is described as a higher-level overview, while design is a more detailed, lower-level activity.
- **Misconceptions and Examples:**
    - Clean Architecture, coined by Uncle Bob (Robert Martin), is often discussed in this context. While termed as an architectural pattern, many of its elements pertain more to design than architecture.

## Conclusion
- **Open for Interpretation:**
    - The distinction between architecture and design is nuanced and can vary based on individual interpretation and application.
    - It's crucial to understand that different perspectives exist, allowing professionals to form their own opinions based on their experiences and the specific contexts they are working in.
