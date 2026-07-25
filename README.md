# Zanvora

Zanvora is a responsive web application for managing an online store and related operations. It includes authentication flows, a polished frontend interface, and a deployment setup for static hosting.

## Features

- Login, signup, and password reset screens
- Responsive UI for desktop and mobile
- SPA-friendly routing setup for deployment
- Static frontend build ready for Vercel or similar hosts
- Custom branding with Zanvora logo and assets

## Project Structure

- `index.html` - App entry point
- `assets/` - Built JavaScript and CSS bundles
- `login_snippet.txt` - Login UI snippet
- `signup_snippet.txt` - Signup UI snippet
- `robots.txt.html` - Robots configuration page
- `vercel.json` - Deployment routing config
- `zanvora-logo.png` - Project logo

## Deployment

This project is configured for static deployment. The included `vercel.json` file rewrites all routes to `index.html`, which is useful for single-page applications.

### Vercel

1. Push this repository to GitHub.
2. Import the repo into Vercel.
3. Deploy with the default settings.

## Notes

- This repository currently contains the built frontend output.
- If you want to continue development from source, make sure to keep the original project files in a separate source branch or folder.

## License

Add your preferred license here.
