# OGP-Installer

Script supports auto install agent or panel for any os supported


1-Click Agent & Panel Installation

| OS     | Version |   |
|--------|---------|---|
| Ubuntu | 22.04   | ✅ |
|        | 20.04   | ✅ |
|  	 | 18.04   | ✅ |
|        | 16.04   | ✅ |
| Debian | 10      | ✅ |
|        | 9       | ✅ |
| 	 | 8       | ✅ |
| CentOS | 8      | ✅ |
|        | 7       | ✅ |
| 	 | 6       | ✅ |


### Panel Installation

    sudo apt update && apt -y upgrade && apt -y install curl && curl -O https://raw.githubusercontent.com/BrilloCloud/OGP-Installer/main/install-panel.sh && chmod 777 install-panel.sh && ./install-panel.sh

### Agent Installation 
	
    sudo apt update && apt -y upgrade && apt -y install curl && curl -O https://raw.githubusercontent.com/BrilloCloud/OGP-Installer/main/install-agent.sh && chmod 777 install-agent.sh && ./install-agent.sh
    
### How To Fix ( MySql Offline ) [ mysqli_real_connect(): (HY000/1698): Access denied for user 'root'@'localhost' ]

    mysql -u root -p
    
###

   use mysql;
   
###

   update user set plugin='' where User='root';
   
###

   FLUSH PRIVILEGES;
   
###

   exit
   
###

### If You Want To Buy VPS Contact Us BrilloCloud Discord
https://discord.gg/psttH7RAE4
