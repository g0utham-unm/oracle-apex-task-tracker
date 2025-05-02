
# 🗂️ Oracle APEX Task Tracker

A project and task management system built using **Oracle APEX**. This low-code web application enables users to manage projects, assign tasks, track task progress, log comments, and maintain a full audit trail of changes — all through an interactive dashboard and clean UI.

## 🚀 Features

- 🧾 **Task Management**: Create, edit, assign, and categorize tasks by status and priority.
- 👥 **User Roles**: Define roles like Developer, Tester, Admin with task assignments.
- 🗓️ **Project Tracking**: Maintain timelines with start and end dates.
- 💬 **Comments**: Users can add updates or notes on tasks.
- 🔄 **Task History**: Track what changed, when, and by whom.
- 📊 **Dashboard**: Visual reports for tasks by status, priority, and project.
- 🧠 **Audit Logic**: Automatically records status changes and who made them.

## 🏗️ Built With

- Oracle APEX (Application Express)
- Oracle SQL & PL/SQL
- Interactive Grids, Forms, Charts, and Dynamic Actions


## 📁 Project Structure

```
oracle-apex-task-tracker/
├── app/
│   └── task_tracker.sql        # APEX application export
├── database/
│   ├── create_tables.sql       # Table creation scripts (optional)
│   └── insert_sample_data.sql  # Demo data (optional)
├── screenshots/                # App screenshots
├── README.md                   # Project overview
└── LICENSE                     # Optional open-source license
```

## 🛠️ Setup Instructions

1. **Oracle APEX Setup**  
   - Import `task_tracker.sql` into your Oracle APEX workspace.

2. **Database Schema (if needed)**  
   - Run `create_tables.sql` and `insert_sample_data.sql` in SQL Workshop.

3. **Run the App**  
   - Set up authentication if needed (e.g., App Users)
   - Launch from APEX dashboard.

## 📌 Notes

- This project was originally created for learning and portfolio use.
- The APEX dynamic actions and PL/SQL processes help demonstrate low-code event handling.

## 👨‍💻 Author

**Sai Goutham Panamgipalli**  
🔗 [LinkedIn](https://www.linkedin.com/in/saigouthampanamgipalli/) | 📧 [Email](saigoutham.panamgipalli@gmail.com)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
