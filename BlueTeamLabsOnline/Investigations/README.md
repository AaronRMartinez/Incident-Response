Completed **Blue Team Labs Online** investigations pertaining to incident response.

## PRETIUM

### Scenario

The Security Operations Center at Defense Superior are monitoring a customer’s email gateway and network traffic (Crimeson LLC). One of the SOC team identified some anomalous traffic from Josh Morrison’s workstation, who works as a Junior Financial Controller. When contacted Josh mentioned he received an email from an internal colleague asking him to download an invoice via a hyperlink and review it. The email read:

*There was a rate adjustment for one or more invoices you previously sent to one of our customers. The adjusted invoices can be downloaded via this [link] for your review and payment processing. If you have any questions about the adjustments, please contact me.*

*Thank you.*

*Jacob Tomlinson, Senior Financial Controller, Crimeson LLC.*

The SOC team immediately pulled the email and confirmed it included a link to a malicious executable file. The Security Incident Response Team (SIRT) was activated and you have been assigned to lead the way and help the SOC uncover what happened.

You have NetWitness and Wireshark in your toolkit to help find out what happened during this incident. 

### Tools

- Wireshark
- TShark
- NetWitness
- CyberChef

<a href="https://blueteamlabs.online/achievement/share/76960/6">View Achievement</a>

## PRETIUM

### Scenario

Like every other day, Terry logged in and began working on his corporate laptop, but after a while he noticed several command prompts open and close without him doing anything. He suspects that his laptop has been infected with malware. He reports to the IT team to understand what's happening.

We have collected Sysmon event logs (both in .json and .csv) from Terry's laptop and network traffic in the form of a packet capture file to support the investigation. Use ELK or Linux CLI to analyze the retrieved Sysmon logs and use wireshark-gtk for analyzing the PCAP. 

### Tools

- ELK
- wireshark-gtk
- Linux CLI

<a href="https://blueteamlabs.online/achievement/share/76960/10">View Achievement</a>
