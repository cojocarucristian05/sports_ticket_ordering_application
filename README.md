# sports_ticket_ordering_application

**UML Diagram**

Commands:

    [Customer]-(Show Events)
    
    [Customer]-(Buy Tickets)
    
    [Customer]-(Show Order History)
    
    (Show Order History)>(Log In Customer)
    
    (Show Events)>(Log In Customer)
    
    (Buy Tickets)>(Log In Customer)
    
    [Organizer]-(Manage Events)
    
    [Organizer]-(Create Events)
    
    (Manage Events)>(Log In Organizer)
    
    (Create Events)>(Log In Organizer)
    
    (Log In Customer)<(Register)
    
    (Log In Organizer)<(Register)

![image](https://user-images.githubusercontent.com/93082736/235707622-e3193d5e-3ddb-4833-85f1-e057795b5758.png)
