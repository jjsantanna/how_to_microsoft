# how_to_microsoft
How to do things using Microsoft tools

### Onboard a Machine/VM in Defender for Endpoint (MDE)
- Manually:
  - go to security.microsoft.com -> settings -> endpoints -> onboarding -> Download the onboarding package -> open the vm and run the file you've downloaded
- Via Microsoft Endpoint Manager (Intune):
  - go to https://endpoint.microsoft.com -> endpoint security -> microsoft defender for endpoint -> turn on "Allow Microsoft Defender for Endpoint to enforce Endpoint Security Configurations" AND "Connect Windows devices to Microsoft Defender for Endpoint" -> login in a VM with credentials from the tenant (ex. @zuidgolf) (Make sure this user has Intune license or M365 E3 or similar)
