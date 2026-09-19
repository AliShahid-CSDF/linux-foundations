# Linux Foundations

A beginner-to-confident Linux path, built hands-on on Kali Linux (XFCE). This is step one of my roadmap toward a cybersecurity career: **Linux → Networking → Python/Bash/Rust → Ethical Bug Bounty → Penetration Testing.**

Every topic is learned one concept at a time, practiced in my own lab, and documented here.

## Why Linux First

Most servers, cloud systems, containers, and security tools run on Linux. Every later step in my roadmap (networking, scripting, bug bounty, pentesting) assumes I can move around a Linux system comfortably, read its logs, and understand its permissions. This repo builds that base.

## What I Will Learn

| # | Module | Key topics | Status |
|---|--------|-----------|--------|
| 1 | Filesystem & Navigation | Filesystem tree, absolute vs relative paths, `pwd`, `ls`, `cd`, `mkdir`, `touch`, `cat` | Done |
| 2 | Users, Groups & Permissions | Users and root, `whoami`, `id`, `sudo`, `chmod`, `chown`, read/write/execute, SUID basics | Planned |
| 3 | Working with Files & Text | `cp`, `mv`, `rm`, `less`, `head`, `tail`, `grep`, `find`, pipes, redirection | Planned |
| 4 | Processes & Services | `ps`, `top`, `kill`, background jobs, `systemctl` | Planned |
| 5 | Package Management | `apt`, updating the system, installing and removing tools | Planned |
| 6 | Logs & System Inspection | `/var/log`, `journalctl`, `dmesg`, reading auth logs | Planned |
| 7 | Networking from the Terminal | `ip`, `ss`, `ping`, `curl`, `ssh` (a bridge into the Networking phase) | Planned |
| 8 | Intro to Bash Scripting | Variables, conditions, loops, small automation scripts (a bridge into scripting) | Planned |
| 9 | Capstone Mini-Project | A small script or lab write-up that combines the modules above | Planned |

The order may change as I learn. Status is updated after each module.

## How Each Module Is Structured

1. **Theory** in plain language
2. **Practical exercise** done on my own lab machine
3. **Daily-life analogy** to make it stick
4. **Real cyber-news tie-in** linked to a real source
5. **Check-understanding question** before moving on
6. **Portfolio output**: notes, commands, and a short write-up

## Lab Environment

- **OS:** Kali Linux (XFCE)
- **Shell:** zsh / bash
- All practice is done only in my own lab environment.

## Repository Structure

```
linux-foundations/
├── README.md
├── 01-filesystem-navigation/
├── 02-users-permissions/
├── 03-files-and-text/
├── 04-processes-services/
├── 05-package-management/
├── 06-logs-inspection/
├── 07-networking-cli/
├── 08-bash-intro/
└── 09-capstone/
```

Each folder holds that module's notes, command cheat sheet, and exercise write-up.

## Progress

- [x] Module 1: Filesystem & Navigation
- [ ] Module 2: Users, Groups & Permissions
- [ ] Module 3: Working with Files & Text
- [ ] Module 4: Processes & Services
- [ ] Module 5: Package Management
- [ ] Module 6: Logs & System Inspection
- [ ] Module 7: Networking from the Terminal
- [ ] Module 8: Intro to Bash Scripting
- [ ] Module 9: Capstone Mini-Project

## About

I'm Ali Shahid, a BS Cyber Security & Digital Forensics student and published researcher, building hands-on skills with the goal of working in cybersecurity in Switzerland.

- LinkedIn: `www.linkedin.com/in/alishahid-cyberx`
- Email: `alishahid.cyberx@gmail.com`
