# Contributing to Pryszm

Thank you for your interest in contributing to Pryszm! We're building the future of conversational infrastructure and welcome contributions from developers, business experts, and organizations who understand the challenges of conversation-driven applications.

## Ways to Contribute

### Code Contributions
- **Core Platform**: Help build the foundational conversational state management engine
- **SDKs & Libraries**: Develop client libraries for different programming languages
- **Channel Adapters**: Create connectors for communication platforms (Slack, Teams, WhatsApp, etc.)
- **Schema Development**: Contribute business entity definitions and validation rules
- **Developer Tools**: Build debugging, testing, and development utilities

### Documentation & Examples
- **Technical Documentation**: Improve API docs, integration guides, and tutorials
- **Business Use Cases**: Document real-world implementation patterns and best practices
- **Code Examples**: Create sample applications and integration templates
- **Community Content**: Write blog posts, create videos, or speak at conferences

### Community & Ecosystem
- **Issue Triage**: Help categorize and prioritize GitHub issues
- **Community Support**: Answer questions in discussions and help new contributors
- **Testing**: Test new features and report bugs
- **Standards Development**: Contribute to the Act Specification and related protocols

## Getting Started

### Development Setup
1. **Fork the repository** you want to contribute to
2. **Clone your fork** locally
3. **Set up the development environment** (see repo-specific setup instructions)
4. **Create a feature branch** from `main`
5. **Make your changes** with clear, focused commits
6. **Test thoroughly** including edge cases and error conditions
7. **Submit a pull request** with a detailed description

### First Contributions
New to the project? Look for issues labeled:
- `good-first-issue` - Perfect for newcomers
- `help-wanted` - Community input needed
- `documentation` - Non-code contributions welcome

## Contribution Guidelines

### Code Standards
- **Follow existing patterns** and architectural decisions
- **Write comprehensive tests** for new functionality
- **Include clear documentation** for public APIs
- **Handle errors gracefully** with appropriate fallbacks
- **Consider performance implications** especially for real-time conversation processing

### Pull Request Process
1. **Describe the problem** your PR solves
2. **Explain your approach** and any trade-offs made
3. **Include test cases** that demonstrate the fix/feature
4. **Update documentation** if you're changing public interfaces
5. **Ensure CI passes** including tests, linting, and security checks

### Commit Message Format
```
type(scope): brief description

Detailed explanation of what changed and why.
Include any breaking changes or migration notes.

Fixes #123
```

Types: `feat`, `fix`, `docs`, `test`, `refactor`, `perf`, `chore`

## Project Structure

### Core Repositories
- **[pryszm/pryszm](https://github.com/pryszm/pryszm)** - Main platform and orchestration engine
- **[pryszm/act-spec](https://github.com/pryszm/act-spec)** - Open standard for conversational state
- **[pryszm/adapters](https://github.com/pryszm/adapters)** - Communication platform connectors
- **[pryszm/schemas](https://github.com/pryszm/schemas)** - Business entity definitions
- **[pryszm/devtools](https://github.com/pryszm/devtools)** - Developer utilities and debugging tools

### SDK Repositories
- **[pryszm/pryszm-js](https://github.com/pryszm/pryszm-js)** - JavaScript/TypeScript SDK
- **[pryszm/pryszm-python](https://github.com/pryszm/pryszm-python)** - Python SDK
- **[pryszm/pryszm-go](https://github.com/pryszm/pryszm-go)** - Go SDK
- **[pryszm/pryszm-react](https://github.com/pryszm/pryszm-react)** - React components

## Community Guidelines

### Be Inclusive and Respectful
- **Welcome newcomers** and help them get started
- **Respect different perspectives** and experience levels
- **Focus on constructive feedback** in code reviews
- **Assume good intentions** when discussing technical decisions

### Communication Channels
- **GitHub Issues** - Bug reports and feature requests
- **GitHub Discussions** - Technical questions and community discussions  
- **Slack Workspace** - Real-time collaboration and support
- **Email** - founders@pryszm.com for sensitive topics

### Code of Conduct
We follow the [Contributor Covenant Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/). Please report any unacceptable behavior to founders@pryszm.com.

## Security and Compliance

### Security Issues
- **DO NOT** file public GitHub issues for security vulnerabilities
- **Email security@pryszm.com** with details and steps to reproduce
- **Allow reasonable time** for response before public disclosure
- **Include your contact information** for follow-up questions

### Enterprise Considerations
When contributing, consider:
- **Privacy implications** of conversation data processing
- **Compliance requirements** (GDPR, HIPAA, SOC2)
- **Audit trail** requirements for business applications
- **Performance impact** on production systems

## Contribution Recognition

### Recognition Program
- **Contributor badges** for sustained participation
- **Feature credits** in release notes and documentation
- **Speaking opportunities** at conferences and community events
- **Early access** to new features and beta programs

### Maintainer Path
Regular contributors may be invited to become maintainers with:
- **Commit access** to repositories
- **Issue triage** responsibilities  
- **Code review** privileges
- **Community leadership** opportunities

## Legal Requirements

### Contributor License Agreement
By contributing to Pryszm, you agree that:
- **You have the right** to submit the contribution under the project license
- **Your contribution** will be licensed under the Apache License 2.0
- **You grant Pryszm** the right to use your contribution

### Attribution
- **Significant contributions** will be acknowledged in CONTRIBUTORS.md
- **Commit history** provides detailed attribution for all changes
- **Release notes** highlight major contributor efforts

---

## Questions?

- **Technical questions**: [GitHub Discussions](https://github.com/pryszm/pryszm/discussions)
- **Contribution help**: [Slack #contributors channel](https://pryszm.slack.com)
- **General inquiries**: founders@pryszm.com

**Ready to contribute?** Check out our [good first issues](https://github.com/search?q=org%3Apryszm+label%3A%22good+first+issue%22+state%3Aopen&type=issues) to get started!
