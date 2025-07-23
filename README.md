# Cricket Game
This is my updated README with latest info.

# A "Bat Ball Stump" Cricket Game using JavaScript and HTML, where:
-> A user clicks a button (Bat, Ball, or Stump)
-> The computer randomly chooses one
-> The result is shown with an alert

# Bat Ball Stump Game (Cricket Mini Game)
This is a fun web-based Cricket game built using simple HTML and JavaScript.
You play by choosing either Bat, Ball, or Stump — and the computer makes a random choice. Based on both choices, the game decides who wins!

# How It Works
When you click one of the buttons:
A random number is generated using Math.random() * 3
Based on the number, the computer randomly chooses Bat, Ball, or Stump
Your choice is compared with the computer's
The result is displayed using a JavaScript alert

# Game Rules
Each option can beat or tie based on the following logic (from your current code):

User Choice         Computer Choice	               Result
   Bat	                 Ball	                     You win
   Bat	                 Bat                    	It's a tie
   Bat	                Stump	                     You lose
   Ball	                 Bat	                   Computer wins
   Ball                  Ball                     It's a tie
   Ball	                Stump	                     You win
   Stump	               Bat                  	   You win
   Stump	               Ball	                   Computer wins
   Stump	              Stump	                     It's a tie

# Files Used
index.html — main HTML file with all the JavaScript inside <button onclick="...">
No external CSS or JS files used.





>>>>>>> c423383 (Updated)
