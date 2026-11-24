## Problem: The sign-in method you are trying to use isn't allowed
I encountered this problem when I haven't start my Home-lab in weeks.
This occured when every users in the department (Under Default Domain Controller and Defaul Domain Policy Inherited) are all affected.
Except Helpdesk and Admin accounts that have elevated accounts.

Writing this to reminder to create theory and dignostics steps:
1. Check the GPO
2. Check Active Directory users and computers
3. Check Event Viewer


3. I remotely connect Desktop-1 (Have to enable inbound firewall rules : Remote Log Management) to view Windows > Security.
The ID im looking for is : ID 4625. That should give me a clue where the problem start.
