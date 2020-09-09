# Fundamentals of Active Directory, workgroups and domains

## The five services within Active Directory.

1. AD Domain Services (AD DS)  
2. AD Lightweight Directory Services (AD LDS)  
3. AD Federation Services (AD FS)  
4. AD Certificate Services (AD CS)  
5. AD Rights Management Services (AD RMS)  

### Is AD a database or a directory?

Some consider AD as a database because you can write data to,   
retrieve data from, and store data in it. However, it’s more of a directory  
than a database since it’s optimized for read operations rather than write  
operations. While you can add new data to AD, the existing data usually doesn’t   
undergo many changes.

### The AD structure

We need to consider two sides of its structure:  

The logical side: This is the hierarchy of objects such as users, computers, groups,  
and organizational units.

The physical side: When designing the physical side, the administrator needs to think about the servers  
that provide the AD services and contain all the critical directory information. 

### Workgroups vs. domains

_A workgroup is a peer-to-peer network with no central authentication._  

_The domain setup ensures better security as we can give varying degrees  
of permissions for different users or groups of users._  


## What is the benefit of AD over a peered/workgroup network?  

Some benefits are:  

Email to phone synchronisation | Centrally managed security | Centrally managed password policy 

Just to name a few

https://www.windows-active-directory.com/fundamentals-of-active-directory-workgroups-and-domains.html

# The structures and benefits of organizational units  

Organizational units (OUs)  
Functional/divisional
Geographic
Object

### Benefits of using OUs

Manage objects efficiently    
Deploy Group Policy Object (GPO) settings  
Delegate administrative control  

### Why might an organization use organizational units?   

Becasue they are useful when you want to deploy group policy settings to a subset of users, groups,   
and computers within your domain. 

https://www.windows-active-directory.com/the-structures-and-benefits-of-organizational-units.html

# Manage Role Based Access Control with Server Manager

* Create a User Role for Access Control  
* Create an Access Policy  
* Set Access Scope for a DNS Zone  
* Set Access Scope for DNS Resource Records  
* View Roles and Role Permissions  



### Have a look around Microsoft’s official documentation to get an idea of processes surrounding RBAC.
