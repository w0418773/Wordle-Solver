<img width="416" height="382" align=center alt="Screenshot 2025-08-07 135501" src="https://github.com/user-attachments/assets/30c45349-38c8-40aa-abe3-61ee1c24627e"/>
<br/>
🧠 Wordle Solver
<br/>
During the height of the Wordle craze, I wanted to create a tool that could help solve the daily puzzle more strategically and efficiently. This project is a Wordle-solving assistant that suggests optimal guesses based on your feedback after each attempt.

The program works by maintaining a list of valid five-letter English words and narrowing down the possibilities based on how you mark each letter in your guess:

<img width="16" height="16" alt="btn_Correct" src="https://github.com/user-attachments/assets/5b2ba9be-d05f-4aa1-9b67-a138b0e4a59f" />
Correct letter in the correct position
<br/><br/>
<img width="16" height="16" alt="btn_WrongPlace" src="https://github.com/user-attachments/assets/2e462115-eb07-4e2b-b277-267211a047d5" />
Correct letter in the wrong position
<br/><br/>
<img width="16" height="16" alt="btn_Incorrect" src="https://github.com/user-attachments/assets/bfc62b83-8d94-4fd7-ac9e-19bb65befff1" />
Incorrect letter not in the word
<br/><br/>

After each guess, you simply tell the program how each letter performed (similar to the game's yellow, green, and gray tiles), and it updates its internal list of possible solutions. With each round of feedback, the program becomes more accurate, filtering out invalid words and refining its recommendations until the solution is found.


