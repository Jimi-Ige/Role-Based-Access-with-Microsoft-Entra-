# Role-Based-Access-with-Microsoft-Entra-
Enhances security by enforcing the principle of least privilege, ensuring appropriate access control across cloud systems.

**Overview:** The lab demonstrates the application of Role Based Access with Microsoft Entra.

**Prerequisites:**
✅ Azure Subscription 
✅ Access to Microsoft Entra ID 
✅ Knowledge of RBAC and IAM principles
✅ Administrator or equivalent permissions for RBAC configuration

**High-Level Steps with Explanations:**

 **1. Configured Azure Subscription Access Control:** I navigated to Azure Active Directory to identify my subscription. I then reviewed the Access Control (IAM) settings to understand the available roles and permissions.
Establishing clear access control at the subscription level ensures that only authorized personnel can manage high-level resources, reducing security risks and preventing unauthorized access. This centralizes management, simplifies audits, and maintains consistent security standards.

 **2. Assigned a Built-In Role:** I selected the Access Control (IAM) option in my subscription. Then, I assigned a built-in role (e.g., Virtual Machine Contributor) to a specific group (e.g., Help Desk) within my subscription.
Assigning built-in roles allows you to leverage predefined access controls that align with standard job functions. Using these standardized roles streamlines role management reduces configuration time, and ensures that users have appropriate permissions to perform their tasks without excessive access.

 **3. Created and Assigned a Custom Role:** I defined a custom role (Custom Support Request) by selecting Roles under Access Control and configured the permissions.
Custom roles allow you to tailor permissions to fit business needs, providing fine-grained control over who can perform what actions. This minimizes the risk of privilege abuse and enforces least-privilege access, aligning user capabilities with organizational security policies.

 **4. Verified Access Permissions:** Finally, I use Azure’s Check Access feature to confirm that the Help Desk group has the correct access permissions based on role assignments.
Regularly verifying access permissions ensures that access rights are up-to-date and align with organizational policies. This proactive approach prevents privilege creep, supports compliance, and maintains a secure environment by quickly identifying and addressing access discrepancies.

**Reference Link(s):**
* https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02a_Manage_Subscriptions_and_RBAC_Entra.html
