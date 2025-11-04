# Agentic AI Starter Kit

A comprehensive template repository for organizing AI-assisted development workflows. This starter kit provides a structured approach to collaborating with AI agents through well-defined personas, guidelines, and standards.

## Overview

The Agentic AI Starter Kit helps teams establish a **single source of truth** for both human and AI contributors. It provides templates and organizational structures that enable seamless collaboration between developers and AI agents like GitHub Copilot.

### Key Features

- **AGENTS.md Framework**: Living document that serves as the single point of truth for all contributors
- **Persona System**: Pre-defined roles (Architecture, Development, Bugfixing, Design, Refactoring) for focused collaboration
- **Guidelines & Standards**: Organized templates for architecture, security, and product vision
- **Agent OS Preview**: Structured approach to specs, product management, and coding standards
- **Templates**: Ready-to-use templates for documentation and project organization

## Repository Structure

```
.
├── AGENTS.md              # Template for team coordination and AI guidance
├── guidelines/            # Long-lived standards and decision records
│   ├── architecture/      # Structural principles and patterns
│   ├── product_vision/    # Product narrative and positioning
│   └── security/          # Security policies and controls
├── agent-os-preview/      # Agent OS integration examples
│   ├── product/          # Mission, roadmap, and tech stack
│   ├── specs/            # Feature specifications and tasks
│   └── standards/        # Backend and frontend coding standards
├── README_template.md     # Template for creating project READMEs
├── CHANGELOG.md          # Track notable updates
└── TODO.md               # Action items for contributors
```

## Getting Started

### Prerequisites

- Git for version control
- An AI assistant (e.g., GitHub Copilot, Agent OS)
- Your project's preferred development environment

### Quick Start

1. **Use this template** to create a new repository:
   ```sh
   # On GitHub, click "Use this template" button
   # Or clone this repository
   git clone https://github.com/StefanSpiess/agentic-ai-starter-kit.git
   cd agentic-ai-starter-kit
   ```

2. **Customize AGENTS.md** for your project:
   - Fill in your repository's purpose and main components
   - Define team roles and personas
   - Link to relevant guidelines

3. **Configure guidelines**:
   - Navigate to `guidelines/` subfolders
   - Copy template files and adapt them to your project
   - Document architectural decisions, security policies, and product vision

4. **Set up Agent OS structure** (optional):
   - Use `agent-os-preview/` as a reference
   - Define your product mission and roadmap
   - Establish coding standards for your tech stack

5. **Create your project README**:
   - Use `README_template.md` as a starting point
   - Replace this README with project-specific content

## How to Use

### For Human Contributors

- **Start with AGENTS.md**: Review this file to understand the project's structure and conventions
- **Follow Guidelines**: Reference the `/guidelines` folder for architecture, security, and product decisions
- **Document Changes**: Update CHANGELOG.md and AGENTS.md as the project evolves
- **Use Personas**: Adopt the appropriate persona when working on specific aspects (e.g., Architecture, Development)

### For AI Agents

- **Read AGENTS.md First**: This is your primary source of truth for the repository
- **Follow Established Patterns**: Adhere to the guidelines and standards defined in the repository
- **Respect Personas**: Understand your assigned role and stay within its scope
- **Keep Context Clean**: Regular refactoring keeps AI quality high by reducing noise

## Contributing

This starter kit welcomes contributions! Here's how to get involved:

1. **File an Issue**: Propose improvements or report problems
2. **Submit a Pull Request**: Share your enhancements to templates or documentation
3. **Follow the TODO**: Check `TODO.md` for planned improvements
4. **Maintain Quality**: Keep documentation up-to-date and well-organized

### Contribution Guidelines

- Treat `AGENTS.md` as the living source of truth
- Organize documentation to support both human and AI collaboration
- Schedule regular cleanups to prevent context from becoming noisy
- Update the CHANGELOG.md with notable changes

## Project Philosophy

This starter kit is built on these principles:

1. **AI-First Collaboration**: Structure your repository to work seamlessly with AI agents
2. **Single Source of Truth**: AGENTS.md guides all contributors
3. **Clarity Over Complexity**: Simple, well-organized documentation is key
4. **Living Documentation**: Continuously update as the project evolves
5. **Clean Context**: AI quality erodes with noise—regular refactoring is essential

## Technology Stack

The starter kit is framework-agnostic but includes examples for:

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, PostgreSQL
- **AI/Automation**: GitHub Copilot, Agent OS
- **CI/CD**: GitHub Actions

Adapt these to match your project's needs.

## Roadmap

- **Q4 2025**: Integrate Agent OS 3-layer context system, launch spec-driven development workflow
- **Q1 2026**: Expand AI agent capabilities, improve onboarding and documentation

See `agent-os-preview/product/roadmap.md` for more details.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Copyright (c) 2025 Stefan Spiess

## Acknowledgments

Built to enable seamless collaboration between human developers and AI agents. Special thanks to the GitHub Copilot team and the broader AI-assisted development community.

## Support

For questions, issues, or discussions:
- Open an issue in this repository
- Review the TODO.md for planned improvements
- Check CHANGELOG.md for recent updates

---

**Ready to start?** Begin by customizing `AGENTS.md` for your project, then dive into the guidelines and templates provided!
