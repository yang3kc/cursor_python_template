# Introduction

This repo contains a collection of cursor rules for my Python projects.

Check out the [.cursor](./.cursor) folder for the rules.

# Installation

This repository provides two scripts:
- `init_cursor_python.sh`: Copies cursor rules to your project directory
- `install.sh`: Creates a system-wide or user-specific installation of the `init_cursor_python` command

## Quick Setup

1. Clone this repository
2. Run the install script with your preferred installation path:
```bash
# For user-specific installation (recommended)
./install.sh ~/bin

# For system-wide installation (requires sudo)
sudo ./install.sh /usr/local/bin
```

## Usage

After installation, you can initialize cursor rules in any Python project by running:
```bash
init_cursor_python
```

This will:
- Create a `.cursor` directory in your current project if it doesn't exist
- Copy any new cursor rules from the source directory
- Preserve any existing cursor rules you may have modified