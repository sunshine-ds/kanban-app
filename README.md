# Kanban Board — Responsive Drag & Drop

A compact, fully responsive Kanban board web application built with Tailwind CSS and vanilla JavaScript. It supports drag-and-drop (desktop) as well as touch-based dragging (mobile), persistent storage using localStorage, task creation/editing/deletion, search filtering, column reordering, JSON export/import, and accessible keyboard interactions.

Features
- 3 default columns: To Do, In Progress, Done
- Drag & drop tasks between columns (desktop and touch/mobile)
- Add, edit, and delete tasks
- Quick add to any column
- Persistent board state in localStorage
- Export board as JSON and import to restore or load another board
- Clear board confirmation
- Column reordering (move left/right)
- Keyboard shortcuts: Ctrl/Cmd+K to focus search, Ctrl/Cmd+N to add a new task
- Responsive layout (1 column on small screens, 2 on medium, 3 on large)
- Accessible: buttons, keyboard controls, ARIA attributes

Usage
1. Open index.html in a modern browser (Chrome, Firefox, Edge, Safari).
2. Add tasks using the "Add Task" button or the quick-add buttons in each column.
3. Drag tasks between columns (desktop: click and drag; mobile: long touch and drag).
4. Edit or delete tasks using the controls on each task card.
5. Use the Menu to export your board as JSON or to import a board. Exported JSON can be saved as a backup.
6. Use the "Clear Board" option to remove all tasks (confirmation required).
7. Column reordering: use the left/right arrow buttons on each column header to change column order.

Notes
- All data is stored locally in your browser (localStorage). Clearing browser storage or switching browsers/devices will not transfer your board unless you export the JSON and import it elsewhere.
- The app aims to be lightweight and dependency-free beyond Tailwind's CDN for styles.

Development
- The entire app lives in a single HTML file (index.html) for simplicity and portability.
- Tailwind CSS is loaded from the official CDN.
- All JavaScript is inline and uses modern browser APIs (Drag & Drop API, Touch events). No build step required.

Accessibility & Keyboard
- Press Enter on a focused task to edit it, or press Delete to remove it (with confirmation for delete button).
- Press Enter while focused on a column to open the Add Task modal targeting that column.

License
This project is released under the MIT License — see the included LICENSE file for details.

Enjoy!
