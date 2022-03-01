# Actors

A physical human user can play multiple roles when interacting with the system. We can say that they are acting in a specific role and therefore we refer to them as actors. A single human user can play multiple roles and thus be represented by multiple actors in the documentation.

The following diagram provides a breakdown of the various actors that have been identified.

![Actors Diagram](actors.drawio.svg)
## User
A User is a person that is authorised to use the system.
## Internal User
An internal user is an employee of the oprganization running StoreMan. An Internal User will have have an account in the organization's LDAP user store.
## System Administrator
A System Administrator is a specific type of user that is authorised to make administritive changes to the system.
## Super User
A Super User is a special type of System Administrator that is autorized to make highly sensitive administrative changes.
## Registration Official
A Registration Official is authorized to register new property items in the system.
## Storage Official
A Storage Official is authorized store property items in storage locations assigned to them and to perform tasks around the storage location. Storage Officials also hand over property items in one of there storage locations for approved requests.
## Storage Location Administrator
A Storage Location Administrator can create and modify storage locations and assign storage officials to storage locations.
## Request Creator
A Request Creator is autorized to create requests for property items.
## Disposal Request Creator
A Disposal Request Creator is a special type of Request Creator that can create disposal requests.
## Request Approver
A Request Approver is autorized to approve or request requests for property items.
## External User
An External User is a user that is not employed by the organization running StoreMan.
## Transport Contractor
A Transport Contractor is an external user contracted by the organization running storeman to transport property items between locaations where the StoreMan system is used.
## Member Of Public
A Member Of Public can use the StoreMan system to view the status of a property item that belongs to them.