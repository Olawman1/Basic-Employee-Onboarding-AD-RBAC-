# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem in this project was related to a fictional healthcare organization called Northstar Medical Group. They are a rapidly growing company that had outsourced its identity lifecycle management processes to a third-party managed service provider (MSP). While this approach initially supported the organization's needs, significant identity and access management challenges emerged as the company expanded. Northstar lacked a formal role-based access control (RBAC) model, resulting in users receiving access on an ad hoc basis. The organization also lacked sufficient audit trails to track access which increased the exposure to HIPAA compliance and security issues. 

## Solution Overview
The solution was to build out a basic employee onboarding pipeline in Active Directory. I setup the RBAC matrix and ensured users were given access ONLY according to their role. I also created a mock service ticket which showed a user who had been provisioned with an incorrect level of access. 

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
* Built the NMG.com Active Directory domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis

