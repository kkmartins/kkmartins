# Hi, I'm Kirk

**IT Specialist | Microsoft 365 Administration | Identity & Security | Healthcare IT | Automation**

I'm an IT specialist with two years of experience, currently running a one-person IT department for a substance use treatment facility based in California. I transitioned into IT from customer support, and I bring that experience into how I troubleshoot, explain technical issues, and support the people who use the systems I manage.

I administer the organization's Microsoft 365 tenant end to end, alongside Azure, Okta, and Kipu CRM/EMR. My work spans daily support, identity and access management, endpoint deployment, security administration, collaboration platforms, and business process automation through Power Automate and integrations between ClickUp and Microsoft 365.

This portfolio documents the systems I build, the problems I solve, and the evidence behind the results.

## What I manage

| Area | Responsibilities and platforms |
|---|---|
| Microsoft 365 tenant | Tenant-wide administration through the Microsoft 365 admin center and associated workloads |
| Security and information protection | Microsoft Defender and Microsoft Purview administration |
| Identity and access | Microsoft Entra ID and Okta administration |
| Endpoints and Cloud PCs | Microsoft Intune, Windows application deployment, and Windows 365 |
| Cloud infrastructure | Microsoft Azure and company VPN infrastructure |
| Collaboration | SharePoint and Microsoft Teams administration |
| AI administration | Administration of AI capabilities within the Microsoft 365 environment |
| Healthcare applications | Kipu CRM/EMR administration |
| Integration and automation | Power Automate cloud flows, ClickUp ↔ Microsoft 365 integrations, webhooks, and workflow automation |

## Healthcare IT and HIPAA

I work in an environment where the systems I build and administer must meet HIPAA requirements. I have practical knowledge of HIPAA compliance and apply it when making decisions about access, security, and how staff use company systems.

## From customer support to IT

Customer support taught me to listen carefully, ask useful questions, and make complex issues understandable. As a one-person IT department, I combine that foundation with hands-on administration and ownership of technical problems from investigation through resolution.

I work across platforms and consider how changes affect the entire environment—for example, how an identity policy affects access to a Cloud PC, or how an endpoint deployment affects a staff member's ability to work.

## Featured projects

### Business Process Automation with Power Automate

I build workflows for staff that connect business processes with Microsoft Teams, Outlook, SharePoint, Excel, Microsoft Forms, and external services. My automation work includes event-triggered flows, scheduled reminders, approval workflows, and HTTP/webhook integrations, including workflows shared with staff for their day-to-day operations.

Examples from my work:

- **Staff operations:** absence notification routing and overtime request approvals.
- **Admissions coordination:** routing phone, web form, and chat admission alerts into Teams channels and group chats.
- **Billing and administrative workflows:** invoice request notifications, scheduled billing reminders, and insurance renegotiation reminders.
- **Communications:** Dialpad and call-tracking SMS notifications delivered to Teams.
- **IT operations:** Veeam backup webhook notifications and an internal helpdesk mailbox auto-reply workflow.
- **Task coordination:** a meeting-to-ClickUp proof of concept.
- **Staff reporting:** end-of-shift form collection into Excel with record IDs, email notifications, and scheduled daily digests.
- **Meeting coordination:** meeting summary and meeting-ID helper workflows.
- **Maintenance and shift operations:** maintenance email-to-Teams notifications, scheduled interaction summaries, and SharePoint-triggered shift record creation.

My reviewed cloud-flow inventory includes **39 flows across My flows and Shared with me**: 24 in my own list and 15 in the shared list. These include enabled workflows, disabled or retired flows, and proof-of-concept work; related channel/group-chat variants are separate flows. Individual case studies will document the trigger, routing logic, integrations, validation, and outcome of selected workflows.

### Automated VPN Deployment for Windows 365 Cloud PCs

Built and tested an Azure-hosted OpenVPN pilot, then prepared Intune deployment of the client and a device-specific background VPN configuration.

- Investigated an installation failure and traced it to an incorrect Windows service name in the deployment script.
- Corrected the deployment; Intune reported one successful test-device installation with zero failures or pending installs.
- Verified VPN connectivity after reboot and the expected VPN egress address in fresh Okta activity.
- Identified a sign-in dependency that affected Cloud PC entry and documented the need for revised policy scope.

**Status:** Working pilot, with broader rollout and security validation in progress. The case study is being prepared for publication.

### Project Upskill — Windows Enterprise Homelab

Outside work, I'm building a personal homelab to deepen my Windows Server, networking, and identity fundamentals as I work toward greater specialization in Microsoft cloud and security technologies.

**Completed and documented:**

- Set up a Windows Server VM and a Windows 11 client VM in a Hyper-V lab.
- Investigated APIPA addressing when no DHCP server was available and configured static IPv4 addresses on a shared lab subnet.
- Troubleshot failed ping tests, adjusted Windows Firewall rules, and verified connectivity between both VMs.
- Recorded the configuration, PowerShell commands, troubleshooting steps, results, and next actions in lab notes.

**Planned next:** Active Directory Domain Services, DNS, DHCP, domain joining, and Group Policy practice. These are learning goals, not completed deployments.

**Status:** In progress. Initial VM networking is documented; the Windows Server VM has not yet been promoted to a domain controller.

## How I approach IT work

- **Start with the operational need.** Understand what staff need to accomplish and the constraints of a healthcare setting.
- **Think across systems.** Consider identity, devices, applications, security, and the user workflow together.
- **Automate repeatable work.** Build integrations and deployment workflows that reduce recurring manual administration.
- **Validate the outcome.** Test installation, service operation, and user access separately while preserving recovery options.
- **Document the evidence.** Record what worked, what failed, and what still needs validation.

I use AI-assisted research and scripting as part of my workflow, alongside hands-on administration, troubleshooting, and validation.

## Portfolio focus

- Microsoft 365 administration and security
- Cloud PC infrastructure and endpoint deployment
- Identity and application access
- Power Automate business processes and ClickUp–Microsoft 365 integrations
- Healthcare IT operations and compliance-informed system design
