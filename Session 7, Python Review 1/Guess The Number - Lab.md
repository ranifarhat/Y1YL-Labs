# Y1 Yearlong 2020/21 - Guess the Number (Mini project)

## Objective:
During this lab: 
- You will be using Python as a programming language, the lab should help you review python from the Y1 summer, especially variables and conditionals.
- You will be more familiarized with **Loops & Dictionaries!**
- You will be creating a fun game called **Guess The Number** using all the material that you have learned!






[![](https://68.media.tumblr.com/74326aa495e4fbc74fbb2ada3cbdc347/tumblr_ol9f1rNceq1vd602xo1_500.gif)]()




## Instructions:
In this part you will create a game called **Guess The Number**-  
**Game Instructions:**
- The program assigns a random number that the player needs to guess.
- Each turn the player can make a guess.
- If the guess is wrong, the program should tell the player if it's higher or lower.
- When the player guesses the number he/she wins.

**In order to build this game, follow the following steps:**

## **Step 1**: 
### Assigning a Random Number!

> Before we start, make sure to create a new Repl.it and call it "Guess The Number Mini Project"!

1. In `main.py`, **Print** the game **instructions** to the player.
2. Create a variable called **random_num** which will be equal to the secret number that the player needs to guess.
3. Use the **random number generator** to set a **random value** to the variable **random_num**. (**Hint:** check out this [link](https://www.tutorialspoint.com/generating-random-number-list-in-python))

***Good Job you finished Part 1! Before moving to Part 2 make sure to run your code to check that everything works properly!***

## **Step 2**: 
### Take the player Guesses!
1. Ask the user to make a guess in the terminal using python `input()` - 
    - *Reminder*: `x = input("Guess the number: ")`

2. Save this value inside another variable called **player_guess**.
3. And now how do we handle the player input ? Let’s move to part 3 to figure it out!

## **Step 3**: 
### Handle the user input!
1. Check if the **player_guess** is equal to the **random_num** using **if statement**:
  - If the two numbers are **equal** then print the following message to the player: "Congratulations you won! The secret number is …"
  - If the player_guess is **greater** than the `random_num` print the following message to the player: "Too high"
  - If the player_guess is **smaller** than `random_num`, print the following message to the player: "Too low"
2.Using **while** loops, Keep asking the player to make more guesses until his guess is correct and then he wins!

***Amazing job! You finished Step 3! Don’t forget to run your code and try to play your awesome game with one of your TAs or Instructors!***

## **Step 4**: 
### Let’s Make our game more FUN!
1. Probably the Player found the game too easy or too hard so let’s make the player choose the **difficulty level**!
    - Before starting the game, Ask the player to choose a difficulty level between: Hard, Medium, & Easy.
    - According to the difficulty level that the user chose, change the **range** of the `random_num`(**e.g.** if the user chose Easy then make the `random_num` range from 0 to 10 but if he chose medium make it from 0 to 20 and so on…)

***Brilliant! You finished Step 4! Don’t forget to show your great work to one of your TAs or Instructors and check out the bonus part!!***

## Bonus:
* These bonuses are not in a specific order, you can start with any one you like - and you can go above and beyond in adding more to it!   

1. Limit the **number of guesses** that the player can make!
    - For example: each player will have 3 guesses only or game over.
2. Print the **game storage** as a **dictionary** by assigning:
    - **Key** - the number of the guess
    - **Value** - the value of the guess  
**For example**: if the user guessed 2 times, the first guess was 13 and the second one was 44, your dictionary should look like this: `game_storage={1:13,2:44}`  
3. **Add another player** to the game and the player who guesses the number first wins.
4. Get Creative and **design** your terminal using **colorama** :D Use the following [link](https://pypi.org/project/colorama/) to install colorama and see different examples, you can ...
    - Print text in different colors in the terminal.
    - Add background colors to the text 
    - Get creative and do your own design and feature.

**Good luck & Do your best!  
Remember to show your brilliant work to your partners and instructors so we can learn from each other.**   
![](https://www.dogwonder.co.uk/wp-content/uploads/2009/12/tumblr_ku2pvuJkJG1qz9qooo1_r1_400.gif)
