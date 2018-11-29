# VPC Sharing
Using AWS Resource manager you can link VPCs without peering.  Creating cross-account VPC.
PROS:
- Reduce CIDR
- No Peering Required
- Separation of duties
- Billing & Security
- Same AZ cost for data transfer is nil.

(Link to Documentation) [https://amzn.to/2Aovw2Z]

# AWS Global Accelerator
Allow Cross region community using AWS backbone instead of Internet.
Create "AnyCast" IP that is cross region == EIP that is Global
(Link to Documentation) [https://amzn.to/2FI3y89]

# Route 53 Hybrid Cloud

# AWS Client VPN
Traditionally VPN to VGW has been Site-to-Site (Cisco ASA).  Now you can use openVPN to connect directly to VGW

# BYOIP
PROS:
- IP Reputation
- Whitelisting
- Migration
- Redundancy

# Transit Gateway
In order to have a full mesh (all VPC connect) = (n(n-1))/2 Peering connection
Attachment = Connection from VPC or On Prem VPN to TGW
Association = Route table used to route packets from an attachment
Propagation = Route table where the attachment's route s are installed.

(Link to Documentation)[https://amzn.to/2Skl4zV]

# Network Performance for EC2
[https://amzn.to/2DL0qG6]

# Flow logs can now be delivered to Amazon S3