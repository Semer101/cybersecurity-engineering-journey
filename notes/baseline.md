# Baseline Diagnostic

**Date:** 2026-09-21

## Questions

### Python

- What is a function?
- What's the difference between a list and dictionary?
- How do you read a file?

### Linux

- What does `chmod` do?
- What's the difference between `/home` and `/etc`?
- What does `ps` show?

### Networking

- What is an IP address?
- What is a port?
- TCP vs UDP?
- What does DNS do?
- What happens when you type a URL into a browser?

### Web

- HTTP vs HTTPS?
- What is an HTTP request?
- What is a cookie?
- Authentication vs authorization?

### Security

- CIA triad?
- Vulnerability vs threat?
- What is SQL injection?
- What is least privilege?


# Original Answers

## Python

A function is used to place a repititive block of code that can be reused with other parameters so that we don't repeat ourselves and keep the code clean and DRY.

A list is not ordered while a dictionary has a key and a value i think.

I read a file by running the code not sure.

## Linux

Chmod changes the owner.

`/home` is the desktop version of linux and `/etc` contains detailed configuration files.

Do not know.

## Networking

An ip address is used to identify a device on the internet/network.

A port is used so that multiple devices/apps can use the same ip address but with their unique port number easy to identify them on the network.

Tcp is more secure with its 3 way handshake while udp is unreliable, unsecure(not encrypted) but good for live streams of videos.

DNS - domain naming system provides ip addresses to domain names eg: google.com has it's own ip address.

A message gets sent to the server to allow us access to the webpage/site of the types url.

## Web

Https is secure and encrypted.

It's sent to a server to allow access such as get, post, etc.

Cookie saved the session once a token is generated after authentication/authorization.

Authentication is who am i and my identity, authorization is what is my role and controls my access level.

## Security

CIA is confidentiality, integrity and availability of data.

Vulnerability is a weak spot in the system while threat is when someone tries to use the available vulnerability for bad actions such as stealing/deleting data.

SQL injection is when a hacker injects a script into the database for malicious purposes through input fields in the webpage.

Least privilege is the basic, bare minimum access level that is given to a user where it protects their data from unauthorized access.


# Scoring

| Area | Score | Notes |
|---|---:|---|
| Python | 2/3 | |
| Linux | 1-2/3 | |
| Networking | 2/3 | |
| Web | 2/3 | |
| Security | 2/3 | |
| Cryptography | 0-1/3 | Not tested |
| Systems / OS | 0-1/3 | Not tested |

**Overall baseline:** 12/21
