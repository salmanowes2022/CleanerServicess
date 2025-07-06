# SuperClean Cleaning Services Website

A professional cleaning services website built with HTML, CSS, and JavaScript.

## Features

- Responsive design
- Modern UI/UX
- Service showcase
- Customer testimonials
- Contact forms
- FAQ section

## Deployment on Render

This is a static website that can be deployed on Render's Static Site service.

### Deployment Steps:

1. **Fork or clone this repository**
2. **Go to [render.com](https://render.com)**
3. **Sign up/Login with your GitHub account**
4. **Click "New +" → "Static Site"**
5. **Connect your GitHub repository**
6. **Configure:**
   - Name: `cleaner-services-website`
   - Branch: `main`
   - Build Command: (leave empty)
   - Publish Directory: (leave empty)
7. **Click "Create Static Site"**

### Manual GitHub Upload (if needed):

If you need to create a new repository:

```bash
# Create a new repository on GitHub
# Then run these commands:

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

## Local Development

To run this website locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## File Structure

```
├── index.html          # Main homepage
├── css/               # Stylesheets
├── js/                # JavaScript files
├── images/            # Website images
└── README.md          # This file
```

## Contact

For any questions about deployment or the website, please refer to the contact information in the website.
