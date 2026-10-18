# Hi, I'm Kirk

I work on practical IT projects involving cloud infrastructure, endpoint management, automation, and troubleshooting. This portfolio documents what I build, how I investigate problems, and the evidence behind the results.

## Areas I work with

- **Cloud infrastructure:** Microsoft Azure and Windows 365 Cloud PCs
- **Endpoint management:** Microsoft Intune, Windows application packaging, and deployment
- **Networking and access:** OpenVPN, routing, and Okta access workflows
- **Automation:** PowerShell and Python
- **Technical documentation:** implementation guides, troubleshooting records, and validation checklists

## Featured project

### Automated VPN Deployment for Windows 365 Cloud PCs

Built and tested an Azure-hosted OpenVPN pilot, then prepared Intune deployment of the client and a device-specific background VPN configuration.

- Investigated an installation failure and traced it to an incorrect Windows service name in the deployment script.
- Corrected the deployment; Intune reported one successful test-device installation with zero failures or pending installs.
- Verified VPN connectivity after reboot and the expected VPN egress address in fresh Okta activity.
- Identified a sign-in dependency that affected Cloud PC entry and documented the need for revised policy scope.

**Status:** Working pilot, with broader rollout and security validation in progress. The case study is being prepared for publication.

## How I approach IT work

I break changes into manageable steps, preserve recovery access, and test installation, service operation, and user outcomes separately. I document both successful results and remaining limitations.

I use AI-assisted research and scripting as part of my workflow, alongside hands-on administration, troubleshooting, and validation.

## Currently developing

- Repeatable deployment and diagnostic workflows
- Clearer evidence for infrastructure and endpoint changes
- A portfolio of practical IT implementation and troubleshooting case studies
