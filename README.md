# Intro-to-AI
How to run our program ?


Our program is written in Python3.
To run our program, first you need to install Python compiler to your computer.
We used some libraries such as random, math, copy,..... However these libraries can be used without downloading.


First, you need to go to file game_better.py and run this python file. 


![image](https://user-images.githubusercontent.com/112222605/210299547-d9c63119-acf6-485a-a59c-fa9ee02bbb20.png)
Choose yes if you want to compulsorily capture if the chosen piece can eat in the next move.


At the next stage, you should enter the figure coordinate without space to choose your move.
![image](https://user-images.githubusercontent.com/112222605/210331304-d362a05c-0dbc-43c3-9d15-36bfcea27894.png)
For example, if I choose my first piece is piece at coordinate 50, then it will display valid move at 41 like this: 
![image](https://user-images.githubusercontent.com/112222605/210331459-026caa1f-197c-4c72-9424-60ea85bf7218.png)
After your turn will be AI turn: ( COM played a move displayed on the table above) 
![image](https://user-images.githubusercontent.com/112222605/210332880-05b6683e-b8d2-4d30-8b3d-b69e8eb1fe30.png)
If you accidentally enter invalid position, it will prompt you to enter again.
The AI will choose his own choice and the board will automatically update. Sometimes the board can be updated very fast, however you always can check the activity of the game by scrolling up the terminal window.


Now it's your game with COM player. The game will end if it satisfies ending condition.
Otherwise, if you want to exit the game,  x to exit: 
![image](https://user-images.githubusercontent.com/112222605/210334540-0ec15327-97c3-4b3c-ab65-018707144ef4.png)

Besides, you also can change the difficulty of the game by changing the initial depth of alpha beta function. By increasing depth, the alpha beta function will explore in a wider range, hence the COM player will take a better move.





