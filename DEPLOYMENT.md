# GitHub Pages Deployment

This project is designed to be deployed easily on GitHub Pages to demonstrate the editable wireframes concept.

## Quick Setup

1. **Fork/Create Repository**
   - Fork this repository or create a new one with these files
   - Ensure all HTML files are in the root directory

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Scroll to "Pages" section  
   - Source: Deploy from a branch
   - Branch: main (or master)
   - Folder: / (root)
   - Save

3. **Access Your Demo**
   - Your site will be available at: `https://yourusername.github.io/repository-name/`
   - GitHub will provide the exact URL in the Pages settings

## File Structure

```
/
├── index.html                    # Main landing page
├── main-window-wireframe.html    # Main app wireframe editor
├── onboarding-wireframe.html     # Onboarding flow editor  
├── settings-wireframe.html       # Settings panel editor
├── *.json                        # Sample configuration files
├── README.md                     # Project documentation
└── DEPLOYMENT.md                 # This file
```

## Features Included

- ✅ Responsive design for mobile/desktop
- ✅ Real-time text editing with instant preview
- ✅ JSON export/import functionality
- ✅ HTML download with modifications
- ✅ Navigation between wireframes
- ✅ Clear instructions and examples

## No Build Process Required

This is a static site with no dependencies:
- Pure HTML, CSS, and JavaScript
- No npm packages or build tools
- No server requirements
- Works immediately on GitHub Pages

## Customization

To adapt this for your own wireframes:

1. **Replace wireframe HTML files** with your own designs
2. **Update index.html** with your wireframe descriptions
3. **Modify JSON structures** to match your text fields
4. **Update README.md** with your project details

## Demo Content

The included wireframes demonstrate a fictional "FreeBusy" calendar app:
- Main window with availability generation
- Onboarding flow for new users  
- Settings panel for configuration

This shows how the concept applies to different UI contexts and use cases.

---

*Ready to deploy and demonstrate contextual UI text editing!*