# Project: To-Do List App

## Overview:

A simple To-Do List App that allows users to add, view, and delete tasks. The app will store the tasks persistently using UserDefaults (or CoreData for more advanced practice later).

## User Flow:

### 1. Main Screen (Task List View):

- Displays a list of tasks.
- Each task will have a checkbox to mark it as completed.
- There will be a "Add Task" button to add a new task.
- Each task has an option to delete it from the list.

### 2. Add Task Screen:

- Users can tap the "Add Task" button from the main screen to open a modal or new screen where they can input a new task.
- The screen will have:
  - A text field for entering the task name.
  - A "Save" button to save the task and return to the main screen.
  - A "Cancel" button to dismiss the screen without saving.

### 3. Completed Tasks:

- Tasks that are marked as complete will be visually distinguished (e.g., strikethrough text or moved to the bottom of the list).
- You can optionally add a filter to view only "Pending" or "Completed" tasks.

## UI/UX Design:

### 1. Main Screen (Task List)

#### UI Components:

- Navigation Bar: "To-Do List" as the title.
- Task List: A List view showing all tasks. Each list item will have:
  - Text: Task name.
  - Checkbox: A Toggle or Button to mark the task as complete/incomplete.
  - Delete Button: A swipe-to-delete gesture or a trash icon to remove a task.
- Add Task Button: At the bottom right (Floating Action Button) to navigate to the Add Task screen.

#### UX Considerations:

- Clear, minimal design. Tasks are easy to read, and users can quickly mark them as complete or delete them.
- The "Add Task" button is always visible for easy task creation.
- Marking a task as completed instantly updates the UI, making it intuitive.

### 2. Add Task Screen

#### UI Components:

- Text Field: To enter the task name.
- Save Button: To save the task.
- Cancel Button: To dismiss the Add Task screen without saving.

#### UX Considerations:

- The "Save" button is disabled until the user types in a task name to prevent saving empty tasks.
- The "Cancel" button allows users to exit without saving, giving them a sense of control.

## Next Steps / Enhancements:

- Persistence: Add UserDefaults or CoreData to persist tasks between app launches.
- Completed Task Filter: Add functionality to filter tasks by "Completed" or "Pending" status.
- Animations: Add subtle animations (e.g., tasks sliding out when deleted or task completion animations).
- Customizations: Implement themes or settings, like dark mode or custom colors for task priorities.
