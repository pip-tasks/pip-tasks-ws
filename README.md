# <img src="https://github.com/pip-tasks/pip-tasks/raw/master/artifacts/logo.png" alt="Pip.Devs Logo" style="max-width:30%"> <br/> Workspace for Pip.Tasks

This is a workspace for [Pip.Tasks](https://github.com/pip-tasks/pip-tasks) project build infrastructure:

- **pip-tasks** - cross-platform project build system in Powershell
- **pip-tasks-common** - common build tasks
- **pip-tasks-dotnet** - .NET build tasks
- **pip-tasks-java** - Java build tasks
- **pip-tasks-js** - Javascript and Node.js build tasks
- **pip-tasks-python** - Python build tasks
- **pip-tasks-all** - Integrated Powershell module

## Installation

- Clone this workspace to local disk
```bash
> git clone https://github.com/pip-tasks/pip-tasks-ws.git
```

- Add the workspace folder to **PSModulePath**

- Manually clone pip-tasks modules
```bash
> git clone https://github.com/pip-tasks/pip-tasks.git
> git clone https://github.com/pip-tasks/pip-tasks-common.git
> git clone https://github.com/pip-tasks/pip-tasks-dotnet.git
> git clone https://github.com/pip-tasks/pip-tasks-java.git
> git clone https://github.com/pip-tasks/pip-tasks-js.git
> git clone https://github.com/pip-tasks/pip-tasks-python.git
> git clone https://github.com/pip-tasks/pip-tasks-all.git
```

## Usage

- Setting default workspace
```bash
> pipuse <Path to this workspace>
```

- Test all components
``` bash
> piptask test -all
```

- Check out changes from remote repository
```bash
> piptask pull -all
```

- Check in changes to remote repository
```bash
> piptask push -m <Changes comment> -all
```

## Acknowledgements

The Pip.Tasks workspace is created and maintained by **Sergey Seroukhov**
