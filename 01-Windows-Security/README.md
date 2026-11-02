# Windows Security Fundamentals

## Objective

Learn the basic structure of Windows, understand how Windows manages users, processes and services, and explore its built-in security tools.

## Topics to Learn

- Windows operating system fundamentals
- Users and groups
- Processes and services
- File systems and permissions
- Windows Task Manager
- Windows PowerShell
- Windows Event Viewer
- Windows Defender
- Windows Firewall

## Practical Activities

- Inspect system information using PowerShell.
- Explore running processes and services.
- Examine Windows Security logs.
- Understand basic security events.

## Investigation Reports

Reports and screenshots will be added as practical activities are completed.



## Lesson 1: Windows Fundamentals

### Topics Covered

1. Operating System
2. Kernel
3. Process
4. Thread
5. Windows Services
6. User Accounts

### Practical Commands

| Command | Purpose |
|---|---|
| `Get-ComputerInfo` | Displays system information |
| `Get-Process` | Lists running processes |
| `Get-Service` | Lists Windows services |
| `Get-LocalUser` | Lists local user accounts |
| `whoami` | Displays current username |
| `whoami /groups` | Displays current user's group memberships |

### Practical Learning

- Explored running processes using Task Manager.
- Inspected processes using PowerShell.
- Explored Windows background services.
- Inspected local user accounts.

### Cybersecurity Relevance

Understanding processes, services, users, and operating-system components provides a foundation for SOC monitoring, security investigations, and digital forensics.

### Learning Status

In Progress


## Lesson 2: Windows Users, Groups & Permissions

### Topics Covered

- Windows user accounts
- Standard users and administrators
- Local user groups
- File and folder permissions
- Access control
- Privilege escalation

### Practical Commands

| Command | Purpose |
|---|---|
| `Get-LocalUser` | Lists local user accounts |
| `Get-LocalGroup` | Lists local groups |
| `Get-LocalGroupMember` | Displays group members |
| `whoami` | Displays current user |
| `Get-Acl` | Inspects file and folder permissions |

### Practical Activities

- Inspected local Windows user accounts.
- Explored local security groups.
- Checked Administrators group membership.
- Created a test folder and file.
- Inspected folder permissions using PowerShell.

### Cybersecurity Relevance

Understanding users, groups and permissions helps security analysts investigate unauthorized access, suspicious account activity and privilege escalation.

### Learning Status

In Progress
