# Vibe Code - Copilot Instructions

## Project Overview
Vibe Code is a Hugo application using Tailwind CSS. This project uses the Blowfish theme as a base, with customizations for a clean, modern look. The project is structured to leverage Hugo's strengths in static site generation while maintaining flexibility for future enhancements.

## Key Architecture Components

### Hugo App
- Uses markdown
- Each folder in the content > comics folder has a featured image that begins with "featured-" and an index.md file.
- The weight of the index.md frontmatter needs to match the prefix number of the parent folder name
- The slug in the frontmatter needs to match the suffix of the parent folder name after the number and dash.
- The title in the frontmatter takes the slug and converts dashes to spaces and capitalizes the first letter of each word.
- At least one tag is required in the frontmatter and that tag should match the grand parent folder name. 

### Styling
- Tailwind CSS for styling (v4)

## Development Workflow

### Commands
- `hugo server` - Start development server with Turbopack
- `hugo build` - Build for production with Turbopack

## Code Conventions

### File Structure
- `/content` - Main application content for each post
- `/layouts` - This is where the primary code is located
- `/layouts` - We are using the blowfish theme as a base

### CSS Approach
- Tailwind classes for styling (className approach)

### Important Notes
- Don't modify more than what I tell you to modify.