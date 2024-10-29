# Setting-Up-a-Nginx-Web-Server

This guide provides instructions to set up a basic Nginx web server. Nginx is a high-performance web server and reverse proxy that is often used to serve static files, load balance, and act as a reverse proxy.

## Prerequisites

- A server with a Debian-based OS (Ubuntu is used in this example).
- Root access or a user with `sudo` privileges.
- Nginx installed (if not, install it by following the installation steps below).

## Installation

### Step 1: Update Package Index

Before installing Nginx, update the package index on your server:

```bash
sudo apt update
