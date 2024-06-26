# Onboard Automator With Azure

Work In Progress!


# Services Used:

  ### Azure AD
  
  ### Azure Logic Apps
  
  ### Azure Email Service (part of Logic Apps connector)
  
  ### Azure Resource Manager
  

# **Step 1: Azure AD Setup**
Set up a new Azure AD instance (if not already present) using the Azure portal.
   
# **Step 2:Logic App Workflow Design**
Design a Logic App workflow triggered by an event (like an entry in a SharePoint list or an email to a specific mailbox) indicating a new employee hire.
   
# **Step 3: Azure AD User Creation**
Use the Azure AD connector in Logic Apps to automatically create a new user in Azure AD based on the trigger event's details.
   
# **Step 4: Role and Group Assignment**
Assign predefined roles and groups to the new user based on the job position or department indicated in the trigger.
   
# **Step 5: Resource Provisioning**
Use the Azure Resource Manager connector in Logic Apps to provision any necessary Azure resources for the user (like VMs or specific permissions).
   
# **Step 6: Welcome Email**
Leverage the Email connector in Logic Apps to send a welcome email to the new hire with instructions and necessary access details.
   
# **Step 7 Monitoring and Review**
Monitor and review the onboarding process through Logic Apps runs history and Azure AD logs to ensure smooth operations.
