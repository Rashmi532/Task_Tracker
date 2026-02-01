# Task Tracker - Simple Frontend Project

A beautiful and modern task tracker application built with vanilla HTML, CSS, and JavaScript.

## 📁 Project Structure

```
Task Tracker/
│
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styling and responsive design
├── js/
│   └── app.js          # Application logic and functionality
├── assets/             # Folder for images, icons, etc.
└── README.md           # Project documentation
```

## 🚀 How to Run

1. **Simple Method (No Server Required):**
   - Simply open `index.html` in your web browser
   - Double-click the file or right-click and select "Open with" your preferred browser

2. **Using a Local Server (Recommended):**
   - If you have Python installed:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # Python 2
     python -m SimpleHTTPServer 8000
     ```
   - Then open `http://localhost:8000` in your browser

   - Or use VS Code Live Server extension
   - Or use any other local development server

## ✨ Features

- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Delete individual tasks
- ✅ Filter tasks (All, Active, Completed)
- ✅ Clear all completed tasks
- ✅ Task counter
- ✅ Local storage persistence (tasks saved in browser)
- ✅ Beautiful, modern UI with animations
- ✅ Fully responsive design
- ✅ Smooth transitions and hover effects

## 🎨 Technologies Used

- **HTML5** - Structure
- **CSS3** - Styling with modern features (gradients, animations, flexbox)
- **Vanilla JavaScript** - No frameworks, pure JS
- **LocalStorage API** - Data persistence

## 📝 Usage

1. Type a task in the input field
2. Click "Add Task" or press Enter
3. Check the checkbox to mark a task as complete
4. Click "Delete" to remove a task
5. Use filter buttons to view All, Active, or Completed tasks
6. Click "Clear Completed" to remove all finished tasks

## 🔧 Customization

- **Colors**: Edit the gradient colors in `css/styles.css` (lines with `#667eea` and `#764ba2`)
- **Fonts**: Change the font-family in `css/styles.css` (line 4)
- **Styling**: All styles are in `css/styles.css` - modify as needed
- **Functionality**: All logic is in `js/app.js` - extend as needed

## 📱 Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## 🎯 Future Enhancements (Optional)

- Add due dates to tasks
- Add task categories/tags
- Add task editing functionality
- Add drag-and-drop reordering
- Add dark mode toggle
- Export/import tasks

---

**Enjoy your task tracking!** 🎉
