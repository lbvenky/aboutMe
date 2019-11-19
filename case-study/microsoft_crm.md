# Microsoft CRM

## Background

- Microsoft Dynamics CRM focuses mainly on sales, marketing, and service (help desk) sectors
- Microsoft CRM is a part of the Microsoft Dynamics family of business applications (D365)
- Microsoft has been marketing Dynamics CRM as a CRM platform and has been encouraging partners to use its once proprietary, now Open Source (.NET based) framework to customize it. 

## Versions

- Workgroup Edition
   - This edition is only allowed 5 CALs maximum,it is not possible to add more CALs. If more CALs are needed, an upgrade to Professional or Enterprise should be done. Also all the server roles are installed on 1 machine and cannot be separated. You can only create 1 organization in this version and the use of external connectors is not allowed. This version is ideal for small organizations that can use it with the SQL Server Workgroup Edition and on a Windows Small Business Server.

- Professional Edition
   - The Professional Edition has the same functionality as the Workgroup Edition except there is no limit on the CALs. If the installation profile calls for supporting either multiple organizations or servers, the Enterprise Edition is required.

- Enterprise Edition
   - Has the same functionality as the Professional Edition but without limits. This version is to be used when multiple divisions should be accessing CRM from one platform.

- Service Provider Edition
   - This edition is actually an Enterprise Edition that is configured to accept Internal user requests from AD and external user requests through IFD (Internet Facing Deployment). This version is mostly implemented by Microsoft Partners that offer Hosted CRM functionality, when letting external users connect to this CRM version through the Internet.
