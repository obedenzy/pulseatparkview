# Pulse At ParkView

## Overview
A static website for "Pulse At ParkView" - a mixed-use development featuring residential, commercial, and wellness spaces. The site includes a simple "Coming Soon" landing page and a full multi-section homepage.

## Project Structure
- `index.html` - Simple "Coming Soon" landing page with logo
- `homepage.html` - Full featured multi-section website with:
  - Hero section
  - Explore/Directory section
  - Apartments/Live section
  - Wellness section
  - Happenings/Events section
  - About section
  - Latest News section
  - Contact form
  - Social media grid
  - Interactive map section
- `assets/logo.jpg` - Pulse At ParkView logo
- `server.py` - Python HTTP server configured for Replit environment

## Technology Stack
- Static HTML/CSS/JavaScript
- Python 3.11 HTTP server
- No build process required

## Development Setup
- Server runs on port 5000 (0.0.0.0:5000)
- Cache-Control headers disabled for development
- Configured for Replit's proxy environment

## Color Scheme
- Primary: Dark Green (#4A5D23)
- Accent: Blue (#A3BFFA)
- Background: Beige (#F5F1E9)
- Text: Dark Green for headers, Dark Grey (#555) for body text

## Recent Changes
- 2025-11-17: Imported from GitHub and configured for Replit environment
- Added Python HTTP server with cache-control headers
- Created .gitignore for Python project
- Set up deployment configuration
- Updated Strength & Conditioning Center to use custom image asset (images/1763319630.png)
- Modified directory rendering logic to support both placeholder and real image paths

## Architecture
Simple static site served via Python's built-in HTTP server. No framework or build tools needed.
