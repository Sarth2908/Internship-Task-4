# Internship-Task-4

Commands used for configuration of firewall on linux
    
    sudo ufw enable
    sudo ufw status numbered
    sudo ufw deny 23/tcp
    sudo ufw allow 22/tcp
    sudo ufw delete deny 23/tcp

Summary 

Firewalls monitor and control incoming and outgoing network traffic based on predefined security rules
Each rule evaluates traffic by IP address, port number, and protocol (TCP/UDP).
Inbound rules manage traffic coming into your device, while outbound rules control traffic leaving it.
They act as a barrier between trusted and untrusted networks, preventing unauthorized access while allowing legitimate communications.

