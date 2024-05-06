# Home Networking/Cybersecurity Projects <br>

I will be documenting each item, including how I set it up and configurations shortly.

OPNsense router for the house with multiple APs thorughout the home.  
  -Setup Suricata on the router in IDS mode.  
  -Install ClamAV to check for Malware.  
  -Have all important log information sending to my Wazuh server.<br>
  
Wazuh server ingesting logs from multiple sources including OPNsense and several computers.  
  -Wazuh also sends automated emails to track any alerts over level 10.  
  -In the process of setting it up with TheHive which is a Security Incident Response platform.  <br>

Nessus is also installed to view vulnerabilities  
  -I know Wazuh is also able to look at vulnerabilities but nessus can do it agentless for devices not reporting to Wazuh.  

Aurora Lite - Keeping up on the latest trends I have also been testing out Aurora Lite.  
  -This is an advanced EDR for windows that uses Event Tracing for Windows.  
  -This means it is able to show the exact process and commands as they run
  -This would be very helpful in determining a process tree to find malware.
  
