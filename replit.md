# SRJ Consulting & Services LLC — Landing Page

## Overview
This is a static landing page for SRJ Consulting & Services LLC. The page showcases their consulting services, industries served, pricing tiers, and includes contact information with Calendly integration for booking meetings.

**Purpose**: Professional landing page for client engagement and service discovery
**Technology**: Static HTML with embedded CSS
**Contact**: 
- Phone: +1 (415) 413-7772
- Calendly: https://calendly.com/srj-srjconsultingservices/introductory-meeting

## Project Structure
- `index.html` - Main landing page with all content and styling
- `assets/` - Favicon and logo images
- `server.py` - Python HTTP server for local development
- `_redirects` - Netlify redirect configuration
- `netlify.toml` - Netlify deployment configuration

## Development Setup
The project uses a simple Python HTTP server to serve static files on port 5000.

**To run locally:**
```bash
python3 server.py
```

The server includes cache-control headers to ensure fresh content delivery during development.

## Recent Changes
- **2025-10-25**: Imported from GitHub and configured for Replit environment
  - Set up Python HTTP server on port 5000
  - Configured workflow for automatic server startup
  - Added Python-related entries to .gitignore

## Deployment
Originally configured for Netlify deployment. Can be deployed to any static hosting service as all content is in a single HTML file with embedded styles.
