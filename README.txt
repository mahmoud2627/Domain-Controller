Domain Controller For educational organizations and Their Branches :

🔍 Project Overview:
- Web Servers: We set up two web servers (http://www.web1.com and https://www.web2.com) to handle different tasks and tested their accessibility.
- Domain Controllers: Configured DC1 within the ITI.LOCAL domain and established a child domain, Alex.ITI.LOCAL.
- DNS Configuration: Implemented DNS to ensure proper resolution and accessibility of our web servers.
- Network Setup: Connected multiple PCs (PC1, PC2, PC3, PC4) and configured them with specific permissions and roles.
- RODIC: Implemented RODIC (Read-Only Domain Controller) to enhance security and manageability within the network.

👥 Key User Configurations:
- USR1@ITI.LOCAL: Restricted from logging into PC1 on Fridays.
- User2@ITI.LOCAL: Can log in to PC1 and remotely access DC1 (not a Domain Admin).
- User3@ITI.local: Found WinRAR installed on PC1 from a domain admin.
- User4@ITI.LOCAL & User3@ITI.LOCAL: Restricted from using flash memory and control panel, with a mandatory ITI logo wallpaper.
- User6@Alex.ITI.LOCAL: Can log in to PC1 remotely when in the Smart Village and browse web2 from local DNS in the Alex domain.
- User7: Local user on PC4 with the ability to remotely manage the web server with administrative privileges.
- User8@ITI.LOCAL: Can log in only to RODIC, create users, and shut down RODIC.
- User9@ITI.LOCAL: Can log in to PC3 and replicate their password to RODIC.

🌐 Key Achievements:
- Successfully configured and tested web server access and DNS resolution.
- Established a child domain, Alex.ITI.LOCAL for enhanced network segmentation.
- Implemented robust user permissions and access control for security.
- Demonstrated proficiency in network setup and management.




