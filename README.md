# web-app-pentesting
Web Application Penetration Testing tools and Materials for Ethical Hackers.

Disclaimer: I am not responsible for any damage done using these tool. This tool should only be used for educational purposes and for penetration testing by those who have the knowlege of Rules of Pen-Testing.

### BruteF XSS       
```
 ____             _       _____  __  ______ ____  
| __ ) _ __ _   _| |_ ___|  ___| \ \/ / ___/ ___| 
|  _ \| '__| | | | __/ _ \ |_     \  /\___ \___ \ 
| |_) | |  | |_| | ||  __/  _|    /  \ ___) |__) |
|____/|_|   \__,_|\__\___|_|     /_/\_\____/____/ 
   
```
### Description:
It is a powerful and fast Cross-Site Scripting Brutforcer which is used for bruteforcing parameters. The BruteFXSS injects multiple payloads loaded from a specified wordlist and fires them at the specified parameters and scans if any of the parameter is vulnerable to XSS vulnerability. BruteFXSS is very accurate at doing its task and there is no chance of false positive as the scanning is much powerful. BruteFXSS supports POST and GET requests which makes it compatible with the modern web applications.

### Features:

* XSS Bruteforcing

* XSS Scanning

* Supports GET/POST requests

* Custom wordlist can be included

* User-friendly UI

## Downloading and running BruteF XSS

Enter the following command in the terminal to download it
```
git clone https://github.com/kaiiyer/web-app-pentesting
```
After downloading the program, enter the following command to navigate to the Recon Dog directory and listing the contents
```
cd web-app-pentesting && ls
```
The directory contains `brutefxss.py` which you can run with Python 2 and 3. 
 
Now run the script for your python version with the following command. 
```
python brutefxss.py
```

###Usage(GET Method):

```
COMMAND:  python brutefxss.py
METHOD:   g
URL:      http://www.site.com/?parameter=value
WORDLIST: wordlist.txt
```

###Usage(POST method):

```
COMMAND:   python brutefxss.py
METHOD:    p
URL:       http://www.site.com/file.php
POST DATA: parameter=value&parameter1=value1
WORDLIST:  wordlist.txt
```
### Begin your Bruteforce !!!!!!!
