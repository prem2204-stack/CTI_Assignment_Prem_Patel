# CTI_Assignment_Prem_Patel
 **Task 3 Extract Diamond Model Elements**
 **1. Adversary:**
    Attacker traced to Hebei, China (nickname 'Covert Grove'), using a US-based VPS and 
    Long-running espionage campaign targeting intellectual property is used in the report.
 **2. Infrastructure:**
    U.S based VPS was used to host attacker operation, and various CC domain and IP address
    (eg from report:173.252.205.36, 173.252.205.37, antivirus-groups.com,domain.rm6.org etc)
** 3. Capability:**
    Poison Ivy or Backdoor.Odivy malware for remote access
    Password-hash dumping & credential theft
    Malicious self-extracting 7zip attachments
 **4. Victim:**
    29 chemical companies targeted, 19 defense-sector organizations
    Earlier waves: NGOs & motor industry, Victims in 20 countries (e.g., US, UK, Bangladesh)
    The purpose may to steal intellectual property, formulas, and manufacturing data

    
**Task 5 Threats Actor Profile summary**
The Nitro Attacks campaign was directed by threat actors traced to chinese national nickname 'Covert Grove', who used a US-based virtual private server for command and control activities.
The campaign primarily trageted organizations in the chemical and advanced materials industries, aiming to steal valuable intellectual property.
The attackers depolyed tailored spear-phishing emails sometimes broadly distributed, even sometimes higly trageted to deliver or spread the Poison IVy remote  acess Trojan.
Once inside, they moved laterally to  escalate privileges, harvested credentials, and exflitrated proprietary documents. While the infrastructure and malware used were not
advanced by modren standards, the attackers demonstrated presistance and organizational awareness. The wide, multinational spread of victims underscores the risks facing compaines
with valuable research and designs.
**Mitigation strategies** should include robust email filtering, user awareness campaigns, multi-factor authentication
and regular security aduits to detect lateral movements and unusual data exfilteration


**Task 6: Reflection Questions (10 points) Answer the following:**
1.How does the Diamond Model help in understanding threat actors?
Ans: The Diamond Model calrifies the relationships and dependencies among Advesary, Victim, Infrastructure and Capability, which make it cleary understandable 
and easy to visualize the attack and inform priotization for defence stratigies. Mapping the Nitro Attacks enchanced understanding of how an external adversary
leveraged specific tools and infrastructure to achieve their goals.
2.What challenges did you face in identifying each vertex? 
Ans: Identifying realiable evidence for each model vertex required parsing technical and narrative sections of the report. Attribution was particularly complex 
becuase there were multiple actors and overlapping infrastrucuture mentioned in report.
3.How could this model support proactive defense strategies? 
Ans:Recognizing attacks vectors like trageted phishing and commodity malware enables defenders to harden controls at entry points, foster employee  vigilance , 
and  monitor for threat infrastructure, such as suspicious domain and IP address. 
