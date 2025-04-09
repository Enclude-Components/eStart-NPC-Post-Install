# eStart NPC Post-Install Add-On
An add-on to eStart-NPC orgs. Adds Person Account functionality.

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
- Muting Permission Sets
  - eStart NPC Permissions Muted
- Permission Set Groups
  - eStart NPC Permissions
- Permission Sets
  - eStart Person Accounts
- Standard Value Sets
  - LeadSource (Account / Contact Lead Source)