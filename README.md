# Penetration-Testing-Toolkit-
A Python-based Penetration Testing Toolkit containing multiple modules, including a port scanner, directory brute-forcer, and subdomain scanner. The toolkit is modular, menu-driven, and demonstrates basic ethical hacking techniques with clear output

COMPANY: CODTECH IT SOLUTIONS
NAME: KAUSHAL M LEMBHE
INTERN ID: CTIS1154
DOMAIN: CYBER SECURITY AND ETHICAL HACKING
DURATION: 4 WEEKS
MENTOR: NEELA SANTOSH

Description of the Task:
This project is a Python-based Penetration Testing Toolkit designed to demonstrate multiple ethical hacking techniques using a modular structure. The toolkit contains three fully working modules: a Port Scanner, a Directory Brute-Forcer, and a Subdomain Scanner. The program runs through a menu-driven interface where the user selects a module, enters a target, and receives real-time output.

1. Port Scanner Module

The Port Scanner checks a target system for open ports using Python’s socket library.
In the execution, the target used was scanme.nmap.org, which is an official safe scanning host.

Output Observed:
[+] Scanning Target: scanme.nmap.org
[+] Scanning Ports...

PORT 22 : OPEN
PORT 80 : OPEN
This confirms the scanner successfully connected to open ports and displayed the results.

2. Directory Brute-Forcer Module

This module sends HTTP requests to common directory paths on a website using the requests library.
The target used in testing was https://httpbin.org
, a legal public testing website.

Output Observed:
[+] Running Directory Bruteforce on https://httpbin.org


This shows the brute-forcer successfully attempted directory enumeration.

3. Subdomain Scanner Module

The Subdomain Scanner checks for active subdomains by trying common subdomain prefixes and verifying their responses.

The domain tested was google.com.

Output Observed:
[ACTIVE] http://www.google.com
[ACTIVE] http://mail.google.com
[ACTIVE] http://api.google.com


These results confirm that the tool successfully detected operational subdomains.

4. Menu-Driven Modular Toolkit

After each scan, the toolkit returns to the main menu:

1. Port Scanner
2. Directory Brute-Forcer
3. Subdomain Scanner
4. Exit


This proves that the toolkit is modular, interactive, and easy to use.



FINAL SUMMARY

The project successfully demonstrates a complete Penetration Testing Toolkit with multiple modules, clear outputs, and practical functionality. All modules executed correctly, showing open ports, directory responses, and active subdomains. This fulfills the requirement of building a Python-based modular toolkit with proper documentation and working results.


Output:
<img width="908" height="791" alt="Image" src="https://github.com/user-attachments/assets/2db6383e-5264-49ad-a7a4-91d89c6d82bc" />
