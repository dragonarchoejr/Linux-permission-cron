# Linux-permission-cron
my bandit OverTheWire journey



# Linux File Permissions and Cron Jobs

## Introduction

This project documents my learning journey into Linux fundamentals and cybersecurity. I explored file permissions, executable scripts, and cron jobs while practising Linux commands and the OverTheWire Bandit wargame.

## Objectives

- Understand Linux file permissions.
- Learn the difference between read, write, and execute permissions.
- Understand how cron jobs automate tasks.
- Practise basic Linux commands in a safe environment.

## 1. Linux File Permissions

Linux permissions control who can read, modify, or execute a file.

The three basic permission types are:

- `r` — Read
- `w` — Write
- `x` — Execute

To inspect permissions:

```bash
ls -l
```

To make a script executable:

```bash
chmod +x script.sh
```

## 2. Cron Jobs

Cron is a Linux utility that runs commands automatically at scheduled times.

To inspect scheduled system tasks, where access is permitted:

```bash
ls -l /etc/cron.d/
```

Cron jobs are useful for automated backups, maintenance, and monitoring.

## 3. Practical Learning

While working through OverTheWire Bandit, I learned that understanding file ownership, permissions, and the user running a process is essential when troubleshooting access errors.

## 4. AI Assistance

I used ChatGPT to help explain Linux concepts, suggest commands, and organise this write-up. I reviewed the explanations and practised the commands myself.

## Conclusion

This project strengthened my understanding of Linux permissions, shell commands, and scheduled tasks. These fundamentals are important for further study in cybersecurity and system administration.

## References

- OverTheWire Bandit: https://overthewire.org/wargames/bandit/
- GNU Coreutils documentation: https://www.gnu.org/software/coreutils/manual/
- Cron documentation: https://man7.org/linux/man-pages/man8/cron.8.html
