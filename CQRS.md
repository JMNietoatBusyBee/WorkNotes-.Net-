#CQRS (Command Query Responsiblity Segregation)  DESIGN PATTERN
References: https://www.youtube.com/watch?v=vdi-p9StmG0
https://www.linkedin.com/learning/advanced-azure-microservices-with-dot-net-for-developers/top-tactics-to-build-advanced-dot-net-microservices?u=89213594
https://www.youtube.com/watch?v=3AKqtggkaIA --- clean video
https://www.youtube.com/watch?v=W_EEKAN9IVU -- starting videos from CQRS pattern with Microservices 


Command Model (Write side):

Responsible for handling commands that change the state of the system.
Often involves creating, updating, or deleting data.
Optimized for writes and may use a different data model than the read model.


Query Model (Read side):

Handles queries and is optimized for reading data.
Represents a different perspective on the data and might be denormalized for performance reasons.


PROS: When dealing with large applications CQRS / using microservices is good because of how you can scale it 

Split writing from the database and Reading from the database



UPDATING YOUR .NET VERSION OF PROJECTS --
Reference: [https://www.code4nord.com/why-and-how-to-update-microsoft-net-framework-to-the-latest-version/](https://devblogs.microsoft.com/dotnet/upgrade-assistant-now-in-visual-studio/#:~:text=Now%20you%20can%20upgrade%20any,Core%20web%2D%20and%20desktop%20apps.)



ENTITY FRAMEWORK supports .net8.0 now  Updated on 11/15/2023
https://devblogs.microsoft.com/dotnet/announcing-ef8/ -- Read more about this line 
![image](https://github.com/JMNietoatBusyBee/WorkNotes-.Net-/assets/151013941/96ba9936-2f78-44fa-88fb-af259f69ea9c)




Adding Class Library 

![image](https://github.com/JMNietoatBusyBee/WorkNotes-.Net-/assets/151013941/28003446-33f9-4f8c-a614-a8275acbd1c1)





Oracle Express 11g 
Documentation: https://docs.oracle.com/cd/E17781_01/admin.112/e18585/toc.htm#XEGSG110



