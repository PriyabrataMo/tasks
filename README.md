# Tasks CLI

Tasks CLI is a command-line todo application that helps you manage your tasks efficiently.

## Features

- **Add** tasks
- **Remove** tasks
- **Mark** tasks as done
- **List** all tasks

## Installation

1. Tap & Install via Homebrew:
    ```bash
    brew tap PriyabrataMo/homebrew-taps
    brew install tasks
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

## Uninstall
```sh
brew uninstall tasks
```

## Troubleshooting
• "Command Not Found" → try:
```sh
brew link tasks
```
• Permission issues → consider:
```sh
sudo brew install tasks
```

## License
MIT License

## Contributing
Open issues or submit pull requests.

## Support
Give a ⭐ on GitHub.