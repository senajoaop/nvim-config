# Neovim Configuration Repository

This repository contains all the necessary configurations for the Neovim application. It provides a comprehensive set of configuration files and plugins to enhance your Neovim experience.

## Usage

To use the configurations from this repository, you have two options:

### Option 1: Complete Version

1. Clone the repository: `git clone https://github.com/senajoaop/nvim_config.git`
2. Copy all the files from the cloned repository to the Neovim configuration folder on your operating system.
   - For Windows:
     - Open a command prompt or PowerShell.
     - Run the following command to navigate to the Neovim configuration folder: `cd %USERPROFILE%\AppData\Local\nvim`
     - Copy the files from the cloned repository to the current directory: `xcopy /E /Y path\to\cloned\repository\* .`
   - For Linux distributions:
     - Open a terminal.
     - Run the following command to navigate to the Neovim configuration folder: `cd ~/.config/nvim`
     - Copy the files from the cloned repository to the current directory: `cp -R path/to/cloned/repository/* .`

### Option 2: New Version

1. Clone the repository: `git clone https://github.com/senajoaop/nvim_config.git`
2. Copy only the `new_version/nvim` folder from the cloned repository to the Neovim configuration folder on your operating system.
   - For Windows:
     - Open a command prompt or PowerShell.
     - Run the following command to navigate to the Neovim configuration folder: `cd %USERPROFILE%\AppData\Local\nvim`
     - Copy the `new_version\nvim` folder from the cloned repository to the current directory: `xcopy /E /Y path\to\cloned\repository\new_version\nvim .`
   - For Linux distributions:
     - Open a terminal.
     - Run the following command to navigate to the Neovim configuration folder: `cd ~/.config/nvim`
     - Copy the `new_version/nvim` folder from the cloned repository to the current directory: `cp -R path/to/cloned/repository/new_version/nvim/* .`

## Neovim Configuration Folder Location

The Neovim configuration folder is typically located in the following directories on different operating systems:

- For Windows: `%USERPROFILE%\AppData\Local\nvim`
- For Linux distributions: `~/.config/nvim`

Please note that the paths provided above are default locations. If you have a customized Neovim configuration folder, please adjust the commands accordingly.

## Contributing

Contributions to this repository are welcome! If you have any improvements, suggestions, or bug fixes, please feel free to contribute by following these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "Add your commit message"`
4. Push the branch to your forked repository: `git push origin feature/your-feature-name`
5. Open a pull request to the main repository.

Please ensure that your contributions align with the existing coding style and best practices.
