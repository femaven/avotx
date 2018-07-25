This connects to AlienVault and accesses the Open Threat eXchange for import into splunk

it reconnects every two minutes, and pulls in the data

sourcetype="avotx.log" "avotx_poller_rev=1.1”

you can rewind its input by setting the avotx_poller.cfg:revision = 0


enjoy!

Femaven's ideas:
DNS 
  update poller to pull in suspicious DNS records from OTX
  Pull in DNS queries for correlation
Dashboards for both IP and DNS
Incorporating CIM
