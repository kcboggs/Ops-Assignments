# What is Microsoft Azure?
_Microsoft Azure, formerly known as Windows Azure_  

Microsoft Azure is a cloud computing service that works similarly to Amazon Web Services  
(AWS) and the Google Cloud Platform.

You pay for as many computing resources as you need, and not a specific number of hardware   
servers on a rack somewhere. Services you deploy in this way can either be public servers   
available to everyone, or part of a “private cloud” that’s just used in an organization.  

# What Can Microsoft Azure Do?  

The Microsoft Azure website provides a directory of hundreds of different services you can  
use, including full virtual machines, databases, file storage, backups, and services for  
mobile and web apps.  

# Azure Active Directory and Windows 10  

Allows organizations to have centralized administration features without requiring them  
to host their own Active Directory server (and set up the often complicated infrastructure   
and access permissions needed to make it work remotely).  

https://www.howtogeek.com/337961/what-is-microsoft-azure/

# Identity management  

Most architectures have shared services that are hosted and accessed across networks. Those  
services share common infrastructure and users need to access resources and data from anywhere.  
For such architectures, relying on just network security controls isn't enough.  

## How are you implementing Zero-Trust in your design?  

* Support a single enterprise directory.
* Keep the cloud and on-premises directories synchronized, except for high-privilege accounts.
* Enforce and measure key security attributes when authenticating all users, especially for  
  high-privilege accounts.
* Have a separate identity source for non-employees.
* Use passwordless and multi-factor authentication.
* Blocking legacy protocols and authentication methods.  

# Use a dingle enterprise directory

_This single-source approach increases clarity and consistency for all roles in IT and Security teams._

# Use role-based access control (RBAC)

_Use Azure RBAC to control the level of access for users. Assign built-in roles to users, groups,   
service principals, and managed identities._  

# Synchronize the hybrid identity systems

_Keep your cloud identity synchronized with the existing identity systems to ensure consistency and  
reduce human errors._  

# Use a separate identity source for third-party accounts

Use cloud identity services that are designed to host third-party accounts. Grant the appropriate   
level of access to those external entities instead of the default permissions that are given to  
full-time employees.  

* Azure AD – Employees and Enterprise Resources
* Azure AD B2B – Partners  

# Use modern password protection  

* Azure AD – Employees and Enterprise Resources
* Azure AD B2B – Partners
* Azure AD B2C – Customers, citizens  

# Use modern password protection

Adopt passwordless authentication and multi-factor authentication (MFA) over time. You can   
also reduce use of passwords through the use of Managed Identities.  

* Password Guidance
* NIST guidance

# Disable legacy authentication methods

Don't use legacy protocols for internet-facing services. For Azure AD-based accounts,  
configure Conditional Access to block legacy protocols.

# Use cross-platform credential management

Use a common identity provider:

* Azure Active Directory (AD), for authenticating all platforms 
* (Windows, Linux, and others) and cloud services  

Azure AD can authenticate on Windows: 
* Linux, Azure
* Office 365
* Amazon Web Services (AWS)
* Google Services
* (remote access to) legacy on-premises applications
* Third-party Software as a Service providers

https://docs.microsoft.com/en-us/azure/architecture/framework/security/design-identity
