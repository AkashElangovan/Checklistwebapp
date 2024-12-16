https://akashelangovan.github.io/Checklistwebapp/
# Enhanced Checklist - Dark Theme

An interactive, customizable checklist application with group functionality, dark theme styling, and local storage for data persistence.

## Features
- **Dark Theme**: Modern and visually appealing dark interface.
- **Group Management**: Create, delete, and manage multiple groups.
- **Item Management**: Add, delete, and toggle checklist items.
- **Drag and Drop Effect**: Checked items are sorted at the bottom of the list automatically.
- **Persistent Storage**: Groups and items are stored in the browser's local storage.

## Table of Contents
1. [Demo](#demo)
2. [Getting Started](#getting-started)
3. [Usage](#usage)
4. [Customization](#customization)
5. [Contributing](#contributing)
6. [License](#license)

---

## Demo
1. Add a new group by clicking "Create New Group."
2. Add items to a group using the input box and the "Add" button.
3. Check items to mark them as complete and automatically move them to the bottom.
4. Delete groups or individual items with the respective buttons.

---

## Getting Started

### Prerequisites
- A modern web browser with JavaScript enabled.

### Installation
1. Clone the repository or copy the `HTML` file.
2. Open the file in your browser.

### Local Storage
Your changes are automatically saved in your browser's local storage. Closing and reopening the page will retain your groups and items.

---

## Usage

### Creating a Group
1. Click the **"Create New Group"** button.
2. Enter the group name in the prompt dialog.

### Adding Items
1. Type a new item in the input box within a group.
2. Click the **"Add"** button to save the item.

### Marking Items as Complete
1. Check the box next to an item.
2. Completed items are automatically moved to the bottom of the list.

### Deleting Items or Groups
1. Click the ❌ next to an item to delete it.
2. Click the 🗑️ next to a group to delete the group.

---

## Customization

### Style Adjustments
- Modify the `style` section in the `<head>` of the file to adjust themes, colors, and layout.
- Key CSS variables:
  - `background-color`: Adjusts the overall background.
  - `color`: Controls text color.

### Adding Functionality
Enhance functionality by editing the `<script>` section, e.g.:
- Adding due dates to items.
- Implementing drag-and-drop sorting.

---

## Contributing
Contributions are welcome! Feel free to:
- Submit issues for bugs or feature requests.
- Fork and submit a pull request with your changes.

---

## License
This project is licensed under the MIT License.

