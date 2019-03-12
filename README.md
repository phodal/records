# Tech Records

> A Technology's Records for Tech Lead to research


## Tech Debt Records

### Explain


### usecases


## Clean Architeture Usecases Records


### Example

Source: [https://fullstackmark.com/post/11/better-software-design-with-clean-architecture](https://fullstackmark.com/post/11/better-software-design-with-clean-architecture)

| Title | Register for courses |
|-------|----------------------|
| Description | Student accesses the system and views the courses currently available for him to register. Then he selects the courses and registers for them. |
| Primary Actor | Student |
| Preconditions | - Student is logged into system <br> - Student has not previously enrolled or registered <br> - Student cannot register within 5 days of course start date |
| Postconditions | Student is registered for courses |
| Main Success Scenario | 1.  Student selects "Register New Courses" from the menu. <br> 2.  System displays list of courses available for registering.  <br> 3.  Student selects one or more courses he wants to register for.  <br> 4.  Student clicks "Submit" button.  <br> 5.  System registers student for the selected courses and displays a confirmation message. |
| Extensions |  (2a) No courses are available for this student.  <br> 1.  System displays error message saying no courses are available, and provides the reason & how to rectify if possible.  <br> 2.  Student either backs out of this use case, or tries again after rectifying the cause.  <br> (5a) Some courses could not be registered.  <br> 1.  System displays message showing which courses were registered, and which courses were not registered along with a reason for each failure.  <br> (5b) None of the courses could be registered.  <br> 1.  System displays message saying none of the courses could be registered, along with a reason for each failure. | 
