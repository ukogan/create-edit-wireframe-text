# Editable Wireframes Demo

A demonstration of contextual UI text editing using interactive HTML wireframes. Edit UI text in real-time and see changes instantly in the mockup context.

## 🌐 Live Demo

Visit the live demo: [https://yourusername.github.io/create-edit-wireframes/](https://yourusername.github.io/create-edit-wireframes/)

## ✨ Features

- **Real-time editing**: See text changes instantly in wireframe context
- **Multiple wireframe types**: Main window, onboarding flow, and settings panel
- **Download functionality**: Export both JSON config and modified HTML
- **Import/Export**: Share wireframe configurations with others
- **No dependencies**: Pure HTML, CSS, and JavaScript - runs anywhere

## 🚀 The Problem This Solves

When AI generates UI mockups, the text content often needs refinement. But editing text in a separate file means you can't see how it fits in the actual UI:

- Will the button text overflow?
- Does the error message make sense in context?
- How does the copy look with the actual spacing and typography?

## 💡 The Solution

Interactive wireframes with contextual text editing:

1. **Select a wireframe** - Choose from demo wireframes
2. **Edit in real-time** - Modify text and see changes instantly
3. **Download results** - Export JSON config and modified HTML

## 📱 Available Wireframes

### Main Window
Primary application interface with availability display and user controls
- User status and connection info
- Date range selector  
- Action buttons (Find, Copy, Save)
- Success/error messaging

### Onboarding Flow
User setup and configuration screens for first-time app setup
- Welcome messaging
- Setup instructions
- Progress indicators
- Call-to-action buttons

### Settings Panel
Configuration interface with preferences and account management
- Setting descriptions
- Help tooltips
- Form labels and placeholders
- Validation messaging

## 🛠️ Usage

1. Open `index.html` in your browser or visit the live demo
2. Select a wireframe to edit
3. Use the text editor panel to modify any UI text
4. See changes appear instantly in the wireframe
5. Download JSON config or modified HTML when finished

## 📦 Local Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/create-edit-wireframes.git

# Navigate to the project
cd create-edit-wireframes

# Open in browser
open index.html
```

No build process or dependencies required!

## 🔧 Technical Details

- **Frontend-only**: Self-contained HTML files with embedded CSS/JS
- **JSON configuration**: Text content stored separately from presentation
- **Real-time updates**: JavaScript listeners update wireframe instantly
- **Download functionality**: Blob API for file downloads
- **Import/Export**: File API for configuration sharing

## 🎯 Use Cases

- **Rapid prototyping**: Test different copy variations quickly
- **Content strategy**: See how messaging fits in actual UI layouts
- **Client presentations**: Let stakeholders edit text directly in context
- **Design handoffs**: Provide developers with refined copy in structured format

## 📄 License

This project demonstrates the concept of contextual UI text editing. Feel free to adapt and extend for your own use cases.

---

*Built to demonstrate contextual UI text editing for rapid prototyping workflows*