# GuardiansDanceOff-UW330B
Final Project for UW JSCRIPT 330 B

## Preamble
My proposal is to take last quarters project and update it to Mongodb from google firestore and add features such as authentication and authorization.

## Project Proposal
### 1. Descripton
- The project is to create a tournament draw using the Guardians of the Galaxy theme and characters.

### 2. Problem to solve
- The project seeks to allow people to create a simple tournament draw on the web for their own purposes.

### 3. Technical components
- The data model will be converted from a firestore database to a mongodb database.
- The existing functionality and routes will be ported to the new Final Project which upload data, and update the database as a player wins or loses a match.
- Features to be added:
    A 'Tournament Director' will have all priveleges to load data and update matches. 
    The 'Tournament Director' will also have the ability to add 'Referee' and 'Player' users.
    'Referee's will have the ability to advance matches, while 'Player's will only have query capability
    A 'Tournament Director' will have the privelege to delete a tournament, no others will have this privilege.
- Rudimentary visual additions will be for login and others as time permits.

### 4. Timeline tasks include:
week1
- designing the mongo db schema 
- converting the existing firestore data structures to mongo db structures (important to get this right)
- creating the load data utilites
week2
- re-writing all existing routes and dao to work with the new data structure in mongodb (biggest task)
- adding login screen
week3
- testing
- adding delete functionality on screen and routes/dao
- create test cases
- create test scripts
week4
- create postman collection as needed




