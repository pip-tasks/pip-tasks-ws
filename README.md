# <img src="https://github.com/pip-tasks/pip-tasks-ps/raw/master/artifacts/logo.png" alt="Pip.Devs Logo" style="max-width:30%"> <br/> Workspace for Pip.Tasks

This is a workspace for [Pip.Tasks](https://github.com/pip-tasks/pip-tasks) project build infrastructure:

- **pip-tasks-ps** - cross-platform project build system in Powershell
- **pip-tasks-common-ps** - common build tasks
- **pip-tasks-dotnet-ps** - .NET build tasks
- **pip-tasks-java-ps** - Java build tasks
- **pip-tasks-js-ps** - Javascript and Node.js build tasks
- **pip-tasks-python-ps** - Python build tasks
- **pip-tasks-all-ps** - Integrated Powershell module

## Installation

- Clone this workspace to local disk
```bash
> git clone https://github.com/pip-tasks/pip-tasks-ws.git
```

- Add the workspace folder to **PSModulePath**

- Manually clone pip-tasks modules
```bash
> git clone https://github.com/pip-tasks/pip-tasks-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-common-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-dotnet-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-java-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-js-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-python-ps.git
> git clone https://github.com/pip-tasks/pip-tasks-all-ps.git
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
