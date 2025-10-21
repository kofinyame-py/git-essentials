# git-essentials
# 📝 To-Do List App (Python CLI + GUI)

A beginner-friendly To-Do List App built with Python. Includes both a command-line interface (CLI) and a graphical user interface (GUI) using Tkinter. Tasks are saved locally in a `tasks.json` file using Python's `json` module.

---

## 💡 Features

### ✅ CLI Version
- Add, view, and delete tasks via terminal
- Save tasks to `tasks.json`
- Graceful error handling for empty or missing files

### 🖼️ GUI Version (Tkinter)
- Interactive window with entry box, listbox, and buttons
- Add and delete tasks with one click
- Styled with Montserrat & Open Sans fonts
- Clean layout with soft background and accent colors

---

## 🧪 How to Run

### CLI Version
```bash
python main.py

GUI Version
python gui_todo.py

todo_app/
├── main.py          # CLI version
├── gui_todo.py      # GUI version with Tkinter
├── tasks.json       # Stores tasks as a JSON list
├── README.md        # Project overview
├── requirements.txt # (Optional) Add dependencies if needed
└── .gitignore       # Ignore cache and virtual env folders
