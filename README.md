Certainly! Here's the revised README.md file:

```markdown
# internsctl - Custom Linux Command for Operations

**Command Version:** v0.1.0

## Overview

`internsctl` is a custom Linux command designed to simplify various system operations. It provides functionalities related to CPU information, memory information, user management, and file information.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
  - [CPU Information](#cpu-information)
  - [Memory Information](#memory-information)
  - [User Management](#user-management)
  - [File Information](#file-information)
- [Contributing](#contributing)
- [License](#license)

## Installation

To use `internsctl`, follow these installation steps:

```bash
git clone https://github.com/your-username/internsctl.git
cd internsctl
chmod +x internsctl
sudo mv internsctl /usr/local/bin/
```

## Usage

Run `internsctl --help` to see the available commands and options.

```bash
internsctl --help
```

## Commands

### CPU Information

Get CPU information:

```bash
internsctl cpu getinfo
```

### Memory Information

Get memory information:

```bash
internsctl memory getinfo
```

### User Management

Create a new user:

```bash
internsctl user create <username>
```

List all regular users:

```bash
internsctl user list
```

List users with sudo permissions:

```bash
internsctl user list --sudo-only
```

### File Information

Get information about a file:

```bash
internsctl file getinfo <file-name>
```

To obtain specific information about the file, use options:

- To get the size of the file:

  ```bash
  internsctl file getinfo --size <file-name>
  ```

- To get file permissions:

  ```bash
  internsctl file getinfo --permissions <file-name>
  ```

- To get the owner of the file:

  ```bash
  internsctl file getinfo --owner <file-name>
  ```

- To get the last modified time:

  ```bash
  internsctl file getinfo --last-modified <file-name>
  ```

## Contributing

Contributions are welcome! Follow the steps in the [Contribution Guidelines](CONTRIBUTING.md) to contribute to this project.

## License

This project is licensed under the [MIT License](LICENSE).
```

Make sure to replace `<username>` with the actual values relevant to your project. If you don't have specific contribution guidelines, you can remove the reference to the CONTRIBUTING.md file from the README.
