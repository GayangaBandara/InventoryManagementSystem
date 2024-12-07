Inventory Management System

What It Does
The Inventory Management System is a robust application designed to help businesses efficiently manage their inventory operations. It tracks products, processes orders, and provides tools for managing suppliers, customers, and categories. The system automates repetitive tasks, reduces manual errors, and enhances decision-making with real-time insights and reporting capabilities. 

By leveraging intuitive design and advanced functionality, this system empowers businesses to:
	- Maintain accurate stock levels.
	- Monitor and fulfill orders efficiently.
	- Generate actionable reports for inventory analysis.
	- Receive notifications for critical updates like low stock or pending tasks.

Key Entities

1.Product
   - What it Represents: Items stored in the inventory.
   - Attributes:
     - Product ID
     - Name
     - Price
     - Quantity

   - Functions:
     - Update product details.
     - Track stock levels in real time.

2.Order
   - What it Represents: Orders placed by customers or orders from suppliers.
   - Attributes:
     - Order ID
     - Product(s) ordered
     - Quantity
     - Supplier or Customer details
     - Status (e.g., Pending, Shipped, Completed)

   - Functions:
     - Create and manage orders.
     - Update order statuses.

3. Customer
   - What it Represents: Customers purchasing products.
   - Attributes:
     - Customer ID
     - Name
     - Contact Information
   - Functions:
     - Manage customer records and order histories.


4. Supplier
   - What it Represents: Companies or individuals providing products.
   - Attributes:
     - Supplier ID
     - Name
     - Contact Information
   - Functions:
     - Maintain supplier records for procurement.

5. Category
   - What it Represents: Grouping of products into logical categories.
   - Attributes:
     - Category ID
     - Name
   - Functions:
     - Organize products for easy navigation and filtering.

6. Admin
   - What it Represents: Users with full control over the system.
   - Attributes:
     - Admin ID
     - Username
     - Email
   - Functions:
     - Assign tasks to other admins.
     - Generate and review reports.
     - Oversee system operations.

7. Task
   - What it Represents: Assignments or actions delegated to admins.
   - Attributes:
     - Task ID
     - Description
     - Assigned By
   - Functions:
     - Track progress of administrative tasks.

 8. NotificationService
   - What it Represents: Communication tool for system alerts.
   - Attributes:
     - Notification ID
     - Message Content
   - Functions:
     - Send notifications for:
       - Low stock alerts.
       - Order updates.
       - Task assignments.
