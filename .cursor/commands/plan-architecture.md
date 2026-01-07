# Plan Architecture

Create a comprehensive ARCHITECTURE.MD document that defines the high-level technical structure, components, and technology choices for the software project.

## INPUT

**Required Information:**

- System components and their interactions
- Data models and flow
- Technology stack with rationale
- Scale and performance requirements
- Security and compliance needs
- External integrations
- Infrastructure and deployment approach

**Reference:** See `.cursor/commands/references/architecture-guide.md` for detailed guidance on role, behavior, questions to ask, and quality standards.

## PROCESS

1. **Discovery Phase**
   - Understand technical requirements and constraints
   - Identify scale, performance, and security needs
   - Gather context on existing systems and integrations
   - Clarify team expertise and preferences

2. **Design Phase**
   - Define major system components
   - Map data flow and storage strategy
   - Identify integration points and dependencies
   - Consider scalability and security implications

3. **Technology Selection**
   - Propose technology stack with rationale
   - Explain tradeoffs of key decisions
   - Consider team capabilities and constraints
   - Address non-functional requirements

4. **Documentation**
   - Create ARCHITECTURE.MD with clear structure
   - Include diagrams or descriptions of system flow
   - Document rationale for major decisions
   - Flag risks and future considerations

## OUTPUT

Generate `ARCHITECTURE.MD` in the repository root containing:

- **System Overview**: High-level architecture description
- **Components**: Major system components and responsibilities
- **Data Architecture**: Data models, storage, and flow
- **Technology Stack**: Chosen technologies with rationale
- **APIs & Integrations**: External systems and interfaces
- **Security & Compliance**: Authentication, authorization, data protection
- **Infrastructure**: Hosting, deployment, monitoring
- **Scalability**: Performance considerations and growth plan
- **Architectural Decisions**: Key decisions with tradeoffs
- **Future Considerations**: Technical debt and evolution path

The document should be high-level, focused on structure, and clear about decision rationale.
