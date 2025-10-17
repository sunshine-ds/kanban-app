# FlowBoard

FlowBoard is a lightweight, responsive web-based Kanban and Idea board application with built-in light and dark themes. It stores boards locally in your browser (localStorage), supports drag & drop between columns, quick card creation, editing, deleting, board creation, export, and an additional dedicated Idea Board out of the box.

Features
- Two preconfigured boards:
  - Project Board: for standard task management
  - Idea Board: for capturing ideas, research, and prototypes (added as requested)
- Light and Dark theme toggle (persists your choice and respects system preference)
- Create new boards quickly
- Create cards by typing in column input and pressing Enter
- Edit card title, tag and details in a modal
- Drag & drop cards between columns
- Clear board content or export a board JSON file
- Responsive UI that works on mobile and desktop
- All data is saved locally (no server required)

Usage
1. Open index.html in any modern browser (Chrome, Firefox, Edge, Safari). No build steps required — this is a single-file application using the Tailwind CDN.
2. Switch between boards using the top-right dropdown. The app includes a pre-built "Idea Board" to capture and manage creative ideas.
3. Add a new card: in any column, type a title in the "Add a card" input and press Enter.
4. Edit a card: click a card to open the edit modal. You can change the title, tag, and details. Save to persist.
5. Move cards: drag a card and drop it into another column. Changes are saved automatically.
6. Theme: click the sun/moon button to toggle between Light and Dark themes. Your choice is saved.
7. Create a new board: click "New Board" and enter a board name. A standard three-column board will be created.
8. Export: click "Export" to download the current board as a JSON file.
9. Clear board: click "Clear" to remove all cards from the current board (confirmation required).

Notes & Customization
- Data persistence: All boards and cards are stored in browser localStorage under the key "flowboard_v1". Clearing site storage or using a private session may remove data.
- Light/Dark theme is stored under "flowboard_theme" in localStorage.
- You can edit the default boards by clearing storage and editing the index.html defaultBoards variable if you want a different seed set.

Accessibility & Design
- Keyboard: Add cards by typing and pressing Enter. Modal fields are focusable and keyboard accessible.
- Responsive: Columns scroll horizontally on small screens; the layout adapts to wide screens naturally.

License
This project is licensed under the MIT License — see the LICENSE file for details.

Enjoy using FlowBoard to manage your projects and ideas!