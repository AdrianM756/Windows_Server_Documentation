![image](https://cdn.worldvectorlogo.com/logos/active-directory-1.svg)

## Active Directory

[Active Directory Domain Services (AD DS)](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview) is a directory service that organizes and stores information about network objects (like users and devices) in a hierarchical structure. It:

* Uses a structured data store to organize data logically.

* Holds user information such as names, passwords, and contact details.

* Provides secure access to this data for authorized users and administrators on the network.

* Makes it easy to locate, manage, and utilize directory information across the system.
<br>

Active Direcrory also includes:

* [Schema](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2003/cc756876(v=ws.10)) - Defines the structure of the directory—it sets rules for object classes, attributes, and naming formats. Think of it as the blueprint for all directory data.

* [Global Catalog](https://learn.microsoft.com/en-us/windows/win32/ad/global-catalog) - A searchable master index containing information about every object in the directory, across all domains. It lets users and admins find what they need without knowing where it’s stored.

* [Query & Index Mechanism](https://learn.microsoft.com/en-us/windows/win32/ad/searching-in-active-directory-domain-services) - Provides search and lookup capabilities. Objects can be easily published and retrieved by users or applications through this built-in search system.

* [Replication Service](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/replication/active-directory-replication-concepts) - Keeps directory information synchronized across all domain controllers. When a change is made, it’s automatically distributed network-wide to ensure consistency.
  
