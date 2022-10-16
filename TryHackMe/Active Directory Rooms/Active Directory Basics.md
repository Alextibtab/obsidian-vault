---
platform: THM
---
# Windows Active Directory Basics
## Windows Domains
A windows domain is a group of users and computers under the administration of a given business. The main idea behind a domain is to centralise the administration of common components of a windows network into a single repository called **Active Directory (AD)**. The server that runs the active directory services is known as a **Domain Controller (DC)**.

The main advantages of having a configured windows domain are:
- **Centralised Identity Management**: All users across the network can be configured from Active Directory with minimum effort,
- **Managing Security Policies**: You can configure security policies directly from Active Directory and apply them to users and computers across the network as needed.

The core of any Windows Domain is the **Active Directory Domain Service (AD DS)**. This service acts as a catalogue that holds the information of all of the "objects" that exist on the network. Amongst the many objects supported by AD, there is users, groups, machines, printers and many others.

### Users
Users are one of the most common object types in Active Directory. Users are one of the objects known as **security principals**, meaning that they can be authenticated by the domain and can be assigned privileges over **resources** like files or printers. A security principal is an object that can act upon resources in the network.

Users can be used to represent two types of entities:
- **People**: users will generally represent persons in an organisation that need to access the network 

tags: #THM #Active_Directory 