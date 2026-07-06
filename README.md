# Java Swing Notepad Application

<div align="center">

# Notepad Clone using Java Swing 

A modern desktop text editor built with **Java Swing** that replicates the core functionality of Windows Notepad while demonstrating GUI programming, event handling, dialogs, menus, and customization features.

![Java](https://img.shields.io/badge/Java-Swing-orange)
![GUI](https://img.shields.io/badge/Desktop-Application-blue)
![OOP](https://img.shields.io/badge/OOP-Java-success)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

</div>

---

## Project Description

This project is a GUI-based **Notepad Application** developed using **Java Swing**. It provides a clean and user-friendly interface for creating and editing text documents.

The application includes:

✅ Menu-driven operations

✅ Font customization

✅ Text color customization

✅ Keyboard shortcuts

✅ Scrollable editor

✅ Dialog-based font selection

The project is designed to help students understand the fundamentals of:

* Java Swing
* Event Handling
* GUI Design
* Dialog Windows
* Object-Oriented Programming
* Desktop Application Development

---

# Features

## File Menu

| Feature       | Description                                      |
| ------------- | ------------------------------------------------ |
| New           | Creates a new document                           |
| Open          | Opens an existing file *(future implementation)* |
| Save          | Saves current file *(future implementation)*     |
| Save As       | Save with a new name *(future implementation)*   |
| Page Setup    | Configure page settings                          |
| Print Preview | Preview before printing                          |
| Print         | Print document                                   |
| Close         | Close current document                           |
| Exit          | Close application                                |

---

## Edit Menu

| Feature    | Description                  |
| ---------- | ---------------------------- |
| Undo       | Undo last operation          |
| Redo       | Redo previous operation      |
| Cut        | Remove selected text         |
| Copy       | Copy selected text           |
| Paste      | Paste clipboard content      |
| Delete     | Delete selected text         |
| Find       | Search text                  |
| Find Next  | Search next occurrence       |
| Replace    | Replace text                 |
| Go To      | Jump to a line               |
| Select All | Select complete text         |
| Date/Time  | Insert current date and time |

> ⚠ Currently available as menu placeholders and can be implemented in future versions.

---

## Format Menu

### Font Customization

* Font Family Selection
* Font Style Selection
* Font Size Selection
* Live Preview

### Text Color Selection

* Built-in Color Chooser
* Instant Text Color Change

### Wrap Text

* Menu option available
* Can be implemented in future versions

---

## Window Menu

* Window 1
* Window 2
* Window 3

(Multiple document support can be added in future.)

---

#  Class Diagram Overview

## MainClass

Responsible for:

* Starting the application
* Creating the main frame
* Setting window properties

---

## MainFrame

Responsible for:

* Creating menus
* Managing user actions
* Displaying text editor
* Opening dialogs

---

## FontFrame

Responsible for:

* Displaying font customization dialog

---

## FontPanel

Responsible for:

* Font Selection
* Style Selection
* Size Selection
* Live Preview
* Applying Font Changes

---

# Keyboard Shortcuts

| Shortcut | Action           |
| -------- | ---------------- |
| CTRL + N | New Document     |
| CTRL + L | Close Document   |
| CTRL + E | Exit Application |

---

# User Interface Components

### Swing Components Used

| Component     | Purpose         |
| ------------- | --------------- |
| JFrame        | Main Window     |
| JMenuBar      | Menu Bar        |
| JMenu         | Menus           |
| JMenuItem     | Menu Items      |
| JTextArea     | Text Editing    |
| JScrollPane   | Scroll Support  |
| JDialog       | Font Dialog     |
| JColorChooser | Color Selection |
| JLabel        | Labels          |
| JButton       | Buttons         |
| JList         | Font Lists      |

---

# Technologies Used

| Technology | Purpose          |
| ---------- | ---------------- |
| Java       | Core Programming |
| Swing      | GUI Development  |
| AWT        | Event Handling   |
| OOP        | Software Design  |

---

#  Installation & Execution

## Requirements

* Java JDK 8+
* NetBeans / Eclipse / VS Code

---

## Compile

```bash
javac *.java
```

---

## Run

```bash
java MainClass
```

---

### Main Editor Window

```text
+------------------------------------+
| File Edit Format Window            |
+------------------------------------+
|                                    |
|          Text Editor               |
|                                    |
|                                    |
+------------------------------------+
```

---

### Font Dialog

```text
+------------------------------------+
| Font Dialog                        |
+------------------------------------+
| Name   Style   Size                |
| Arial  Bold    18                  |
|                                    |
| Sample Preview                     |
| AaBbCcDd                           |
|                                    |
| OK      Cancel                     |
+------------------------------------+
```

---

# Learning Objectives

After completing this project, students will gain knowledge of:

✔ Java Swing

✔ GUI Design Principles

✔ Event-Driven Programming

✔ Dialog Box Handling

✔ Object-Oriented Programming

✔ Desktop Software Development

✔ User Interface Design

---

#  Author

**Soumyadeep Basu**

---

