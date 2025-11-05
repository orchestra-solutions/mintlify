# Orchestra Developer Documentation

## Project Overview
Building developer documentation for Orchestra, a payment orchestration service (orchestrasolutions.com). Developer relations is the primary channel for client acquisition.

## Objectives
- Create comprehensive, best-in-class developer documentation
- Enable developers to integrate Orchestra quickly and confidently
- Establish Orchestra as the authoritative resource for payment orchestration
- Drive developer adoption through clear, practical guides and examples

## Documentation Scope
- API reference and technical specifications
- Integration guides for popular payment providers
- Code examples and SDKs
- Authentication and security
- Troubleshooting and FAQ
- Best practices for payment orchestration

## Working Directory
- **Local path**: `/home/adam/orchsol-docs`
- **GitHub repo**: https://github.com/adam-marash/orchsol-docs.git
- **Service**: https://orchestrasolutions.com/

## Dev Rel Strategy
- Documentation as the core product for developer acquisition
- Focus on reducing time-to-first-integration
- Maintain practical, real-world examples
- Version control all documentation assets

## Technical Stack
- **Platform**: Mintlify - hosted documentation with MDX support
- **Format**: Markdown with MDX components for visual enhancement
- **Repo structure**: GitHub repo with `docs/` directory for content
- **API spec**: OpenAPI 3.0.4 (`orchsol.json`) for auto-generated reference
- **Deployment**: GitHub → Mintlify pipeline (automatic on push)
