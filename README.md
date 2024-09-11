# User-Analytics-Workbook
A custom Sentinel Workbook that provides an overview individual user activities and attributes
# Description
The User Analytics Workbook is designed to provide a comprehensive overview of individual user activities and attributes within your organization. This custom solution aggregates and visualizes critical data related to users, including their group memberships, personal information, sign-in activities, recently assigned roles, behaviour analysis, assigned Entra ID (Formerly known as Active Directory (AD)) roles, risk status, and any recent incidents associated with the user.

By consolidating this information into a single, user-friendly workbook, organizations can easily monitor and analyze user behaviour, track changes in roles and responsibilities, and assess potential risks associated with user accounts. This solution enhances your ability to conduct detailed user analytics, supporting better decision-making and improved security oversight.

# Business Requirements
•	Detailed User Overview: The need to compile and visualize extensive information about user activities and attributes for enhanced monitoring and analysis.

•	Behaviour Analysis: The requirement to track and assess user behaviour, including sign-in activities and role changes, to identify potential risks.

•	Risk Management: Integration of risk status and recent incidents to provide a holistic view of user-related security concerns.

# Prerequisites
•	An Active Azure Subscription

•	An Active Sentinel Instance

•	Sentinel Contributor Role

•	Required data sources including Sign-in Logs, Audit Logs, Azure Activity and UEBA logs.

# Setup Guide
The following provides step-by-step instructions to deploy the Workbook:

**Step 1: Access Microsoft Sentinel**

 • Sign in to the Azure portal: https://portal.azure.com.
 
 • In the search bar, type Microsoft Sentinel and click on it from the results.
 
 • Select the appropriate Sentinel workspace where you want to deploy the custom workbook.
 
**Step 2: Navigate to the Workbooks Section**

 • Once in the Sentinel workspace, on the left-hand panel, scroll down and click on Workbooks under the Threat Management section.
 
**Step 3: Create a New Workbook**

 • At the top of the Workbooks page, click on the + New button to start creating a custom workbook.
 
 • You’ll now see the workbook editor interface, where you can start designing your custom workbook.
 
**Step 4: Import a Custom Workbook Template**

 • If you already have a custom workbook template in JSON format, click on the "Advanced Settings" gear icon (⚙️) in the top right corner of the workbook editor.
 
 • In the menu, choose "Edit as Code".
 
 • Copy your custom workbook JSON code and paste it into the code editor.
 
 • Click Apply to load the template into the workbook.
 
**Step 5: Save the Workbook**

 • Once your custom workbook is ready, click Save at the top of the page.
 
 • Provide a name and description for your workbook.
 
 • Select Save to Microsoft Sentinel or My Workbooks to choose the visibility of the workbook. Saving it to Sentinel will make it available to all users in the workspace.

# Solution Insights: Workbook Visuals
![image](https://github.com/user-attachments/assets/43872d7a-ba00-4e8b-8595-0e8da59062ee)



