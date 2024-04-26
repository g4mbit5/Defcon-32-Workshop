# Defcon-32-Workshop
This workshop starts with some basic malware analysis and reverse engineering on a custom encrypted and obfuscated info stealer malware I made. The malware grabs system/network information and exfils the data over DNS TXT records.   
  
  After finding the right IoCs, I then cover how to build various detections for catching the malware including; how to make a Yara Rule, OSQuery detection and also how to use OSQuery's yara scanning combined with FIM alerting, how to make a custom ClamAV signature, and a snort signature. As well as, how to import the snort signature into pfsense's IDS capability. 
  
  After this, I taught the crowd how to import the various detection logs into elastic stack (ELK).
