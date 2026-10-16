# Challenge: Security Detective

## Question 1
Answer: I am logged in as tehreemmubashar36. My home folder is /home/tehreemmubashar36.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu. It runs Ubuntu 26.04.1 LTS.
Commands: hostname, cat /etc/os-release | head -2

## Question 3
Answer: The server has 1.6 GiB of RAM. The root filesystem has 2.3 GiB of free disk space.
Commands: free -h, df -h /

## Question 4
Answer: The users with /bin/bash as their login shell are root and tehreemmubashar36.
Command: grep "/bin/bash" /etc/passwd

## Question 5
Answer: The command returned 246 lines, including the header line. Therefore, there are 245 process entries excluding the header.
Command: ps aux | wc -l

## Question 6
Answer: lab5user was created at 18:03:13 UTC and deleted at 18:12:08 UTC on 16 October 2026.
Command: sudo grep lab5user /var/log/auth.log
