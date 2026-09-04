# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group is a fast growing company that handed off their Identity Lifecycle workflow to a third-party MSP. It worked fine at first. But as they scaled, the cracks showed. There was NO RBAC policy in place. Users were getting access AD-HOC with no consistent process. No audit trail existed to track who had access to what. Furthermore, this created real HIPAA risk since sensitive data wasn't being protected by any enforced access model.


## Solution Overview
* I rebuilt Northstar's Identity infrastructure from scratch in Active Directory. I designed an OU structure by department and built out an RBAC matrix so users ONLY get access based on their role, not manual one-off decisions. All 15 users were provisioned with a consistent naming convention and correctly placed to their department's security group. I also simulated a real-world ticket where a user was provisioned the WRONG level of access, then diagnosed and fixed it just like an actual analyst would.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
