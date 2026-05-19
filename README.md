FlowBoard Task Manager

A dark, modern task management web application built as a single-file frontend project. It turns a simple to-do experience into a richer workspace with projects, priorities, status stages, filters, analytics, list view, and Kanban-style board view.
<a href:"https://taskmanager-d8l.pages.dev/" alt="webpage workin progress">WEBPAGE</a>
Overview

FlowBoard Task Manager is designed as a lightweight personal productivity workspace that feels closer to a real task manager than a plain checklist. Modern task management products commonly include multiple task views, progress visibility, project grouping, and workflow stages, which shaped the structure of this app.

The project currently runs as a static web app with local browser storage, so it is easy to open, test, and deploy without a backend. That makes it useful both as a personal tool and as a frontend prototype for future expansion into a larger SaaS-style product.​
Features

    Create, edit, and remove tasks with title, description, project, assignee, tags, due date, priority, and workflow status.​

    Switch between a detailed list view and a Kanban-style board view for different planning styles.

    Filter tasks by project, priority, status, completion state, and free-text search.

    Track progress with summary metrics for total tasks, in-progress tasks, completed tasks, and overdue tasks.

    Save data locally in the browser for a simple no-backend workflow.​

Interface

The visual design uses a dark dashboard approach with glass-like panels, strong contrast, and a focused workspace layout. Dark Kanban and task dashboard inspiration often emphasize grouped columns, compact metric cards, and high-information control surfaces, which influenced this interface direction.

The layout is split into three main parts:
Area	Purpose
Top bar	Shows app identity, workspace summary, and sort controls.
Left sidebar	Handles task creation, editing, deletion, and project overview.
Main workspace	Displays metrics, filters, list view, and board view.
Tech Stack
Layer	Choice
Markup	HTML5
Styling	CSS3
Logic	Vanilla JavaScript
Persistence	Browser localStorage
Deployment	Static hosting

This architecture keeps the app fast to run and simple to maintain. It also makes the project easy to deploy on static platforms such as GitHub Pages, Netlify, or Vercel because no server-side runtime is required.​
Project Structure

text
FlowBoard Task Manager/
└── todo-webapp.html

The project is intentionally kept as a single-file web app for easy portability. All layout, styling, and interaction logic live in one HTML file, which is convenient for fast iteration and quick sharing.
Getting Started
Run locally

    Download or clone the project.

    Open todo-webapp.html in a modern browser.

    Start creating tasks.

Because this is a static frontend app, no package manager or build step is required. Task data is stored in the browser, so it remains available between sessions on the same device and browser profile.
Usage
Create a task

Fill in the task editor with a title, optional description, project, assignee, priority, status, due date, and tags, then save it. This structure reflects the broader feature set expected in task management software, where tasks are typically grouped, categorized, and tracked across workflow stages.
Manage work visually

Use List View when scanning lots of detail, and switch to Board View when thinking in terms of workflow stages such as To Do, In Progress, Review, and Done. Board-based organization is a core pattern in Kanban-inspired task management interfaces.
Track progress

The summary cards at the top of the workspace surface the operational state of your tasks, including totals, active work, completed work, and overdue items. This reflects the dashboard emphasis seen in many task management systems, where quick progress visibility matters as much as task entry itself.
Roadmap

Planned improvements that would make the project feel even more like a full task management platform include:

    Drag-and-drop movement across board columns.

    Calendar or timeline planning view.​

    Recurring tasks and reminders.​

    Activity history and comments.

    Team collaboration and multi-user support.

    Backend persistence with authentication and cloud sync.​

Deployment

This project can be deployed as a static site. Good deployment targets include GitHub Pages, Netlify, and Vercel, since the app is frontend-only and does not depend on a server runtime.​
Why this project exists

The project began as a JavaFX to-do application and then evolved into a richer web-based task manager with a more flexible interface and product-style layout. Moving to the web made it easier to experiment with dashboard structure, Kanban workflows, and responsive interaction patterns while keeping the app easy to run and share.
