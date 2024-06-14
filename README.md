# eStart NPC Post-Install Add-On
An add-on to eStart-NPC orgs. Adds Person Accounts and Account Contact Relationship functionality.

## Deploy
<a href="https://githubsfdeploy.herokuapp.com?owner=Enclude-Components&repo=eStart-NPC-Post-Install&ref=main">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

***After deploying, you will need to activate the General Person Account record type for all active profiles***

## Contents

- Flows
  - Contact OnCreate CreatePersonAccount
  - PersonAccount OnCreateUpdate CommunicationPreferences
- Layouts
  - Account - eStart Default Account Layout
  - AccountContactRelation - eStart ACR Page Layout
  - PersonAccount - eStart Person Account Layout
- Account
  - List Views
    - All Business Accounts
    - All Person Accounts
    - My Business Accounts
    - My Person Accounts
  - Record Types
    - Business Account
- Person Account
  - Compact Layouts
    - eStart Compact Person Account Layout
  - Record Types
    - Person Account
- Permission Set Groups
  - eStart NPC Permissions
- Permission Sets
  - eStart Account Contact Relationships
  - eStart Person Accounts
- Standard Value Sets
  - AccountContactMultiRoles (ACR Roles)
  - LeadSource (Account / Contact Lead Source)