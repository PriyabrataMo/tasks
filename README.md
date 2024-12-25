# Tasks CLI

Tasks CLI is a command-line todo application that helps you manage your tasks efficiently.

## Features

- **Add** tasks
- **Remove** tasks
- **Mark** tasks as done
- **List** all tasks

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/PriyabrataMo/tasks-cli
    ```
2. Build the executable:
    ```bash
    cd tasks-cli
    go build
    ```
3. Move the executable to `/usr/local/bin`:
    ```bash
    mv tasks-cli /usr/local/bin
    ```

## Usage

```bash
tasks add [task name]
tasks remove [task id]
tasks done [task id]
tasks list
```

## Example

Add a new task:
```bash
tasks add "Buy groceries"
```

List all tasks:
```bash
tasks list
```