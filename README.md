# AWS EC2 Deployment

## Objective
Deploy and configure Linux EC2 instances with Apache web server on AWS for production-ready hosting.

## Tools Used
- AWS Free Tier Account
- Amazon EC2 (Elastic Compute Cloud)
- Linux (RHEL)
- Apache Web Server
- SSH Key Pair

## Implementation Steps
1. Logged into AWS Management Console
2. Launched 2 Linux EC2 instances with appropriate instance type
3. Created and configured SSH key pair for secure access
4. Connected to EC2 instance via SSH key-based authentication
5. Installed and configured Apache web server
6. Configured AWS Security Groups with inbound/outbound rules
   - Port 22 (SSH)
   - Port 80 (HTTP)
   - Port 443 (HTTPS)
7. Verified server functionality across multiple scenarios

## Security Groups Configuration
| Port | Protocol | Purpose |
|------|----------|---------|
| 22   | SSH      | Secure remote access |
| 80   | HTTP     | Web traffic |
| 443  | HTTPS    | Secure web traffic |

## Result
Successfully deployed 2 Linux EC2 instances with Apache web server,
secured with SSH key-based authentication and AWS Security Groups.
