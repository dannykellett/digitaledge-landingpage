# DigitalEdge Landing Page

A modern, responsive landing page for DigitalEdge featuring a hero section, statistics, services showcase, and contact information.

## 🚀 Quick Start

### Prerequisites
- A web browser
- A text editor (optional, for customization)
- Git installed on your machine

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/digitaledge-landingpage.git
   cd digitaledge-landingpage
   ```

2. Open `index.html` in your web browser:
   - Double-click the file, or
   - Use a local server (recommended):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

## 📦 Deployment Options

### Option 1: GitHub Pages (Free & Easy)
1. Push your code to GitHub
2. Go to Settings → Pages in your repository
3. Source: Deploy from a branch
4. Branch: Select `main` (or `master`) and `/root`
5. Click Save
6. Your site will be available at: `https://YOUR_USERNAME.github.io/digitaledge-landingpage/`

### Option 2: Netlify (Free with Custom Domain)
1. Create a [Netlify account](https://netlify.com)
2. Connect your GitHub repository
3. Deploy settings:
   - Build command: (leave empty)
   - Publish directory: `/`
4. Click "Deploy site"
5. Optional: Add a custom domain in Domain settings

### Option 3: Vercel (Free with Custom Domain)
1. Create a [Vercel account](https://vercel.com)
2. Import your GitHub repository
3. Framework Preset: Other
4. Root Directory: `./`
5. Click "Deploy"
6. Optional: Add a custom domain in Project settings

### Option 4: Traditional Web Hosting
1. Use FTP/SFTP to upload files to your web host
2. Upload only the `index.html` file
3. Ensure the file is in the public directory (usually `public_html` or `www`)

## 🛠️ Customization

### Updating Content
- Edit `index.html` to change text, images, or structure
- All styles are embedded in the `<style>` section
- The site uses vanilla HTML/CSS with no dependencies

### Changing Colors
The color scheme uses CSS variables defined at the top of the style section:
```css
:root {
    --primary-color: #4f46e5;
    --primary-hover: #4338ca;
    /* etc. */
}
```

### Adding Sections
Copy an existing section structure and modify the content as needed.

## 📱 Features
- ✅ Fully responsive design
- ✅ Mobile-friendly navigation
- ✅ Smooth scrolling
- ✅ Contact form ready (requires backend integration)
- ✅ SEO-friendly structure
- ✅ Fast loading (no external dependencies)

## 📄 License
This project is private and proprietary.

## 🤝 Support
For questions or support, please contact the repository owner.