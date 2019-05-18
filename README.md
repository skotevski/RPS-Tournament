# RPS-Tournament Rapid Prototype


## How to use the Application
*Note This only works on one machine, because all clients are connecting to the same IP address (localhost)*
- First run Server.java
- Once you have your server running, you are going to have to run an instance of Client
- Then run another instance of Client
- You will get a message on both instances of Client, prompting you to enter a choice of either R, P, or S to play.
- After the game ends, both Clients are disconnected, and will provide an output of the winner. 
- The Server will then output that it is looking for new players.

## Sample Outputs
### Winning Game
**Server Output**

<img src="https://i.gyazo.com/a46db937350aa883368c97fa531b5ae7.png" width="60%">


**Player 1 Output**

<img src="https://i.gyazo.com/688e5333dea5553cddca410b465f1a95.png" width="60%">


**Player 2 Output**

<img src="https://i.gyazo.com/bd98700317973132ef23699e597a9651.png" width="60%">




### Tied Game
**Server Output**

<img src="https://i.gyazo.com/1daf8208277af9f1942a7be30d69e704.png" width="60%">


**Player 1 Output**

<img src="https://i.gyazo.com/00d77b135705c4136fdf1a30b5146d87.png" width="60%">


**Player 2 Output**

<img src="https://i.gyazo.com/3b2588e4ec882cc21e8018727869ec56.png" width="60%">




### Invalid Input
**Server Output**

<img src="https://i.gyazo.com/c7a0437d71f49c75645cb7bd9bc21e18.png" width="60%">


**Player 1 Output**

<img src="https://i.gyazo.com/3931be296d8e2349a91b7c175bd956f7.png" width="60%">

Once the server saves a Player's choice, it cannot be changed. Even if you try to enter valid values like **P** or **S** after entering R, you are unable to change it, and the Server will determine the winner with the first valid input. 

**Player 2 Output**

<img src="https://i.gyazo.com/231104ed4806fd75d5d2065113fd0053.png" width="60%">











