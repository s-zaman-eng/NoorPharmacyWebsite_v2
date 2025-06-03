# Deployment Guide for Noor Pharmacy Website

## Quick GitHub Pages Setup

1. **Create GitHub Repository**
   - Go to GitHub.com and create a new repository
   - Name it `noor-pharmacy-website` (or your preferred name)
   - Make it public for free GitHub Pages hosting

2. **Upload Files**
   - Upload all website files to the repository
   - Ensure `index.html` is in the root directory

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main (or master)
   - Folder: / (root)
   - Click Save

4. **Access Your Website**
   - Your site will be available at: `https://yourusername.github.io/repository-name`
   - Initial deployment may take 5-10 minutes

## File Checklist

Ensure these files are in your repository:
- ✓ index.html
- ✓ about.html
- ✓ services.html
- ✓ contact.html
- ✓ css/style.css
- ✓ js/main.js
- ✓ assets/logo.svg
- ✓ assets/wallpaperflare.com_wallpaper.jpg
- ✓ favicon.svg
- ✓ favicon.ico
- ✓ README.md
- ✓ .gitignore

## Custom Domain (Optional)

To use a custom domain like `www.noorpharmacy.com`:

1. Purchase domain from registrar
2. Add CNAME file to repository with your domain
3. Configure DNS settings at your registrar
4. Update GitHub Pages settings

## Alternative Hosting Options

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **Traditional Web Hosting**: Upload via FTP

## Google Maps Configuration

For full map functionality, obtain a Google Maps API key:
1. Go to Google Cloud Console
2. Enable Maps Embed API
3. Create API key
4. Replace placeholder in contact.html

## Support

For deployment assistance, contact your web developer.