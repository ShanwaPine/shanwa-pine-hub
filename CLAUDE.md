# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

"山娃寒松记" (Shanwa Pine Hub) is a personal knowledge base and content repository focused on technical mentorship and personal development. The repository owner is a technical professional with 10+ years of experience in technology and product management, sharing growth insights and productivity tools.

## Repository Structure

```
shanwa-pine-hub/
├── tools/
│   └── prompts/          # AI prompt templates and configurations
├── seeds/                # Archived content and reference materials
└── README.md            # Personal brand introduction
```

### Key Directories

- **tools/prompts/**: Contains AI prompt engineering templates, particularly for the "慧音导师" (Huiyin Mentor) persona - a comprehensive AI mentor character combining technical expertise, life coaching, and Eastern philosophy (心学/Xinxue, Weiqi/Go strategy)

- **seeds/**: Archive directory for reference materials and foundational content (may contain compressed archives)

## Content Language

All content in this repository is in Chinese (Simplified). When working with this codebase, maintain consistency with Chinese language conventions and terminology.

## Working with Prompts

The primary content type in this repository is AI prompts located in `tools/prompts/`:

- **慧音导师提示词.md**: A detailed prompt template for an AI mentor persona that integrates:
  - Technical mentorship (programming, product management, entrepreneurship)
  - Eastern philosophy (心学/Xinxue principles, Weiqi/Go strategy)
  - Personal development coaching
  - Practical wisdom for career and life decisions

When modifying or creating new prompts:
- Follow the structured format used in existing prompts (role definition, interaction context, response guidelines)
- Maintain the balance between practical advice and philosophical depth
- Keep the mentor's voice authentic and experience-based
- Ensure prompts are detailed enough to provide consistent, high-quality AI responses

## File Management

The .gitignore is configured to exclude:
- Development environment files (Python, Node.js, IDE configs)
- Archive files (.7z, .zip, .tar, etc.)
- Sensitive information (.env, *.key, *.pem)
- System files (macOS, Windows, Linux temporary files)

When adding new content:
- Use Markdown (.md) for documentation and prompt files
- Compress large reference materials before adding to seeds/
- Avoid committing temporary or generated files
