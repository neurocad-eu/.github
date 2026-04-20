# Governance

## Purpose

The NeuroCAD public GitHub organization exists to expose inspectable technical surfaces around the platform without disclosing proprietary implementation details.

## Repository classes

### Public repositories

Public repositories are used for:

- API contracts and schemas
- benchmark packaging and release artifacts
- integration examples
- public architecture and diligence-facing documentation

### Private repositories

Private repositories are used for:

- kernel implementation
- internal model and data systems
- production infrastructure and operations

## Maintenance model

Public repositories are maintained as versioned technical artifacts.

Expected maintenance signals include:

- tagged releases
- validation workflows
- explicit ownership
- change logs or release notes
- issue triage for repository-scoped requests

## Change policy

Changes to the public surface should prefer:

- additive contract evolution
- explicit release boundaries
- stable identifiers and schema versions
- clear notes when public behavior changes

## Security and private disclosure

Security reports and private diligence requests should not be opened as public issues.

Use:

- `office@neurocad.eu`
