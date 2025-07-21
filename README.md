# Robot-Monitoring-Dashboard
### Display robot task logs in real-time
### Provide role-based filtering (Admin sees all; Employee only their robots)
### Enable task-type filtering via dropdown
### Visualize task statuses dynamically

## 📦 Features & Implementation

Role-Based Access:Admin: all logsEmployee: only assigned robots

Auto-Refresh:Logs + chart update every 5 seconds via setInterval

Task Filter:Dropdown lists unique tasks; updates table/chart

Charts:Mini pie-chart shows distribution of task statuses (completed/failed/in-progress)

## Technical Highlights

FastAPI for quick REST setup

React + Axios + Chart.js = responsive UI

Simple OAuth2 simulation

SQLite + SQLAlchemy = easy DB layer
