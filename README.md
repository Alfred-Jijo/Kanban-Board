# GoLang Kanban Project

![GoLang Logo](https://github.com/rfyiamcool/golang_logo/blob/master/gif/golang_color.gif)


## Introduction

This small project is a Kanban board implementation in Go, utilizing the [Bubble Tea](https://github.com/charmbracelet/bubbletea) framework for building modern command-line applications and the [Lip Gloss](https://github.com/charmbracelet/lipgloss) styling library for layout and styling.

## Features

- Simple and intuitive CLI interface.
- Manage tasks across three columns: To Do, In Progress, and Done.
- Navigate and modify tasks using keyboard shortcuts.

## Installation

To install this project, you need to have Go installed on your system. Follow these steps:

1. Clone the repository:

2. Navigate to the project directory and run build
    ```bash
    go build .
3. Run it
    ```bash
    go run .

### Keyboard Shortcuts

- `Left` or `h`: Move focus to the left column.
- `Right` or `l`: Move focus to the right column.
- `Enter`: Move the selected task to the next column.
- `n`: Create a new task.
- `Ctrl+C` or `q`: Quit the application.


