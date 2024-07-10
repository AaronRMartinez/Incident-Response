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

## MINER

### Scenario

Our detection team reported that they receive an IDS alert related to reconnaissance but they were unable to read the traffic as it was encrypted. Pcap files and analysis tools are available on the Desktop. 

### Tools

- Network Miner
- Wireshark

<a href="https://blueteamlabs.online/achievement/share/76960/16">View Achievement</a>

## GHOSTED

### Scenario

WeLoveDogz LLC does not have enough funds for a testing environment and their one-man IT department, John, set up a new server straight into production while still being configured. Unfortunately the server got compromised and John does not have clue how this happened. Luckily, he was able to obtain a packet capture, a log from Suricata IDS/IPS and a TTY report from auditd running on the system. Help John understand how his system got compromised! 

### Tools

- Wireshark
- OSINT
- Linux CLI

<a href="https://blueteamlabs.online/achievement/share/76960/51">View Achievement</a>

## DRILLDOWN

### Scenario

Your organization doesn't use Amazon Web Services, so when a Threat Hunter starts seeing connections to multiple EC2 instances, it's time to start hunting to understand what happened, so the information can be passed to the incident response team, and indicators can be gather for intelligence sharing.

### Tools

- Splunk
- VirusTotal

<a href="https://blueteamlabs.online/achievement/share/76960/108">View Achievement</a>

## SUKANA

### Scenario

Desi Sukana is an aspiring DFIR Analyst. These are professionals who gather and investigate vast amounts of data to fill in gaps in information about cyber attacks. He garnered this interest after witnessing his father pass in a tragic accident. His father, Drake Sukana, fell victim to a data breach that compromised his personal information including salary, location, marital status, etc. The attacker used that information to send robbers to his domicile in the United States. He faithfully defended his household but could not survive the injuries. After the funeral, Mrs. Sukana (Desi’s mom) took him and moved to Sydney, Australia — her home country. Fueled by the passing of his father and strange environment, Desi rigorously pushed through his college classes and independent studies to not only gain the skills needed to solve his father's murder but also to find gainful employment.

Mr. Sukana was the breadwinner in the family while Ms. Sukana was the housewife. The life insurance payout from his death provided Desi and his mother to live 4 years without having a job — that same payout ends in two months. Mrs. Sukana has no employable skills in the market to afford the high rent in Bellevue Hill. She is placing her bets on Desi to land a job within the cybersecurity field - specifically DFIR.

Desi currently holds a Bachelor of Science in Computer Forensics, GHFI, and GCFA. He runs a DFIR Discord, Podcast, and hosts CTFs. Despite this killer portfolio, he is struggling to break into the field of cybersecurity as a recent grad. He still deals with depression from his father’s passing 4 years ago. He has two service dogs called Moxie (a human lover) and Waffle (a wild barker) for support. On his recent dog walk, he met the opportunity of a lifetime.

He met Kurt Hansen in a local dog park. Kurt is the CEO of Tesserent, Australia’s largest listed cybersecurity company. Moxie and Waffle were doing a canine freestyle that gathered a public crowd — especially Kurt. Desi, knowing his status within the country, used the opportunity to sell himself and explain his interest in DFIR. Kurt was impressed with his background and passed his information along to his cybersecurity department.

A week later, Desi had an interview with the DFIR team at Tesserent. It went extremely well. He made it to the final stages after some behavior assessments and an introduction call with the team. His final round consisted of an Online Assessment (OA). He has been provided with the KAPE output and a memory dump of an infected Windows machine. Some extra context was provided in the OA like the email conversation with the victim and a malware report. If Desi passes this OA, he will be presented with a DFIR Analyst Role with a starting salary of $120,000. This will allow him to afford rent in Bellevue Hill, get more treatment for his depression, and take care of his mother. Will he pass the 19-question OA is it up to you? You have 24 hours, Desi. Good luck! 

### Tools

- Thunderbird
- VirusTotal
- Cisco Talos
- Certutil
- Volatility3
- Volatility Workbench
- Autopsy
- Wireshark
- Timeline Explorer
- CyberChef
- MFTECmd

<a href="https://blueteamlabs.online/achievement/share/76960/163">View Achievement</a>

## NIMBUS

### Scenario

My name is Jet Cloud! Some people call me ‘JC’ for short. I have been in cybersecurity for the past 3 years as a SOC Analyst. The money is great but there is an issue. To be frank, the work is really boring… I sit at a desk, look at a dashboard, and click. I am not sure if it was worth 4 years of my life to major in mundane tasks but I can’t get those years back. I have been contemplating a career change—something in the cloud potentially.

Two of my best friends, Samir and Otuonye, suggested that I should bring my security background to the cloud. They mentioned that the role of Cloud Security Analyst would fit me well. They referred me to their current employer Cloud Trail Technologies (CTT). If it helps, the company is big in the industry according to my brief research. While I waited for the status of my application, they advised that I should study for my AWS certifications to get familiar with the cloud stack they use.

Three weeks have passed since that day. I passed my AWS Certified Cloud Practitioner exam—it was fairly easy, to be honest, more of a vocabulary test. Most importantly, CTT reached out and I passed the behavior interview with flying colors. I have been placed in the final stage. The hiring manager Mr. Adams commended me for reaching this stage in a relatively short time. I told him that have my AWS CCP and I am currently studying for my AWS Solution Architect. Mr. Adams' facial expression seemed pleased.

The call ended on a high note and he said to keep an eye on my email. I immediately called Samir and Otuonye to share the news. They exhorted me further saying, “You got this in the bad JC!” Another boost was this statement, “Hey JC! Mr. Adams and the company are flying all the ‘Cloud Employees’ to Las Vegas for AWS re:Invent 2023 next month. Bro, if you can pass the final assessment, we turn Vegas upside down with a huge celebration party!” I am not going to lie, when I heard that, I almost teared up. Not only will I be able to leave my boring SOC job—I will be in a better position with my best friends. I am going to pass this final interview!

A few days later, Mr. Adams sent me an email. He further explained the final assessment in detail with the following scenario: “As a Cloud Security Analyst, you have been assigned to investigate the activities performed on an S3 bucket in your AWS account. Your goal is to gather information about the bucket's name, object-level operations, and access requests made to the bucket. You will perform your analysis using CloudTrail Management Events, CloudTrail Data Events, and S3 Access Logs.”

It looks like I have been given access to start this investigation on a platform called BTLO. I personally never heard of it but that won’t stop me. I had made it this far, the end is within my grasp. It looks like I have 10 hours of lab time to answer all the questions below. Let’s get started! My last name isn’t Cloud for nothing! 

### Tools

- CyberChef
- Notepad++
- JSON Viewer
- Sublime Text
- ChatGPT

<a href="https://blueteamlabs.online/achievement/share/76960/170">View Achievement</a>

## WINTER STEW

### Scenario

Festiva has many ideas for Winter Wonderland one of which includes mass manufacturing of stew to make sure everyone is fed over this sometimes harsh period of the year.

With all the recent issues with Glacier happening she wants to make sure that her Chemical Plant where the stew is getting made is okay. Can you help threat hunt and see if everything is okay?

### Tools

- Wireshark

<a href="https://blueteamlabs.online/achievement/share/76960/181">View Achievement</a>

## DEEP BLUE

### Scenario

A Windows workstation was recently compromised, and evidence suggests it was an attack against internet-facing RDP, then Meterpreter was deployed to conduct 'Actions on Objectives'. Can you verify these findings?

You have been provided with the Security.evtx and System.evtx log exports from the compromised system - you should analyze these, NOT the Windows logs generated by the lab machine (when using DeepBlueCLI ensure you're providing the path to these files, stored inside \Desktop\Investigation\.

### Tools

- DeepBlueCLI
- PowerShell
- Event Viewer

<a href="https://blueteamlabs.online/achievement/share/76960/32">View Achievement</a>
