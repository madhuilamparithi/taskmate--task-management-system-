# TASKMATE – TASK MANAGEMENT APP
## Software Requirements Specification (SRS)

### 1. Introduction

**1.1 Purpose**

The purpose of TaskMate is to develop a task management application that helps users create, organize, update, and track their daily tasks efficiently.

**1.2 Scope**

TaskMate provides a centralized interface for managing tasks, setting priorities and deadlines, monitoring progress, and viewing task statistics.

**1.3 Intended Users**

- Students
- Individual users
- People who want to organize daily activities

### 2. Functional Requirements

Functional requirements describe what the application must do.

| ID | Requirement |
|---|---|
| FR01 | The system shall allow users to log in. |
| FR02 | The system shall validate login credentials. |
| FR03 | The system shall allow users to create new tasks. |
| FR04 | The system shall allow users to view their task list. |
| FR05 | The system shall allow users to edit existing tasks. |
| FR06 | The system shall allow users to delete tasks. |
| FR07 | The system shall allow users to assign task categories. |
| FR08 | The system shall allow users to set task priorities as High, Medium, or Low. |
| FR09 | The system shall allow users to set task due dates. |
| FR10 | The system shall organize tasks by status: To Do, In Progress, and Completed. |
| FR11 | The system shall provide a calendar to view tasks by date. |
| FR12 | The system shall display task statistics and completion progress. |
| FR13 | The system shall allow users to manage profile and application preferences. |
| FR14 | The system shall allow users to log out. |

### 3. Non-Functional Requirements

These describe the quality and performance expected from the application.

- **Usability:** The interface should be simple and easy to understand.
- **Performance:** Pages and task operations should respond promptly.
- **Reliability:** The application should handle task operations consistently.
- **Security:** User credentials and personal information should be protected.
- **Maintainability:** The code should be organized for easier updates.
- **Compatibility:** The application should work in supported modern web browsers.
- **Responsiveness:** The interface should adapt to desktop, tablet, and mobile screens.

### 4. Hardware Requirements

- Computer or laptop
- Minimum 4 GB RAM recommended
- Keyboard and mouse or touch input
- Internet connection if online services are used

### 5. Software Requirements

- Operating system: Windows, Linux, or macOS
- Web browser: Google Chrome, Microsoft Edge, or Firefox
- Code editor: Visual Studio Code (recommended)
- Version control: Git
- Repository hosting: GitHub

### 6. User Stories

| ID | User Story |
|---|---|
| US01 | As a user, I want to log in so that I can access the application. |
| US02 | As a user, I want to add tasks so that I can record my activities. |
| US03 | As a user, I want to edit tasks so that I can correct task details. |
| US04 | As a user, I want to delete tasks that are no longer needed. |
| US05 | As a user, I want to set priorities so that I can identify important tasks. |
| US06 | As a user, I want to track task status so that I can monitor progress. |
| US07 | As a user, I want to view a calendar so that I can manage deadlines. |
| US08 | As a user, I want to view analytics so that I can understand my productivity. |

### 7. Project Scope

**In Scope**
- Login interface
- Task creation, viewing, editing, and deletion
- Task priorities and due dates
- Kanban board
- Calendar view
- Analytics dashboard
- Profile and settings interface

**Out of Scope for the Initial Version**
- Real-time collaboration
- Advanced AI task recommendations
- Third-party calendar synchronization
- Mobile application development

### 8. Assumptions and Constraints

- Users have access to a compatible web browser.
- The initial prototype focuses on the core task management workflow.
- Database integration and authentication depend on the selected implementation.
- The final features depend on the team's development time and available resources.

### 9. Acceptance Criteria

The project will be considered ready for demonstration when:

1. The implemented login flow behaves as expected.
2. Users can add and view tasks.
3. Users can edit and delete tasks.
4. Task priorities, dates, and statuses work correctly.
5. Implemented dashboard modules display the appropriate information.
6. The team has executed test cases and documented actual results.
7. The README, workflow diagram, wireframes, and presentation are prepared.

### 10. Conclusion

The TaskMate requirements define the features, quality expectations, project boundaries, and acceptance criteria for developing a task management application. They guide the team through design, implementation, testing, and final presentation.
