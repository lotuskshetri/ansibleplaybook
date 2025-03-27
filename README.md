# ansibleplaybook

a. Setup
An EC2 instance was launched using a specified AMI.

A security group was configured to allow SSH (port 22) and HTTP/HTTPS (ports 80 & 443).

Ansible was installed on the control machine to manage the EC2 instance.

b. A playbook was written to perform the following tasks:
System Update and Package Installation

Updated all system packages.

Installed Nginx web server.

Enabled and started the Nginx service.

Website Hosting Configuration

Created directories for hosting web pages.

Added an index.html file for /page1 and /page2.

Generated an Nginx configuration file to serve both pages.

Restarted Nginx to apply changes.

HTTPS Configuration

Generated a self-signed SSL certificate using OpenSSL.

Updated Nginx configuration to enable HTTPS on port 443.

Restarted Nginx to enforce SSL.

SSH Authentication Setup

The local machine’s public SSH key was added to the EC2 instance for secure, passwordless authentication.
