# zero_to_hero

## From Zero to Hero - Leverage Sysmon and Auditd for Zero Trust Monitoring of All Your hosts


In a zero trust environment, host based security monitoring becomes even more important than past days of the old moat and castle methodology of infosec where we were most concerned about the perimeter of the network and allowed resources within to operate and communicate with each other freely as trusted parties.



This project also includes a Splunk App That uses auditd data on linux hosts and sysmon data on windows hosts and maps the detections to the Mitre Att&ck Framework to monitor hosts in a zero trust environment






Credits:

This work is based on the hard work of others who have already forged a path in this area of knowledge:

Sysmon Policy Framework and Related Topics <br />
########################################### <br />

https://github.com/SwiftOnSecurity/sysmon-config
https://github.com/olafhartong/sysmon-modular
https://www.syspanda.com/index.php/2017/02/28/deploying-sysmon-through-gpo/
https://www.varonis.com/blog/sysmon-threat-detection-guide/
https://static1.squarespace.com/static/552092d5e4b0661088167e5c/t/5d5588b51fd81f0001471db4/1565886646582/Windows+Sysmon+Logging+Cheat+Sheet_Aug_2019.pdf

Auditd Policy Framework <br />
####################### <br />

https://github.com/bfuzzy/auditd-attack/blob/master/auditd-attack.rules
https://github.com/doksu/splunk_auditd/wiki/About-Auditd
https://splunkbase.splunk.com/app/4232/#/details
https://splunkbase.splunk.com/app/2642/#/details
https://superuser.com/questions/222912/how-can-i-log-all-process-launches-in-linux
https://izyknows.medium.com/linux-auditd-for-threat-detection-d06c8b941505
https://github.com/Neo23x0/auditd/blob/master/audit.rules
https://github.com/bfuzzy1/auditd-attack/blob/master/auditd-attack/auditd-attack.rules
https://github.com/izysec/linux-audit/blob/main/DS-to-audit.MD
https://capsule8.com/blog/auditd-what-is-the-linux-auditing-system/
https://linux.die.net/man/7/audit.rules



Mitre Att&ck Mapping <br />
###################### <br />

https://github.com/olafhartong/ThreatHunting/
https://medium.com/@olafhartong/endpoint-detection-superpowers-on-the-cheap-threat-hunting-app-a92213f5e4b8

APT and Lateral Movement <br />
######################### <br />

https://www.first.org/resources/papers/conf2017/APT-Log-Analysis-Tracking-Attack-Tools-by-Audit-Policy-and-Sysmon.pdf

Comparing Methods <br />
################## <br />

https://pberba.github.io/security/2021/11/22/linux-threat-hunting-for-persistence-sysmon-auditd-webshell/
