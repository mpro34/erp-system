# inventory
An ERP System with only an inventory management app so far.

# Models

Employee Model - Track each employee, what they have access to, what they have checked out, etc.

Item Model - Parent model that each inventory item inherits from with base information.

Each item will have a checked-out flag and will organize the duplicate items by id.


# Admin Site

The Django admin site will be used by site administrators to add/delete Inventory items, add/delete Employees, etc.
