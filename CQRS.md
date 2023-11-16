#CQRS (Command Query Responsiblity Segregation)  DESIGN PATTERN
References: https://www.youtube.com/watch?v=vdi-p9StmG0
https://www.linkedin.com/learning/advanced-azure-microservices-with-dot-net-for-developers/top-tactics-to-build-advanced-dot-net-microservices?u=89213594
https://www.youtube.com/watch?v=3AKqtggkaIA --- clean video


Command Model (Write side):

Responsible for handling commands that change the state of the system.
Often involves creating, updating, or deleting data.
Optimized for writes and may use a different data model than the read model.


Query Model (Read side):

Handles queries and is optimized for reading data.
Represents a different perspective on the data and might be denormalized for performance reasons.


PROS: When dealing with large applications CQRS / using microservices is good because of how you can scale it 

Split writing from the database and Reading from the database



