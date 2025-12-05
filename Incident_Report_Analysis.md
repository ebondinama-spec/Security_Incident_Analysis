Incident report analysis
Instructions
As you continue through this course, you may use this template to record your findings after completing an activity or to take notes on what you've learned about a specific tool or concept. You can also use this chart as a way to practice applying the NIST framework to different situations you encounter.
Summary
Am a security professional working for a multimedia organization providing various services  to small businesses .We recently encountered a breach in the organization's internal network systems which disrupted the normal business operations for two hours.

 To troubleshoot the incident a TCPDUMP network analyzer tool  reveals  a  Distributed Denial of Service  “DDoS” attack against the organization's network systems. Our further investigation revealed that a malicious actor has exploited a vulnerability in the company's network through an unconfigured firewall by flooding the server with ICMP packets .

The malicious actor takes advantage of communication protocols by sending overwhelming numbers of requests to the network server at the first part of the handshake which  makes the server unable to perform. The disruption in the organization's operations for hours prevented the company from performing tasks that generate revenue  and possibly financial loss .Our security team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services.
Identify
Our security team identified the attack as a Distributed Denial of Service “DDoS”. It’s a network level attack that stimulates a TCP connection between a device and a server .A malicious actor has flooded the network server with ICMP packets .
Protect
To protect the organization's assets from future breach the organization's network systems firewall should be configured correctly and updated regularly by creating a rule to reject all incoming traffic that has the same IP address as the local network. 

An additional layer of defense  should be applied to incrementally harden the network to support the minimum security a firewall provides. A combination of devices and tools such as firewall,IDS/IPS and SIEM tools  would secure and protect the organization's internal network system from future compromise.
Detect
Our security team  monitors and analyzes network traffic and events with devices and tools.
Software applications like 
The Firewall is installed on operating systems and hardware platforms  based on set rules  that block incoming external ICMP packets from non-trusted IP addresses and protect against IP spoofing.

The IDS is an application that monitors and alerts on possible intrusion, this application detects known attacks.

The IPS  is an application that monitors systems for intrusive activity and takes action to stop them; it reports anomalies to security analysts and blocks specific senders. 
These software applications offer a high level of security, the disrupt risky data streams before the reach sensitive parts of the  network

The SIEM tools is an application that analyzes network log data sourced from Firewall ,IDS ,IPS,  it aggregates security event data in one place for security teams to analyze .Network  protocol analyzers like TCPDUMP are used by our security team to detect network traffic patterns and investigate suspicious activity
Respond
For future incidents our security team would monitor network systems with packet sniffers to prevent breach to the organization's internal network systems, compromised internal networks would be blocked  from incoming ICMP packets and restore  all affected operating systems to normal operations.
Recover
To recover from the DDoS attack that breached the organization's internal network services critical network services would be restored after the security team has taken measures to block the affected internal network .




Reflections/Notes:


