# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **GitHub Profile Repository** for LessUp, an AI Infrastructure & HPC Developer. The repository serves as a personal homepage showcasing projects, experience, and technical expertise.

## Repository Structure

```
/home/shane/lessup/LessUp/
├── README.md              # Main profile page (visual showcase)
├── changelog/
│   └── CHANGELOG.md      # Version history and updates
└── .git/                 # Git repository
```

## Key Files

### README.md
- Personal profile page with visual elements (badges, stats, project cards)
- Contains sections: About, Now, Projects, Experience, Tech Stack, Stats, Contact
- Uses GitHub profile README features (activity graphs, stats widgets, etc.)
- **Note**: This is NOT a code file - it's a visual presentation document

### changelog/CHANGELOG.md
- Tracks changes to the profile page
- Documents additions, modifications, and updates
- Uses standard [Keep a Changelog](https://keepachangelog.com/) format

## Development Workflow

### Common Tasks

Since this is a static profile repository:

1. **Updating Profile Content**
   - Edit README.md to modify personal information, projects, or stats
   - Follow the existing structure and visual formatting
   - Update changelog/CHANGELOG.md with each modification

2. **Adding New Projects**
   - Add project cards in the "Featured Projects" section
   - Include badges for relevant technologies
   - Update CHANGELOG.md

3. **Updating Stats/Sections**
   - Modify the About, Now, or Tech Stack sections as needed
   - Ensure consistency with English/Chinese bilingual format
   - Keep visual elements (badges, images) properly formatted

### No Build Process

This repository does not include:
- Build scripts or compilation
- Testing frameworks
- CI/CD pipelines
- Package management (no package.json, requirements.txt, etc.)

## Important Notes

- **Language**: The README uses English as primary language with Chinese translations for key sections
- **Visual Elements**: README heavily relies on images, badges, and GitHub widgets
- **Content Type**: This is content/documentation, not application code
- **Changes**: All modifications should be logged in changelog/CHANGELOG.md

## Git Workflow

Standard git operations:
- `git add .` - Stage changes
- `git commit -m "message"` - Commit changes
- `git push` - Push to remote

Remember to update CHANGELOG.md before committing significant changes.
