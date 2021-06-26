# Roles and Cards {#game-roles .breakbefore}

Each role has different rules for drawing and playing cards.

## The Fronters

If you're one of the Fronters, you draw your cards from the *System's Deck*. You can
play a given card on a Status Stack only if the card ***matches***
either the suit or rank of the top card on that stack.

You play one card per turn, when your turn comes up in the turn order. 
In games with more than three players, at least two players will share the System 
role, and you alternate turns.

For example, if the Status Stacks look like this ...

::::::: cardstacks :::::::::
[Ten of Diamonds]{.card .d .ten}
[Three of Diamonds]{.card .d .three}
[Jack of Spades]{.card .s .jack}
::::::::::::::::::::::::::::

... and you have these cards in your hand...

:::::: cardhand :::::::::
[Ten of Clubs]{.card .c .ten}
[Three of Hearts]{.card .h .three}
[Four of Clubs]{.card .c .four}
[Five of Spades]{.card .s .five}
[Jack of Diamonds]{.card .d .jack}
:::::::::::::::::::::::::

...you could play your cards on these stacks:
[You can't play the <span class="card c five"></span> at all, since it doesn't
match either the suit or the rank of a stack.]{.dera}

:::::::::::::::: cardmatrix :::::::::::::::::::::::::::::::::::::::::::::::::

                                    [Ten of Diamonds]{.card .d .ten} [Three of Diamonds]{.card .d .three} [Jack of Spades]{.card .s .jack}
---                                 ---                              ---                                  ----
[Ten of Clubs]{.card .c .ten}       **yes** (rank matches)           *no*                                 *no*   
[Three of Hearts]{.card .h .three}  *no*                             **yes** (rank matches)               *no*   
[Four of Clubs]{.card .c .four}     *no*                             *no*                                 *no*   
[Five of Spades]{.card .s .five}    *no*                             *no*                                 **yes** (suit matches)
[Jack of Diamonds]{.card .d .jack}  **yes** (suit matches)           **yes** (suit matches)               **yes** (rank matches)

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## The Date {.breakbefore}

If you're the Date, you draw your cards from the *Date's Deck*. You can
play a given card on a Status Stack only if the card ***does not***
match the suit or rank of the top card on that stack. This is the opposite
of the rules for the Fronter role.

You play one card per turn, when your turn comes up in the turn order. 
In games with more than three players, you will be taking turns more
frequently than the players in the System role.

For example, if the Status Stacks look like this ...

::::::: cardstacks :::::::::
[Ten of Diamonds]{.card .d .ten}
[Three of Diamonds]{.card .d .three}
[Jack of Spades]{.card .s .jack}
::::::::::::::::::::::::::::

... and you have these cards in your hand...

:::::: cardhand :::::::::
[Ten of Clubs]{.card .c .ten}
[Three of Hearts]{.card .h .three}
[Four of Clubs]{.card .c .four}
[Five of Spades]{.card .s .five}
[Jack of Diamonds]{.card .d .jack}
:::::::::::::::::::::::::

...you could play your cards on these stacks:
[You can't play the <span class="card d jack"></span> at all, because it
matches either the suit or the rank of the card on each stack.]{.dera}

:::::::::::::::: cardmatrix :::::::::::::::::::::::::::::::::::::::::::::::::

                                    [Ten of Diamonds]{.card .d .ten} [Three of Diamonds]{.card .d .three} [Jack of Spades]{.card .s .jack}
---                                 ---                              ---                                  ----
[Ten of Clubs]{.card .c .ten}       *no* (rank matches)              **yes**                              **yes**
[Three of Hearts]{.card .h .three}  **yes**                          *no* (rank matches)                  **yes**
[Four of Clubs]{.card .c .four}     **yes**                          **yes**                              **yes**
[Five of Spades]{.card .s .five}    **yes**                          **yes**                              *no* (suit matches)
[Jack of Diamonds]{.card .d .jack}  *no* (suit matches)              *no* (suit matches)                  *no* (rank matches)

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

## The Outside Interference {.breakbefore}

If you're the Outside Interference, you draw your cards from the *Date's Deck*. 
You can play a given card on a Status Stack only if the card's 
***rank matches the last card played***.

You can play a card **immediately after any other player** plays a card to a stack.
When you do, instead of providing dialog for a character, you introduce a 
complication into the scenario determined by the card you played.

For example, if the Status Stacks look like this, with the last-played card shown
in red ...

::::::: cardstacks :::::::::
[Ten of Diamonds]{.card .d .ten .gray}
[Three of Diamonds]{.card .d .three}
[Jack of Spades]{.card .s .jack .gray}
::::::::::::::::::::::::::::

... and you have these cards in your hand...

:::::: cardhand :::::::::
[Ten of Clubs]{.card .c .ten}
[Three of Hearts]{.card .h .three}
[Four of Clubs]{.card .c .four}
[Five of Spades]{.card .s .five}
[Jack of Diamonds]{.card .d .jack}
:::::::::::::::::::::::::

...you could play your cards on these stacks:
[It's entirely likely that you can't play a card every time you potentially could -- 
that's by design.  The Outside Interference has more opportunities to play cards 
than the other roles.]{.dera}

:::::::::::::::: cardmatrix :::::::::::::::::::::::::::::::::::::::::::::::::

                                    [Ten of Diamonds]{.card .d .ten} [Three of Diamonds]{.card .d .three} [Jack of Spades]{.card .s .jack}
---                                 ---                              ---                                  ----
[Ten of Clubs]{.card .c .ten}       *no*                             *no*                                 *no*   
[Three of Hearts]{.card .h .three}  *no*                             **yes** (rank matches)               *no*   
[Four of Clubs]{.card .c .four}     *no*                             *no*                                 *no*   
[Five of Spades]{.card .s .five}    *no*                             *no*                                 *no*                  
[Jack of Diamonds]{.card .d .jack}  *no*                             *no*                                 *no*                  

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

