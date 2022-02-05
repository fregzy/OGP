# OGP-Installer

Script supports auto install agent or panel for any os supported


1-Click Agent & Panel Installation

| OS     | Version |   |
|--------|---------|---|
| Ubuntu | 20.04   | ✅ |
|        | 18.04   | ✅ |
|  	 | 16.04   | ✅ |
|        | 20.04   | ✅ |
| Debian | 10      | ✅ |
|        | 9       | ✅ |
| 	 | 8       | ✅ |
| CentOS | 8      | ✅ |
|        | 7       | ✅ |
| 	 | 6       | ✅ |

### Panel Installation

    sudo apt update && apt -y upgrade && apt -y install curl && curl -O https://raw.githubusercontent.com/fregzy/OGP/master/panel.sh && chmod 777 panel.sh && ./panel.sh

### Agent Installation 
	
    sudo apt update && apt -y upgrade && apt -y install curl && curl -O https://raw.githubusercontent.com/fregzy/OGP/master/agent.sh && chmod 777 agent.sh && ./agent.sh

### mysqli_real_connect(): (HY000/1698): Access denied for user 'root'@'localhost'

    mysql -u root -p
    اكتب باسورد القاعدة
    use mysql;
    update user set plugin='' where User='root';
    FLUSH PRIVILEGES;
    exit
    
### VPS Hosting
https://www.host1fire.com/
