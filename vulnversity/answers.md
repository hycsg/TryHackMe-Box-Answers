# Answers for vulnversity

## Task 1

1. **Deploy the machine**: No Answer Needed

## Task 2 (Reconnaissance)

1. **Scan this box**: `No Answer Needed`
2. **Scan the box, how many ports are open?**: `6`
3. **What version of the squid proxy is running on the machine?**: `3.5.12`
4. **How many ports will nmap scan if the flag -p-400 was used?**: `400`
5. **Using the nmap flag -n what will it not resolve?**: `DNS`
6. **What is the most likely operating system this machine is running?**: `Ubuntu`
7. **What port is the web server running on?**: `3333`
8. **Its important to ensure you are always doing your reconnaissance thoroughly before progressing. Knowing all open services (which can all be points of exploitation) is very important, don't forget that ports on a higher range might be open so always scan ports after 1000 (even if you leave scanning in the background)**: `No Answer Needed`

## Task 3 (Locating Directories Using GoBuster)

1. **run GoBuster with a wordlist: gobuster dir -u http://<ip>:3333 -w <word list location>**: `No Answer Needed`
2. **What is the directory that has an upload form page?**: `/internal/`
  
## Task 4 (Compromise the webserver)

1. **Try upload a few file types to the server, what common extension seems to be blocked?**: `.php`
2. **To identify which extensions are not blocked, we're going to fuzz the upload form. To do this, we're doing to use BurpSuite. If you are unsure to what BurpSuite is, or how to set it up please complete our BurpSuite room first.**: `No Answer Needed`
3. **what extension is allowed?**: `.phtml`
4. `No Answer needed`
5. **What user was running the web serer?**: `bill`
6. **What is the user flag?**: `8bd7992fbe8a6ad22a63361004cfcedb`

## Task 5 (Privilege Escalation)

1. **On the system, search for all SUID files. What file stands out?**: `/bin/systemctl`
2. **Become root and get the last flag (/rooot/root.txt)**: `a58ff8579f0a9270368d33a9966c7fd5`



