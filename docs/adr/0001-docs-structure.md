# ADR 0001: Documentation Structure

## Status

Accepted

## Context

The `docs/` directory is growing and needs a predictable structure so product, engineering, GitHub workflow, and operations material stay easy to find.

## Decision

We will organize `docs/` by functional area:

- `product/`
- `engineering/`
- `github/`
- `operations/`
- `adr/`
- `archive/`

We will use `docs/README.md` as the master documentation index.

## Consequences

### Positive

- Faster navigation
- Lower doc sprawl
- Clearer separation of active vs historical material
- Better onboarding for humans and AI agents

### Tradeoffs

- Small upfront cleanup effort
- Ongoing need to maintain the docs index
