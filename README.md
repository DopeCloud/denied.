# Denied.

Networks who aren't allowed to reach dopehosting.net. Not all parts of it.

When we get a network attack or something else if we see that ip is from a hosting provider we just ban the whole subnet and all ips which are in the same org of attacker ip. But reason of banning all the subnet and other ips from the same org is that they're from a hosting/vps/dedicated/vpn/proxy provider and they don't have why to reach our network if they leave their customers to abuse with their service means that's not a good provider so we ban them all. **And those bans are permanent.**


About ADSL IPs. 

1. Dynamic ips are banned for month, week or day or hours based on kind of attack.

2. Static ADSL ips are banned permanently.


--------------------

To request a unban you can send a request to : `raw@dopehosting.net` ex

[TITLE] - `UNBAN REQUEST.`

[MESSAGE] *For single ip you can just tell us a simple reason.* ***For subnet/org You should provide the improvement of your service (network care)!***


# Installation

1. **`cd /bin/; wget https://raw.githubusercontent.com/DopeCloud/denied./master/bin/ban; chmod +x /bin/ban; cd ~/`**

2. **`ban fresh`** *(Update and get ip list)*

# Update

1. **`ban fresh`** *(Update and get latest ip list)*

# Usage

1. **`ban em`** *(Ban iplists)*
