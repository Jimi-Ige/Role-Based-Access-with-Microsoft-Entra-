# Role-Based-Access-with-Microsoft-Entra-
Enhances security by enforcing the principle of least privilege, ensuring appropriate access control across cloud systems.

**Overview:** The lab demonstrates the application of Role Based Access with Microsoft Entra.

**Prerequisites:**
✅ Azure Subscription 
✅ Access to Microsoft Entra ID 
✅ Knowledge of RBAC and IAM principles
✅ Administrator or equivalent permissions for RBAC configuration

**Steps with Explanations:**
1. Configure Azure Subscription Access Control
* Navigate to Azure Active Directory and identify your subscription.
* Review the Access Control (IAM) settings and understand the roles and permissions available.
2. Assign a Built-In Role
* Select the Access Control (IAM) option on your subscription.
* Assign a built-in role (e.g., Reader or Contributor) to a specific user or group within the subscription.
3. Create and Assign a Custom Role
* Define a custom role by selecting Roles under Access Control.
* Configure the permissions specific to the custom role and assign it to a user or group.
4. Manage Role Assignments at Resource Scope
* Navigate to a specific resource group or resource within your subscription.
* Use the Access Control (IAM) to assign roles at a more granular level, like a resource group or specific resource.
5. Verify Access Permissions
* Use Azure’s Check Access feature to confirm that users or groups have the correct access permissions based on their role assignments.
* Test role effectiveness by logging in as the assigned user or group to ensure proper permissions are granted.
