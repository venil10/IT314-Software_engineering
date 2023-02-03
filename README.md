# IT314-Software_engineering

#### Name       : Gondaliya Venil Chandubhai
#### StudentID  : 202001446
#### Date       : 10-02-2003
----

### Objective:
    Identifying Functional and Non-Functional Requirements
----
## 1. Identify FRs and NFRs
### Functional Requirements
    1. Student and Employee Login (User Login)
        - varification mail will be sent when they register first time
        - Borrowing a book and Returning a book
        - Extend return date if no other booking request are made for that particular book
        - show return date of a book if it is already borrowed by someone else
        - Add user to waitinglist for the book if not avalabale.
        - Borrowing or returning a book require user to login
    
    2. Library Staff Login (Staff Login)
        - Get the list of books that are currently on available in the library
        - View pending borrow requests of the books that need to be finished
        - View the list of pending return requests 
        - Locating a book location on shelf at the platform
        - View the waiting list of the book.
        
    3. Librarian Login (Admin Login)
        - Create a new record book that are available for borrowing
        - Mark the record of the book that is borrowed
   
    4. system work in  concurrent booking.
    
    5. security and privacy of the system and user
    
    6. Borrowing of the book are restricted to users only.
    
    7. New book recommendation that can be available in LIS
    
    8. Non-Members is able to freely browse the books.
    
    9. Reminder for the returning of the book to user when date is nearby.
    
    ### Non-Functional Requirements
    
    1. Authentication - While loging to LIS user must be authorizeed and validated
    
    2. Scalability - The system should be compatable with large login
    
    3. Reliability
        - Database must be updated when there are borrowing or returning of book.
        
    4. Maintainability 
        - System and web should be up to date and maintained after closing of system
    
    5. Compatibility - system should work in every system.
    
    6. Accuracy - accuracy in all the information that are stored.
    
    7. Privacy - Credentials of the user should be private.
    
----
## 2. Identify scope, features and non-functional aspects of the following problem.

### 1. Scope
    - The application's target audience will be the 5% of the world's population who are suffering from hearing loss. 
    - Artificial intelligence software which recognises basic key sound and give immediate alert via vibration to user.
    - Application must have low latency that can be used for real time application.
    
### 2. Features
    - Artificial intelligence to recognise basic key sounds.
    - Low latency to enable real-time use.
    - Alerts to user about the incoming sounds via vibration.
    - The sounds recorded must also be logged properly in readable format
    - When a critical emergency is recognised and there is no reaction from the user, notify friends and family.
    - Background running of application.
    - Less Power use and law latency.

### 3. Non-Functional aspects
    - The App should alert the user through some vibrations.
    - When travelling, the app should be able to recommend the lanes with the least amount of traffic.
    - App should be able to send their live location to friends and relatives in case of an emergency via the app.
    - Compatible in every OS.
