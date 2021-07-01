
BACK END:
FLASK framework: K Team (Katrina K and Kate M)

                                                                        (WAVE 1)
- Create database       (TEAMWORK K&M)

- Creating models
    Board Model
        Attributes: 
            board_id (int) The unique board id number
            title (string)
            owner (string)
            ** ??? cards (list) The list of cards on that board ?? **

    Card Model
        Attributes:
            card_id (int) The unique card id number
            message (string)
            likes_count (int)
            board_id (int) foreign key to board_id in board

- Creating a one-to-many relationship between two models



                                                                        (WAVE 2)
- Creating conventional RESTful CRUD routes for a model
    - GET /boards
    - POST /boards
    - PUT /boards/<board_id>
    - GET /boards/<board_id>
    - DELETE /boards/<board_id>

    - POST /boards/<board_id>/cards
    - DELETE /boards/<board_id>/cards/<card_id>
    - PUT boards/<board_id>/cards/<card_id>

    Backend User Stories:
    -  User can create a new board with a name (POST)
    -  User can view single board and it's contents (GET)
    -  User can rename a single board (PUT)
    -  User can see all the current boards (GET)
    -  User can delete board (DELETE)
  
    -  User can add a card to a board (POST)
    -  User can delete a card (DELETE)
    -  User can update (like/message/etc) a card (PUT)



- Create unconventional routes for custom behavior

- Apply knowledge about environment variables




FRONT END:
REACT JS library: A Team (Andre P and Allison L) 

- Sending data to nested components through `props`

    App.js
    Board.js -- *props: board, onBoardSelect 
    NewBoardForm.js -- *props: createNewBoard *state: title, owner *functions  
    CardList.js
    NewCardForm.js
    Card.js

- Receiving and using `props` within a component

- Initializing and using state within a component

- Passing callback functions to child components and use them to update state




**If you work on a task/feature - mark it with your last initial, and PUSH :)**

WAVE 1: Layout Components (FRONT END)   &&    Set Up DataBases and Models (BACK END)


WAVE 2: Add Events/Handlers (FRONT END)    &&    CRUD (BACK END) 


WAVE 3: Debug    &&    Deploy    (Altogether)



Great Question:

?? WORKFLOW:

by 9:59am** 
    What are you working on?
    What is complete?
    Where are you stuck?
    Feedback  - provide actionable/communicative feedback <3 YES show that you understand in your feedback
    
10am check-in
    Plan a merge time together --> 
    I AM THE WALRUS




7pm check-out
    What are you working on?
    What is complete?
    Where are you stuck?
    Feedback


How do we Push to github? 
    *if it's pair programmed - push to main together and merge
    *if dev independently - push to branch and get approval before merge
