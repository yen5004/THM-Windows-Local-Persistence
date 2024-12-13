To check which services are currently running on a Windows system via the Command Prompt, you can use the following methods:

### 1. **Using `sc query` command**
The `sc query` command displays information about the services on your system.

- To list all services and their statuses, open Command Prompt and type:
  ```cmd
  sc query
  ```

  This will show the list of services along with their status (e.g., `RUNNING`, `STOPPED`).

- To check the status of a specific service, type:
  ```cmd
  sc query <service_name>
  ```
  Replace `<service_name>` with the name of the service. For example:
  ```cmd
  sc query wuauserv
  ```
  This will check the status of the Windows Update service (`wuauserv`).

### 2. **Using `tasklist` command**
If you want to see the running processes (which may be related to services), you can use the `tasklist` command.

- To list all running processes:
  ```cmd
  tasklist
  ```

  This will give you a list of all processes, including services that are running as part of processes.

### 3. **Using `net start` command**
The `net start` command displays all services that are currently running.

- To view running services:
  ```cmd
  net start
  ```

  This will list all services that are started and running.

### 4. **Using `Get-Service` (PowerShell)**
Though this isn't a CMD-specific command, you can run PowerShell commands from CMD.

- To get a list of running services using PowerShell, use:
  ```cmd
  powershell Get-Service
  ```

This will give you a detailed list of all services and their status.

These commands should help you find and manage running services in Windows via the command line.
