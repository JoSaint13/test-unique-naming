# Specification-Driven Development

## Project: test-unique-naming

This project follows **Specification-Driven Development (SDD)** principles, inspired by [GitHub's spec-kit](https://github.com/github/spec-kit).

### Philosophy

In traditional development, code is king. Specifications serve code. In SDD, we **invert this power structure**:

- **Specifications don't serve code—code serves specifications**
- The Product Requirements Document (PRD) isn't a guide; it's the source that generates implementation
- Technical plans produce code directly
- Specifications are executable and become the primary artifact

### Project Structure

```
test-unique-naming/
├── README.md                          # Project overview
├── spec-driven.md                     # This file
├── specs/                             # Feature specifications
│   └── 001-initial-feature/
│       ├── spec.md                    # Feature specification
│       └── plan.md                    # Implementation plan
├── src/                               # Generated source code
└── tests/                             # Generated tests
```

### Workflow

1. **Specify**: Define features in natural language with clear acceptance criteria
2. **Plan**: Generate implementation plans from specifications
3. **Generate**: Produce code from plans automatically
4. **Iterate**: Update specifications, regenerate code

### Benefits

- **Single Source of Truth**: Specifications drive everything
- **Continuous Alignment**: Code always matches intent
- **Rapid Iteration**: Change specs, regenerate code
- **Living Documentation**: Specs are always up-to-date

### Learn More

- [GitHub Spec-Kit](https://github.com/github/spec-kit)
- [Spec-Driven Development Philosophy](https://github.com/github/spec-kit/blob/main/spec-driven.md)

---

**Generated**: test-unique-naming uses SDD to maintain quality and velocity throughout development.
