# Tales from the Decrypt Keeper

Antigen Security. Steven Legg. 

Expense of the perverse incentives that create these circumstances in the first place. Basically there are too many incentives and reasons to do the crime that outweigh our ability to defend.

- See the Cyber Social Contract. 

- SMB Client 1
	- Access via exchange proxylogon. Down for a week. 
	- Manufacturing.
	- No trusted backups.
	- MSP stuggled with simple EDR deployment. 
	- MSP did not patch Exchange. 
	- 68% of environment unpatched. 
- SMB Client 2
	- Down for five days. 
	- Limited backups.
	- No command of SIEM.
	- Incomplete MFA deployment. 
	- Attributed to Deep Blue Magic. 
	- Lack of network segmentation.
	- No backup strategy.
	- No cyber insurance.
	- Admin password cracked at Firewall. Pivot from the firewall. 
	- Crypto 85% of environment. 
- Midsize Client 1
	- ProxyLogon via Conti. 
	- Poor patching process.
	- Poor network logging. 
	- Fixated on the root cause to the detriment of the case/recovery.
	- Cost them $10,000 an hour to keep a forge running while they were down.
- Midsize Client 2
	- Hit by Lockbit v2
	- Under-configured SIEM
	- Zero trusted backups
	- No least privilege config. All domain users were Domain Admin.
	- No standard endpoint security.
	- No log aggregation.
	- Took 8 days for an actual administrator to get onsite. 
	- MSP was not managing that site.
	- Exposed via RDP as well.
- Midsize Client 3
	- Antagonism severely slowed the investigation.
	- IT Admin click a malicious link.
	- Squirrel Waffle Malware
		- https://news.sophos.com/en-us/2022/02/15/rapid-response-the-squirrelwaffle-incident-guide/
	- XDR solution allowed them to find the issue.
- Ease of opportunity, not data assets, determined target status. Meaning that the threat actors are looking for easy to exploit and if they happen onto good data then all the better. 
- Many attack vectors were preventable: misconfigurations and unpatched vulnerabilities. 
- Antivirus is ineffective on its own. Need to have an EDR/XDR process.
- Invest today or pay tomorrow. 
- Email security-as-a-solution is now critical.
	- Link verification
	- Attachment scanning
	- Sandboxing
- Technology installed without understanding is a sunk cost. 
- Resiliency is KEY: 
	- host/network visibility
	- remote endpoint access
	- asset knowledge
	- responsive containment practices
	- incident response familiarity amongst team
	- resourceful partners
- Smart people don't learn from their mistakes - they learn from the mistakes others make. 
