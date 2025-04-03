
# Dynamic Input Manager

![Dynamic Input Manager Screenshot](https://via.placeholder.com/800x500.png?text=Dynamic+Input+Manager+Demo)

A flexible, client-side input management system with dark/light theme support, data persistence, and export/import capabilities.

## Key Features

- 🎨 **Theme Support**: Toggle between light/dark modes
- ➕ **Dynamic Inputs**: Add/remove input fields on demand
- 📋 **Label Editing**: Customize field labels directly
- 💾 **Data Persistence**: Automatically saves inputs
- 📤📥 **Import/Export**: JSON file support
- 📋 **Copy Output**: One-click copy functionality
- 🍪 **Cookie Storage**: Preserves data between sessions

## Installation & Usage

1. Simply download the HTML file
2. Open in any modern browser
3. No server or dependencies required

## Where You Can Use This

### For Developers
- **Prototyping forms** - Quickly mock up form structures
- **Configuration management** - Store and edit app settings
- **API testing** - Manage test data inputs
- **Local storage experiments** - Learn client-side data handling

### For Content Creators
- **Blog post outlines** - Organize article sections
- **Video script planning** - Structure scene descriptions
- **Social media content calendars** - Plan post captions

### For Educators
- **Lesson planning** - Organize teaching materials
- **Student feedback forms** - Collect and manage evaluations
- **Quiz creation** - Build question banks

### For Personal Use
- **Shopping lists** - Manage grocery items
- **Task management** - Track to-do items
- **Contact organization** - Store important information
- **Journaling** - Maintain daily entries

## Technical Implementation

### Core Technologies
- Pure HTML/CSS/JavaScript
- Client-side storage using cookies
- File API for import/export
- Clipboard API for copying

### Key Functions
```javascript
// Theme management
ThemeManager.toggleTheme()

// Input handling
InputManager.addInput()
InputManager.removeInput()

// Data persistence
DataManager.exportData()
DataManager.importData()
```

## Customization Options

### Theme Colors
Modify the CSS variables:
```css
:root {
  --main-color: #e61355;
  --second-color: #f48fb1;
  --bg-color: #ffffff;
}
```

### Input Behavior
Adjust in the JavaScript:
```javascript
// Change default label/text
InputManager.addInput("New Label", "Default Value")
```

## Future Enhancements

1. LocalStorage integration
2. Cloud sync capability
3. More export formats (CSV, XML)
4. Input validation
5. Drag-and-drop reordering
