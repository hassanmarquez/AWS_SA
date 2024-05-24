# SERVICES

## IAM: Users & Groups
#### IAM (Identity and Access Management)
- **Root account** Should not be used or shared 
- **Users:** They are people in the organization and can be grouped.
- **Groups:** Grouped users.

<img title="Example" alt="Example" src="/Users/hmarquez/Documents/GitHub/AWS_Solution_Architect_Associated/Services/Images/IAM/Groups_example 1.png">

<img title="Example2" alt="Example2" src="/Users/hmarquez/Documents/GitHub/AWS_Solution_Architect_Associated/Services/Images/IAM/Groups_example 2.png">

--> Users or groups can be assigned JSON documents called policies.

--> These define the permissions of the users.

--> Do not give more permissions than the user needs.

## AIM Policies Structure
   
Consist of: 
- Version: Language version.
- Id: Identifier (Optional).
- Statement: one or more individual statements (Required). 
      
     **Statement consists of:**
  - **Sid:** identifier for the statement.
  - **Effect:** Statements to deny or allows
  - **Principal:** account/user/role to apply the policy
  - **Action:** list of actions to allows or denies
  - **Resource list:** List of resources where the policy will be apply

  *The following is an example of the creation of the permissions using JSON template:*

<img title="Example2" alt="Example2" src="/Users/hmarquez/Documents/GitHub/AWS_Solution_Architect_Associated/Services/Images/IAM/permissions.png ">






<!--
#Comment
-->
