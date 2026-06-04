# To-Do List Application

A modern, responsive to-do list application with local storage functionality. Built with vanilla HTML, CSS, and JavaScript.

## Features

✨ **Core Features:**
- ✅ Add, complete, and delete tasks
- 💾 Automatic local storage persistence
- 🎯 Filter tasks (All, Active, Completed)
- 📊 Real-time statistics (Total, Completed, Remaining)
- 🗑️ Bulk actions (Clear Completed, Delete All)
- 📱 Fully responsive design
- ⚡ No dependencies required

## Getting Started

1. **Clone or download the project**
   ```bash
   git clone https://github.com/wangxueming/todo-app.git
   cd todo-app
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     python -m http.server 8000
     # or
     npx http-server
     ```

3. **Start adding tasks!**

## How to Use

### Adding Tasks
- Type your task in the input field
- Press Enter or click the "Add" button
- Your task will be saved automatically

### Managing Tasks
- **Check/Uncheck**: Click the checkbox to mark a task as completed
- **Delete**: Click the "Delete" button next to any task
- **Filter**: Use the filter buttons to view All, Active, or Completed tasks

### Bulk Actions
- **Clear Completed**: Remove all completed tasks at once
- **Delete All**: Remove all tasks (confirmation required)

## Local Storage

All tasks are automatically saved to your browser's local storage. This means:
- ✅ Tasks persist even after closing the browser
- ✅ No server required
- ✅ No sign-up or login needed
- ✅ Data stays on your device

**Note**: Clearing browser data will delete stored tasks.

## Technical Details

### Project Structure
```
todo-app/
├── index.html    # HTML structure
├── styles.css    # Styling and responsive design
├── script.js     # Application logic and local storage
└── README.md     # Documentation
```

### Key Technologies
- **HTML5**: Semantic markup
- **CSS3**: Flexbox, Grid, Gradients, Animations
- **Vanilla JavaScript**: No frameworks or dependencies
- **LocalStorage API**: Data persistence

### Browser Compatibility
Works on all modern browsers that support:
- ES6 JavaScript
- LocalStorage API
- CSS Grid and Flexbox

## Features Breakdown

### Statistics Dashboard
Real-time display of:
- Total number of tasks
- Completed tasks count
- Remaining tasks count

### Filtering System
- **All**: Shows all tasks
- **Active**: Shows only incomplete tasks
- **Completed**: Shows only completed tasks

### Responsive Design
- Desktop-optimized layout
- Tablet-friendly interface
- Mobile-responsive design
- Touch-friendly buttons

## Customization

### Change Colors
Edit the gradient in `styles.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Change Font
Modify the font-family in `styles.css`:
```css
font-family: 'Your Font Name', sans-serif;
```

### Storage Key
Change the storage key in `script.js`:
```javascript
this.storageKey = 'your-custom-key';
```

## Future Enhancements

Potential features for future versions:
- 📅 Due dates and reminders
- 🏷️ Categories and tags
- 🎨 Theme switcher
- 📤 Export/Import functionality
- 🔄 Undo/Redo capability
- 📝 Task editing
- ⭐ Priority levels
- 🔔 Notifications

## License

This project is open source and available under the MIT License.

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## Support

If you encounter any issues, please:
1. Check your browser's console for error messages
2. Clear browser cache and try again
3. Ensure JavaScript is enabled
4. Try a different browser

---

**Made with ❤️ for productivity enthusiasts**