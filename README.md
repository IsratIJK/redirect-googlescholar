# Google Scholar Redirect

A simple redirect service that redirects visitors from `gs.isratjahankhan.com` to Israt Jahan Khan's Google Scholar profile.

## Overview

This repository contains a beautifully designed HTML redirect page that automatically redirects users to the Google Scholar profile at:
`https://scholar.google.com/citations?user=n4mCE9QAAAAJ&hl=en`

## Features

- **Instant Redirect**: Uses multiple redirect methods for maximum compatibility
- **Beautiful Design**: Modern glassmorphism UI with gradient background
- **Loading Animation**: Animated spinner to indicate redirect in progress
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **SEO Friendly**: Includes proper meta tags and canonical links
- **Fallback Support**: Manual link for users with JavaScript disabled

## Redirect Methods

The page uses three redirect methods to ensure reliability:

1. **Meta Refresh**: `<meta http-equiv="refresh">` for immediate redirect
2. **JavaScript**: `window.location.href` as a backup method
3. **Manual Link**: Clickable link for users with JavaScript disabled

## Deployment

### GitHub Pages
1. Push this repository to GitHub
2. Go to Settings > Pages
3. Select source as "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Your redirect will be available at `https://github-username.github.io/redirect-googlescholar`

### Netlify
1. Connect your GitHub repository to Netlify
2. Deploy with default settings
3. Configure custom domain `gs.yourdomain.com`

### Vercel
1. Import your GitHub repository to Vercel
2. Deploy with default settings
3. Configure custom domain `gs.yourdomain.com`

### Other Hosting Providers
Simply upload the `index.html` file to your web hosting provider's public directory.

## Domain Setup

To use the custom domain `gs.yourdomain.com`:

1. **DNS Configuration**: Add a CNAME record pointing to your hosting provider
2. **SSL Certificate**: Most hosting providers offer free SSL certificates
3. **Custom Domain**: Configure the custom domain in your hosting provider's dashboard

## File Structure

```
redirect-googlescholar/
├── index.html          # Main redirect page
├── LICENSE            # MIT License
└── README.md          # This file
```

## Technical Details

- **HTML5**: Uses modern HTML5 structure
- **CSS3**: Features gradient backgrounds and animations
- **Responsive Design**: Mobile-first approach with flexible layouts
- **Cross-browser Compatible**: Works on all modern browsers
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no external libraries

## Customization

To modify the redirect destination, update the URL in three places in `index.html`:

1. Meta refresh tag (line 7)
2. Canonical link (line 8)
3. JavaScript redirect (line 55)
4. Manual fallback link (line 52)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Israt Jahan Khan**
- Google Scholar: [Profile Link](https://scholar.google.com/citations?user=n4mCE9QAAAAJ&hl=en)

## Reference

- Md. Fahim Bin Amin's [redirect-googlescholar](https://github.com/FahimFBA/redirect-googlescholar)