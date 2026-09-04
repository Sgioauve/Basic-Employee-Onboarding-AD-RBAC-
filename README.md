# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
* Northstar Medical Group's IT environment was previously managed by an outside MSP with no consistent structure or documentation. User accounts were created ad-hoc with no standardized naming convention, no organizational unit structure, and no role-based access controls in place. Permissions were assigned manually and inconsistently, making it difficult to track who had access to what. This lack of structure created real HIPAA compliance risk, since sensitive employee and patient-adjacent data could be accessed without a clear audit trail or enforced least-privilege model.


## Solution Overview
* I rebuilt Northstar's identity infrastructure from the ground up, starting with a new Active Directory domain (NMG.com) and a promoted domain controller. I designed a department-based OU structure (Finance, HR, IT, Operations) to logically separate accounts and enable scoped administration. Each department was paired with a dedicated security group, creating a flat RBAC model where access is granted by group membership rather than individual user permissions. All 15 user accounts were provisioned using a consistent naming convention (first initial + last name) and correctly placed into their department's OU and security group. This structure makes access reviews, onboarding, and offboarding faster and far less error-prone than the previous ad-hoc setup.

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
