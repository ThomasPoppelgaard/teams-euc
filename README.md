# teams-euc
Teams VDI 2.0 icons 
This share contains ico files for new Microsoft Teams that was released in 2024 and which is used for End User Computing environments
The icons can be used to publish Microsoft Teams as RemoteApp in Azure Virtual Desktop or creating shortcuts inside Desktops in EUC environments

Microsoft dont share any path for Teams ICON so a solution is to copy the Teams ICONS to example: 
"C:\ProgramData\Microsoft\Windows\"

New Teams is installed as an MSIX package, which is a format used for applications from the Microsoft Store. The directory path for an application installed from the Microsoft Store includes the version number, which changes each time an application is updated. To publish new Teams as a RemoteApp, follow the steps in Publish Microsoft Store applications, and for the path enter shell:appsFolder\MSTeams_8wekyb3d8bbwe!MSTeams

You can publish new Teams in Azure Virtual Desktop RemoteApp

**Application Path:**
shell:appsFolder\MSTeams_8wekyb3d8bbwe!MSTeams

**Application Identifier:**
shell:appsFolder

**Name:**
Microsoft Teams

**Icon path:**
"C:\ProgramData\Microsoft\Windows\ms-teams_new.ico"

Source:
https://learn.microsoft.com/en-us/azure/virtual-desktop/teams-on-avd

/TPoppelgaard
