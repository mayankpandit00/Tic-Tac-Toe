# TicTacToe
A simple game of tic-tac-toe to enjoy with your friends !

### Requirements :
Any C++ compiler or IDE (vscode/xcode/online).

### Introduction : 
Tic-tac-toe, noughts and crosses, or Xs and Os, is a paper-and-pencil game for two players, X and O, who take turns marking the spaces in a 3×3 grid. The player who succeeds in placing three of their marks in a diagonal, horizontal, or vertical row is the winner.

### Setup :
1. Download any C++ compiler or use online compilers :
   1. https://visualstudio.microsoft.com/vs/features/cplusplus/ (Download)
   2. https://developer.apple.com/xcode/ (Download)
   3. https://www.jdoodle.com/online-compiler-c++/ (Online)
   4. https://www.tutorialspoint.com/compile_cpp11_online.php (Online)

2. Download repository :
   1. On GitHub, navigate to the main page of the repository.
   2. Under the repository name, click Clone or download.
   3. In the Clone with HTTPs section, click to copy the clone URL for the repository.
   4. Open Git Bash.
   5. Change the current working directory to the location where you want the cloned directory to be made.
   6. Alternatively, you can download its .zip file and store it to your desired location on the system.

### How to play ?
1. Run the code and choose the **"1. Play Game."** option from the menu and enjoy!
2. You can also select **"2. View scoreboard."** to know the points of each player or **"3. Exit"** to exit the code.

### Working :
1. Asks the users to choose an option from the menu. Notifies if an invalid option is choosed.
2. If **"1. Play Game."** is selected, a 3x3 board with numbers 1-9 will be displayed. The users can choose their desired spot by entering its respective number. The game will continue till any one of the user wins or the match gets tied or they try to choose a spot that is already taken. Between each turn, the program will check if any player has won or not. If yes, the users will be notified with a message on the screen. After any round has ended, the users will be asked if they wish to continue or quit.
3. If **"2. View scoreboard."** is selected, points of both the users will be displayed on the screen. Points reset to default when the program is restarted, else it will continue to calcuate the points of each user. 
4. If **"3. Exit."** is selected, the program will quit with a thank you message.
5. If any other option is selected, the program will notify it to the users and re-run. 
