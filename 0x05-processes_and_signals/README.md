# 0x05. Processes and signals

## Requirements

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.7.0 via apt-get) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Tasks

### 0. What is my PID

Bash script that displays its own PID.

### 1. List your processes

Bash script that displays a list of currently running processes.

### 2. Show your Bash PID

Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.

### 3. Show your Bash PID made easy

Bash script that displays the PID, along with the process name, of processes whose name contain the word bash

### To infinity and beyond

Bash script that displays To infinity and beyond indefinitely

### 5. Don't stop me now!

Bash script that stops 4-to_infinity_and_beyond process

### 6. Stop me if you can

Bash script that stops 4-to_infinity_and_beyond process.

### 7. Highlander

Bash script that displays:

- To infinity and beyond indefinitely
- With a sleep 2 in between each iteration
- I am invincible!!! when receiving a SIGTERM signal

### 8. Beheaded process

Bash script that kills the process 7-highlander
