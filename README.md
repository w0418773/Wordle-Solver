<img width="416" height="382" alt="Screenshot 2025-08-07 135501" src="https://github.com/user-attachments/assets/30c45349-38c8-40aa-abe3-61ee1c24627e" 
  style="display: block;
  margin-left: auto;
  margin-right: auto;"/>
<br/>
🧠 Wordle Solver
During the height of the Wordle craze, I wanted to create a tool that could help solve the daily puzzle more strategically and efficiently. This project is a Wordle-solving assistant that suggests optimal guesses based on your feedback after each attempt.

The program works by maintaining a list of valid five-letter English words and narrowing down the possibilities based on how you mark each letter in your guess:

<img width="32" height="32" alt="btn_Correct" src="https://github.com/user-attachments/assets/5b2ba9be-d05f-4aa1-9b67-a138b0e4a59f" />
 Correct letter in the correct position

🔁 Correct letter in the wrong position

❌ Incorrect letter not in the word

After each guess, you simply tell the program how each letter performed (similar to the game's yellow, green, and gray tiles), and it updates its internal list of possible solutions. With each round of feedback, the program becomes more accurate, filtering out invalid words and refining its recommendations until the solution is found.
