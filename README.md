# UML_Assignment

Basic Assignment: Library Management System

Class Diagram <br>
The Class Diagram for the Library Management System shows the main components of the system and how they are connected. There's a base class called Person that contains common details like name and email. From this, we get two main types of users: Member and Librarian. Members can borrow and return books, while librarians handle things like registering new members and adding books to the system. The Book class includes details such as title, author, ISBN, and whether the book is available. A member can borrow multiple books, and the librarian manages both books and members. The diagram helps to clearly show the structure of the system and the roles of each part.

![image](https://github.com/user-attachments/assets/3b50a2cd-ab96-4dc4-9c7e-6069c8cf8979)

Use Case Diagram<br>
The Use Case Diagram explains what actions the users can perform in the system. There are two main users: Member and Librarian. Members can borrow and return books, which are the basic actions they perform. Librarians have more responsibilities, like registering new members and adding new books to the collection. The diagram simply connects each user to the tasks they are involved in. It gives a clear picture of how the system is used on a day-to-day basis and who is responsible for what.

![image](https://github.com/user-attachments/assets/a253aaba-d2e5-4fd9-beeb-97a8d914a07c)

Medium Assignment: Online Shopping System

Class Diagram <br>
This diagram shows all the main pieces of our shopping system and how they fit together. We have classes like Customer, Product, Order, ShoppingCart, Payment, Shipment, and Admin, each with its own key details and actions. For example, a Customer “has” a ShoppingCart and can place multiple Orders; the Admin class handles updating product stocks. We also added an interface for payment processing to show that different payment methods can plug in easily. It’s a neat way to see the system’s structure at a glance.

![image](https://github.com/user-attachments/assets/0eab8fa9-6e47-4d3c-9075-1a3c343297e5)

Sequence Diagram <br>
The sequence diagram walks through exactly what happens when a customer places an order. It starts with the customer adding items to the cart, then the system checks inventory, processes payment, and finally confirms the order or reports a failure. By showing each step in order—along with the “alt” branches for things like payment declined or stock unavailable—it makes the dynamic flow obvious and shows all the back-and-forth messages between components.

![image](https://github.com/user-attachments/assets/f9fbb8a9-6495-4c99-8369-1b3de2da1496)

Activity Diagram <br> 
This flowchart-style diagram maps the end-to-end order fulfillment process. You begin by browsing and adding items to your cart, then decide to checkout. The system validates your cart and attempts payment; if it’s successful, inventory is reserved and shipment is generated before sending confirmation. If anything goes wrong (like payment failure), you get notified. It’s a simple, top-down view of how work moves through the system from start to finish.

![image](https://github.com/user-attachments/assets/889e11fc-ac6a-4577-ba19-99822152411d)




