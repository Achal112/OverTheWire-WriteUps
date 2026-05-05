# Bandit Level 0

## Level Goal
The goal of this level is to log into the game using SSH.

- **Host:** `bandit.labs.overthewire.org`
- **Port:** `2220`
- **Username:** `bandit0`
- **Password:** `bandit0`

---

## Concepts Learned
- What SSH is
- Remote server login
- Using terminal commands
- Connecting to a server using a custom port

---

## Command Used

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

---

## Step-by-Step Solution

### Step 1: Open Terminal
I opened my Linux terminal (or command prompt with SSH support).

---

### Step 2: Connect Using SSH
I used the following command:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

### Command Breakdown

| Part | Meaning |
|---|---|
| `ssh` | Secure Shell command used for remote login |
| `bandit0` | Username |
| `@` | Connects user to host |
| `bandit.labs.overthewire.org` | Remote server address |
| `-p 2220` | Specifies custom SSH port |

---

### Step 3: Enter Password
When prompted, I entered the password:

```text
bandit0
```
---

![task](<img width="982" height="753" alt="image" src="https://github.com/user-attachments/assets/112a837d-7777-4e33-890e-fef6f52f1abf" />)

---

> **Note:** While typing the password, nothing appears on the screen. This is normal behavior in Linux terminals for security purposes.

---

### Step 4: Successful Login
After entering the password correctly, I successfully logged into the Bandit server.

Example prompt:

```bash
bandit0@bandit:~$
```

This indicates that the SSH connection was successful.

---

## Key Takeaways
- Learned how to connect to a remote server using SSH
- Understood the use of custom SSH ports
- Practiced basic terminal usage
- Gained familiarity with remote Linux environments

---

## Skills Practiced
- SSH
- Linux Terminal
- Remote Access
- Command Line Basics
- Cybersecurity Fundamentals

---

## Helpful Resources
- [OverTheWire Official Website](https://overthewire.org/wargames/)
- [SSH Wikipedia Guide](https://en.wikipedia.org/wiki/Secure_Shell)
- [How to Use SSH with Custom Port](https://itsfoss.com/change-ssh-port/)
