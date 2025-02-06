# Contributing to Open Facilitation Library

First off, thank you for considering contributing to OFL! It's people like you that help turn facilitation wisdom into accessible patterns for everyone.

## Types of Contributions

### 1. Facilitation Patterns
- Document successful facilitation techniques
- Share case studies and outcomes
- Propose improvements to existing patterns
- Translate patterns into different languages

#### Pattern Contribution Format
```yaml
name: "Pattern Name"
category: "Category"
context: "When to use this pattern"
time_required: "Estimated duration"
group_size: "Recommended group size"
materials_needed: "Required materials"
steps:
  - step: "First step"
    description: "Detailed description"
outcome: "Expected outcomes"
variations: "Possible adaptations"
references: "Sources and credits"
```

### 2. Code Contributions
- API improvements
- Bug fixes
- Feature implementations
- Documentation updates

#### Coding Standards
- Use TypeScript for type safety
- Follow ESLint configuration
- Write tests for new features
- Keep functions small and focused
- Document public APIs

### 3. Documentation
- Improve existing docs
- Add examples and tutorials
- Fix typos or unclear sections
- Add translations

### 4. Data Contributions
- Annotated facilitation sessions
- Success metrics
- Use cases
- Impact studies

## Contribution Process

### 1. Pattern Contributions
1. Check existing patterns in `data/patterns/`
2. Use pattern template from `templates/pattern.yaml`
3. Add your pattern in appropriate category
4. Include relevant metadata
5. Submit PR with `[Pattern]` prefix

### 2. Code Contributions
1. Fork the repository
2. Create feature branch
3. Write/update tests
4. Update documentation
5. Submit PR with issue reference

#### Commit Message Format
```
type(scope): Message

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

### 3. Documentation Updates
1. Locate relevant docs
2. Make changes
3. Preview locally
4. Submit PR with `[Docs]` prefix

### 4. Data Contributions
1. Review data guidelines
2. Use provided templates
3. Include metadata
4. Submit PR with `[Data]` prefix

## Quality Standards

### Pattern Quality
- Clear purpose and context
- Step-by-step instructions
- Measurable outcomes
- Real-world examples
- Proper attribution

### Code Quality
- Passes all tests
- Follows style guide
- Includes documentation
- Has error handling
- Performance conscious

### Documentation Quality
- Clear and concise
- Proper grammar
- Working links
- Up-to-date information
- Examples where needed

## Review Process

1. Initial Review (2-3 days)
   - Completeness check
   - Style guide compliance
   - Basic functionality

2. Technical Review (if applicable)
   - Code quality
   - Test coverage
   - Performance impact

3. Pattern Review (if applicable)
   - Facilitation expert review
   - Community feedback
   - Integration assessment

4. Final Review
   - Documentation check
   - Merge preparation
   - Release planning

## Communication

- **Questions**: Use GitHub Discussions
- **Bugs**: Open GitHub Issues
- **Features**: Use Feature Request template
- **Direct Contact**: Join our [Discord]()

## Development Setup

```bash
# Install dependencies
npm install

# Run tests
npm test

# Start development server
npm run dev

# Build documentation
npm run docs
```

## Best Practices

### Pattern Development
- Start with user needs
- Document assumptions
- Include edge cases
- Provide examples
- Consider accessibility

### Code Development
- Write tests first
- Keep it simple
- Document as you go
- Consider edge cases
- Focus on maintainability

### Documentation
- Use clear language
- Include examples
- Keep up-to-date
- Link related content
- Consider all skill levels

## Recognition

Contributors will be:
- Listed in `CONTRIBUTORS.md`
- Mentioned in release notes
- Invited to special events
- Given priority support

## Questions?

- Check our FAQ
- Join Discord community
- Email contribute@openfacilitation.org
- Open a GitHub Discussion

Thank you for contributing to better collective sensemaking! 🌟
