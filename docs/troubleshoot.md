# Troubleshooting Guide: Using Git on VSCode

## Overview

This troubleshooting guide provides solutions to common issues that users may encounter while using VS Code following this user guide.

### Missing Installation

If you encounter errors related to missing installations of [Visual Studio Code](./index.md) or [Git](https://github.com/git-guides/install-git), ensure that both are properly installed on your system.

### Failure to Initialize Repository

If you're unable to initialize a local Git repository in VS Code, double-check that you're in the correct folder or workspace where you want the repository to be created. Ensure that you've followed the steps outlined in the documentation accurately.

### Connection Issues

If you're experiencing difficulties connecting your local repository to a remote repository, ensure that you've copied the correct repository URL and that there are no typos in the `git remote add origin <repository URL>` command. Refer to [this troubleshooting guide](./Troubleshooting_Remote_Repository_Connection.md) for more details.

### Authentication Errors

If you encounter authentication errors while trying to push changes to a remote repository, verify that you have the necessary permissions to push to the repository. You may need to authenticate using SSH keys or provide your credentials.
