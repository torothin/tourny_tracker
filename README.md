# tourny_tracker
creating a tournament tracker in c#
freeCodeCamp.org

Requirements
1.  Tracks games played and their outcomes (who won)
2.  Multiple competitors play in the tournament
3.  Creates a tournament plan (who plays in what order)
4.  Schedules games
5.  Single loss eliminates player
6.  The last player standing is the winner

Questions
1.  How many players will the tournament handle? is it variable?
    -Should be able to handle variable number of players
2.  If a tournament has less than full compliment of players, how do we handle it?
    -Less than perfect numbers then have byes
3.  Should the ordering of the who plays who be random or ordered by input
    -Random
4.  Should we schedule the game or are they just played whenever?
    -The games should be played in whatever order and whenver the players want to play them
5.  If scheduled, how does the system know when to schedule games for?
    -They are not scheduled
6.  If the games are played whenever, can a game from the second round be played before the first round is complete
    -Fully complete rounds before next nround
7.  Does the system need to store a score of some kind or just who won?
    -Storing a simple score would be nice (just a number for each player)
8.  What type of front-end should this system have (form, webpage, app, etc.)
    -Desktop system to start and maybe a webapp down the road
9.  Where is the data stored?
    -Microsoft SQL database, option for txt file
10.  Will this system handle entry fees, prizes, or other payouts?
    -Yes, entry fee, prizes, total cash should not exceed tournament income, percentage based system.
11.  What type of reporting is needed?
    -Report specifying the outcome of the games per round, specifics on who won and how much they won.  In a form or emailed to the tourn comp and admin
12.  who can fill in the results of the game?
    -Anyone using the app should be able to fill in game scores
13.  Are there varying levels of access?
    -No, comp should not have access to tourn
14.  Should this system contact users about upcoming games?
    -Yes, email users
15.  Is each player on their own or can teams use this tournament tracker?
    -Be able to add members, all members are treated equal, teams can name their team
    
Big Picture Design
  Structure: Windows Forms application and Class Library
  Data: SQL and/or Text file
  Users: One at a time on one application
  
