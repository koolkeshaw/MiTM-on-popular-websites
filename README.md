# man-in-the-middle-attack
As a part of checking security of popular websites, I tried implementing a Man-in-the-middle attack on them. 
I found many websites like https://www.amazon.in, https://www.google.com, https://www.linkedln.com, https://www.facebook.com, etc are not using client-side encryption for sensitive data. Hence they are susceptible to man-in-the-middle attack. I was able to fetch credentials. Using SSLSplit, I was able to bypass all the preventive steps present. As I shown in my presentation, victim is able to see Chrome's GREEN-LOCK, even though certificate was invalid. Banking websites like https://discovercard.com is also vulnerable to such attacks. 

Threat-Model:-
I am assuming that attacker can install a certificate in victim's machine. Also, he has control over router via which victim is communicating. These assumptions are satisifed in Internet-cafe.
Victim is using attacker's controlled machine and is talking over attacker's controlled router. 
