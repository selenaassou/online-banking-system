# online-banking-system
Java Spring Boot Application. 
( Scalable and maintainable application : Design, Devope, Deploy ! TEST ? )

    NEXT PROJECTS: Book Managemnt, User Management (Maybe), REACT project (Because it's very common), Python Django because why not?
                    TRY Docker, Redis idk play with different technologies and USE THEM TO SEE HOW THEY REALLY WORK
                    ( Practice to solidify the Knowledge ! ) 

Building a Spring Boot Full Stack application \
TECHNOLOGIES:
* Spring Boot:
    Spring Boot 3 and Spring Security 6
* ReactJS
* MySQL
* Bootstrap
* Maven ( for Dependencies ! )



This project essentially contains 3 modules: Admin, Bank & Customer. 


STEP 1: Register, Sign up, Have an assigned account number. \

STEP 2: Implement the core banking services: Credits (pay) + Debits (deposit) accounts.
            + Transfer (One sending money: Debited, One getting the money: Credited) I THINK IT'S THE OPPOSITE ! ~JAVA ACADEMY update please. \
            
STEP 3: Balance + Name inquiries. \

STEP 4: Email service for creating alerts. (e.g: EMAIL: "You signed up for a new account !" and "This is your account." ME: only show the last
            and mask the rest) 
            You'll get alerts for transfers and credits, debits etc ... \
            
STEP 5: Spring ** SECURITY ** with JWT. -- Authentication and Authorization.
        -> Not every should be able to :
            -Delete a user
            -Show other users
        -> role-based authentication (or he meant road-based ? ?)  \
        
STEP 6: CHATGPT: Customer Care Agent (OH THE SIDE CHAT THING ! OMG THIS IS SO COOL! ) emulating/imitating a member of a bank talking to you. 


OBJECTS / METHODS: Builder Pattern, BTO?, Model Mapper?, 

As time goes by, we will be REFACTORING the code to maintain best coding practices.

AFTER this project, I am ready for the industry !

------------------------------------------------------------------------------------

Controller Layer --> Service Layer --> Repository Layer --> DataBase (DB) / MySQL. \
-3)-Repositor Layer:  Where Users Perfrom DB operations. \
-2)-Service Later: Business Logic. \
-1)-Controller Layer: Exposed to the clients. \

OK ... Let's start

start.spring.io \
    Project: Gradle-Groovy, Gradle-Kotlin, Maven \
    Spring Boot: not (SNAPSHOT) but ... the version (right before the last) : I selected 3.2.5 not 3.1.11 (not RC1=first version release: 3.3.0 ) \
                I'll keep the default. He selected the latest. 
                
    ADD DEPENDENCIES: Lombok (java lib to reduce boilerplate code like getters/setters), Spring Web (Tomcat Apache for RESTful Web)


