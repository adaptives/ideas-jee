**What have we made this project ?**

Even before explaining what this project does, I feel it is important to explain the context, so you can view it in the right light. 

The purpose of this project is to create a reference implementation for a JEE project made using Servlets, JSP, and EJB. The project also has unit tests, so users can understand how to unit test EJB's and Servlets. 

Since a toy reference implementation is no fun, and since a large implementation is difficult to understand, we created something in between the two. This is a small production quality application made using Servlets, JSP< EJB and with unit and functional tests.

** What does this project do ? **

Many of us get a lot of ideas which we do not have the time to implement. This project helps a group share there ideas on the Internet. Along with sharing ideas the application also allows users to solicit prototype requests for these ideas.

The application supports multiple users with a profile that indicates whether they are admin users. All users who have an account can add their idea to the system. They can also edit and delete their idea. Admin's have all the permissions of regular users, along with the permission to edit/delete other user's ideas.

Each user can specify their email and whether they want to solicit prototype requests for their idea.

**Technology stack **

 - JDK 1.7
 - Servlet
 - JSP
 - JUnit 4.x
 - OpenEJB for testing EJB's in an in-memory container
 - EasyMock for mocking objects
 - Selenium for creating functional tests
 
 