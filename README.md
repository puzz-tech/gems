# GEMS

GEMS is the Game Event Management System, an application for managing the logistics of running a "Game".  A Game is a
large, multi-day event that involves many participants and staff.

[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/puzz-tech/gems)

## Getting Started

This repo uses [DevContainers] to enable getting setup with all the development dependencies quickly and easily. Using a
DevContainer requires that you have VSCode and Docker installed but it should minimize the getting started friction
after that initial setup. Follow the [DevContainers Getting Started] instructions for more detail.

1. Install and run [VSCode].
2. Install Docker by running the `Dev Containers: Install Docker` command from the command palette.
3. Run the `Dev Containers: Clone Repository in Container Volume...` command from the command palette.
4. Enter the URL of this repo: `https://github.com/puzz-tech/gems`.
5. A Docker container will get created and launched and VSCode will be attached to it.  This may take a few minutes the
   first time.  Any work you do in VSCode will be done in the container.

### Manual Setup

When you clone a repository in a container volume it will be available in the container but not on your local machine.
This means that you must be running the VSCode in the container to access the code.  If you want to be able to access
the code from your local machine you can clone the repo manually and then open it in a DevContainer.

> Note: When cloning locally, you may experience performance issues on Windows an MacOS.  Using a container volume is
> the recommended solution for the best performance.

1. Clone the repo

   ```bash
   git clone https://github.com/puzz-tech/gems
   ```

2. Open it up in [VSCode]

   ```bash
   code gems
   ```

3. VSCode should prompt you to reopen the repo in a DevContainer.  If not, you can open the command palette and search
   for `Remote-Containers: Reopen in Container`.

[VSCode]: https://code.visualstudio.com/
[DevContainers]: https://code.visualstudio.com/docs/devcontainers/containers
[DevContainers Getting Started]: https://code.visualstudio.com/docs/devcontainers/containers#_getting-started
