# Oracle_CPU_API_CVE_to_Excel-Automation
This project enhances vulnerability assessment procedures by automating critical tasks. Utilizing Oracle API requests, the system efficiently retrieves CVE details and essential CVSS key values, organizing them into an excel sheet with clean, structured data. This exported data can then be utilized to automate further processes based on your organization's structure. For instance, it can be employed to cross-reference vulnerable software versions within your organization's systems. Upon detection of a match, automated ticket generation is triggered, directing the issue to the relevant department for immediate patching. By automating this process, the project expedites the mitigation of potential threats, saving valuable time and bolstering our security measures through timely identification and resolution of vulnerabilities.
Oracle CPU API data Link: https://www.oracle.com/security-alerts/#CriticalPatchUpdates

Program execution:
Alienware-15-R3:~/Json_to_excel$ python3 oracle_released_CVE_DB.py

##################################
##  LIST OF O R A C L E CVE DB  ##
##################################


Select a month from jan, apr, jul, oct (case-sensitive): jan
Enter the year (format reference: 20XX): 2024
Data exported to 'Oracle_jan_2024_DB.xlsx' successfully.


Future Scope:
I am currently engaged in a research project aimed at enhancing the autonomy and convenience of the aforementioned system. The goal is to enable users to identify vulnerabilities associated with all software installed across their organization's network without the need for conventional vulnerability scanning tools. Given that such tools rely on CVE data from entities like NIST, there is often a delay in updating their databases, which can impact the accuracy and timeliness of vulnerability assessments. By directly importing data from NIST and comparing it with the current software versions installed in your organization, we aim to expedite the vulnerability assessment process while minimizing network traffic load and reducing the likelihood of false positive detections by SIEM tools.
