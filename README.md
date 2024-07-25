# OpenCPU Server Deployment

This repository contains the GitHub Actions workflow to deploy an OpenCPU server on an Ubuntu instance.

## Setup

1. Generate an SSH key pair and add the public key to your cloud server.
2. Add the private key as a GitHub secret named `SSH_PRIVATE_KEY`.
3. Modify the `main.yml` workflow file with your server's IP address and domain name.

## Deployment

1. Push any changes to the `main` branch.
2. The GitHub Actions workflow will automatically deploy and configure the OpenCPU server.
3. Access your server at `https://your-server-domain/ocpu`.

## Files

- **.github/workflows/main.yml**: The GitHub Actions workflow file.
- **README.md**: This instruction file.
