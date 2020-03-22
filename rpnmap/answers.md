# Answers for rpnmap

## Task 1 [Deploy!]

1. **Deploy the machine!**: `No answer needed`

## Task 2 [Nmap Quiz]

1. **First, how do you access the help menu?**: `-h`
2. **Often referred to as a stealth scan, what is the first switch listed for a 'Syn Scan'?**: `-sS`
3. **Not quite as useful but how about a 'UDP Scan'?**: `-sU`
4. **What about operating system detection?**: `-O`
5. **How about service version detection?**: `-sV`
6. **Most people like to see some output to know that their scan is actually doing things, what is the verbosity flag?**: `-v`
7. **What about 'very verbose'? (A personal favorite)**: `-vv`
8. **Sometimes saving output in a common document format can be really handy for reporting, how do we save output in xml format?**: `-oX`
9. **Aggressive scans can be nice when other scans just aren't getting the output that you want and you really don't care how 'loud' you are, what is the switch for enabling this?**: `-A`
10. **How do I set the timing to the max level, sometimes called 'Insane'?**: `-T5`
11. **What about if I want to scan a specific port?**: `-p`
12. **How about if I want to scan every port?**: `-p-`
13. **What if I want to enable using a script from the nmap scripting engine? For this, just include the first part of the switch without the specification of what script to run.**: `--script`
14. **What if I want to run all scripts out of the vulnerability category?**: `--script vuln`
15. **What switch should I include if I don't want to ping the host?**: `-Pn`

## Task 3 [Nmap Scanning]

1. **Let's go ahead and start with the basics and perform a syn scan on the box provided. What will this command be without the host IP address?**: `nmap -sS`
2. **After scanning this, how many ports do we find open under 1000?**: `2`
3. **What communication protocol is given for these ports following the port number?**: `tcp`
4. **Perform a service version detection scan, what is the version of the software running on port 22?**: `6.6.1p1`
5. **Perform an aggressive scan, what flag isn't set under the results for port 80?**: `httponly`
6. **Perform a script scan of vulnerabilities associated with this box, what denial of service (DOS) attack is this box susceptible to? Answer with the name for the vulnerability that is given as the section title in the scan output. A vuln scan can take a while to complete. In case you get stuck, the answer for this question has been provided in the hint, however, it's good to still run this scan and get used to using it as it can be invaluable.**: `http-slowloris-check`




