# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-page static website for **Leśna Residencja Królewo** (Forest Residence Królewo), a Polish vacation rental business offering luxury apartments by a lake in Królewo, Mazowieckie, Poland.

## Architecture

**Single-file architecture**: The entire website is contained in `index.html` with embedded CSS and JavaScript. No build process, dependencies, or external files required.

### Technology Stack
- Pure HTML5, CSS3, and vanilla JavaScript
- Responsive design using CSS Grid and Flexbox
- Polish language content (lang="pl")
- Green forest/nature color scheme (#2c5530, #4a7c59, #ff6b35)

## Content Structure

The website contains these main sections:
- **Hero**: Main landing area with reservation CTA
- **Apartments**: Three types (family, couples, group)
- **Amenities**: Lake access, parking, campfire, trails, fishing, water sports
- **Gallery**: Placeholder items for property photos
- **Contact**: Phone, email, address, website

## Business Information
- **Contact**: +48 123 456 789
- **Email**: rezerwacje@lesnaresidenckjakrolewo.pl
- **Website**: www.LesnaResidencjaKrolewo.pl
- **Location**: Królewo, Mazowieckie, Poland

## Repository Information

- **Remote Repository**: https://github.com/andrewgacamac/LesnaResidencjaKrolewo.git
- **Branch**: main

## Development Workflow

**No build process required** - edit `index.html` directly and deploy to any static hosting service.

### Making Content Changes
- **Text content**: Edit directly in HTML
- **Contact info**: Update in the contact section and any meta references
- **Images**: Replace gallery placeholder divs with actual `<img>` tags
- **Styling**: Modify the embedded CSS in the `<style>` block

### Deployment
Deploy `index.html` directly to static hosting services like:
- GitHub Pages
- Netlify
- Vercel
- Traditional web hosting

## Key Features to Maintain
- **Responsive design**: Mobile breakpoint at 768px
- **Smooth scrolling navigation**: JavaScript handles anchor link scrolling
- **Fixed header**: Navigation stays visible while scrolling
- **Accessibility**: Semantic HTML structure with proper headings
- **Performance**: Self-contained single file loads quickly

## Future Enhancement Considerations
- Replace gallery placeholders with actual property photos
- Add contact form functionality (requires backend)
- Implement booking system integration
- Add Google Maps integration for location
- Consider splitting into multiple files if content grows significantly