# DMACC - Weekly Class Agenda Repository

This repository stores markdown files used to create slides for displaying weekly class agendas at Des Moines Area Community College (DMACC).

## Repository Structure

```
DMACC/
├── README.md
└── agendas/
    ├── template-agenda.md          # Template for creating new weekly agendas
    ├── 2024-week-01-agenda.md      # Example agenda file
    └── [YYYY-week-XX-agenda.md]    # Additional weekly agenda files
```

## File Naming Convention

Use the following naming convention for weekly agenda files:
- Format: `YYYY-week-XX-agenda.md`
- Examples: 
  - `2024-week-01-agenda.md`
  - `2024-week-15-agenda.md`
  - `2025-week-01-agenda.md`

## Creating a New Weekly Agenda

1. Copy the `template-agenda.md` file
2. Rename it using the naming convention above
3. Fill in the course-specific information
4. Update the content for the specific week
5. Commit and push your changes

## Template Structure

Each agenda includes:
- **Course Information**: Basic course details and timing
- **Learning Objectives**: What students will accomplish
- **Topics Covered**: Main content for the week
- **Activities**: In-class activities, lab work, and assignments
- **Resources**: Required and supplementary materials
- **Next Week Preview**: Looking ahead
- **Notes**: Additional information and reminders

## Converting to Slides

These markdown files can be converted to presentation slides using tools such as:
- **Marp**: Markdown presentation ecosystem
- **reveal.js**: HTML presentations framework
- **Pandoc**: Universal document converter
- **GitPitch**: Git-based slideshow presentations

### Quick Marp Example
```bash
# Install Marp CLI
npm install -g @marp-team/marp-cli

# Convert markdown to slides
marp agendas/2024-week-01-agenda.md --pdf
marp agendas/2024-week-01-agenda.md --html
```

## Best Practices

1. **Consistency**: Use the template structure for all agendas
2. **Clarity**: Keep bullet points concise and actionable
3. **Updates**: Review and update agendas before each class
4. **Version Control**: Commit changes with descriptive messages
5. **Accessibility**: Use proper markdown formatting for screen readers

## Contributing

When adding new agenda files:
1. Follow the naming convention
2. Use the template structure
3. Include all required sections
4. Test markdown formatting before committing
5. Add meaningful commit messages
