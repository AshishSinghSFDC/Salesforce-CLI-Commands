# Salesforce-CLI-Commands
This repository contains commonly used Salesforce CLI Commands

1. View all authenicated Orgs in CLI
sfdx force:org:list

2. Open default Org
sfdx force:org:open

3. Open target Org
sfdx force:org:open -u [alias/username]

4. Create a scratch Org
sfdx force:org:create edition=Developer -a [set alias name of scratch Org] -v [authorized DevHub username]

5. Set Default Org
sfdx force:config:set defaultusername=[ORG ALIAS]
