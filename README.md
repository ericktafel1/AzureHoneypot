Using an Azure Subscription, I created a Virtual Machine environment on the cloud to act as a Honeypot in the hopes of attracting global attackers. With the log data, I  then used Log Analytics Workspace to ingest the logs and Sentinel SIEM to create a map to track attacker data, also utilizing a PowerShell script, I extracted the IP addresses from the Windows log, and sent them to 3rd party API to create geographic data.

[See Honeypot.md](https://github.com/ericktafel1/AzureHoneypot/blob/main/Honeypot.md)
