# IAM Access Control Project

## Scenario

A company has three types of users:

### Admin
Responsibilities:
- Manage cloud resources
- Manage IAM settings

Permissions:
- Full access

### Developer
Responsibilities:
- Create test servers
- Deploy applications

Permissions:
- Create and modify resources
- No IAM access

### Read-Only User
Responsibilities:
- Monitor resources

Permissions:
- View only

## Security Principles

### Least Privilege
Users receive only the permissions required for their job.

### Role-Based Access Control (RBAC)
Permissions are assigned through roles rather than individually.

## Project Status

Phase 1: Design Complete
Phase 2: Implementation In Progress
## Access Matrix

| Role | View Resources | Create Resources | Modify Resources | Delete Resources | Manage IAM |
|--------|--------|--------|--------|--------|--------|
| Admin | Yes | Yes | Yes | Yes | Yes |
| Developer | Yes | Yes | Yes | No | No |
| Read-Only User | Yes | No | No | No | No |

🚀 Project Started
