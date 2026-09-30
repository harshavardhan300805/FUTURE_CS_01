# Vulnerability Assessment Report – Cyber Security Task 1

## Overview

This repository contains my Vulnerability Assessment Report completed as part of Cyber Security Task 1.

The assessment was conducted using a read-only and non-destructive approach to identify common security configuration weaknesses on a publicly accessible website.

## Website Tested

**Target Website:**

https://harshavardhan300805.github.io/NexMinds-FS-Developer-Assessment/

## Scope

### In Scope

- Publicly accessible website pages
- HTTP/HTTPS response headers
- Security header configuration
- Basic service exposure
- Passive vulnerability scanning
- Publicly accessible resources

### Out of Scope

The following activities were not performed:

- Login bypass
- Authentication attacks
- Brute-force attacks
- Denial-of-service testing
- Exploitation of vulnerabilities
- Destructive testing
- Unauthorized access

The assessment was performed using a read-only and non-destructive methodology.

## Tools Used

### 1. Nmap

Used for basic service and port exposure analysis.

Command used:

```bash
nmap -sV harshavardhan300805.github.io
