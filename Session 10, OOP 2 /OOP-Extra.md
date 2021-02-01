
# Y1 Yearlong 2020/21 - Project Practice

## Objective: 
During this mini-lab you will be practicing with basic instructions on parts of your personal project !




<img src="https://www.incimages.com/uploaded_files/image/1920x1080/getty_133970892_157811.jpg" width="400">





## Instructions:
> Before we start, make sure to create a new Repl.it and call it "Project Practice" as not to confuse it with your actual Project!

## Useful Terms:
> Before you start, take a look at the screenshot and familiarize yourself with these terms :

![meetOOP](https://user-images.githubusercontent.com/30011130/105876069-41359400-6007-11eb-92d9-f329160c28ff.png)

> initialization `__init__` is always the first function of a class.             
> attributes are considred parameters.                                 
> Note that you might not use all these terms, but this is the collection for future references. 


### Part 1:
This is going to be a practice on how to write a class in your project with inheritance. 
1. Create a class called `Person`: 
	- Add 2 attributes to the class: `name` and `age`. (Don't forget `self`, as it is always your first and default attribute)
	- Receive both the `name` and `age` as a parameter to the `__init__` function and set them accordingly. 
  - Create a function that returns the name of this person. you may call it `identity` for example.

  
2. Create another class called `Visitor` that inherits from `Person`:
  - Add 1 attribute to the class: `money`. (Don't forget `self`, as it is always your first and default attribute)
  - Receive the attributes of the inherited class `Person`. (refer to line 13 in the picture above)
	- Receive `money` as a parameter to the `__init__` function and set it accordingly. 
  - Create a function called `Enter` that *prints* either True or False depending on these rules:
    * If the age is under 10 then the ticket costs 5 shekels.
    * if the age is 10 or more then the tickets costs 10 shekels. 
    * with these rules and the amount of money the visitor has, they may enter (True) or may not (False).
> this goes without saying, but if the visitor has more money than the ticket cost then they can enter.                           
> you might have noticed that we did not define identity here but we can use it; 
> this is a bit advanced so the code is provided :       
"""  print (True, Person.identity(self))  """

**you can check if your code works by creating an instance of a visitor with a name, age and money to see if they can enter or not.**

check my solution: https://repl.it/@mousa19meet/MicroPlainWebpages#main.py

## Part 2 : 
This is going to be a practice on how to deal with a while loop that will always keep your program running and waiting for inputs from the user.


* Let's put this in practice with a guessing the number game. 

1 - First, let's assign `input` to a variable so we have a number to guess.

2 - then let's have our boolean variable that will be responsible for running our code. 

3 - here we start our while loop with the variable, so for example : `while Running:` (Running is the name of our boolean variable)

4- we ask again for an input, but this time it's the guess/ answer. 

- if the guess is lower than our initial number : print guess higher 
- if the guess is higher than our initial number : print guess lower 
- else then the guss must be correct so we reverse our boolean variable and print out a congratulations message. 

check my solution : https://repl.it/@mousa19meet/ColorlessDearestRuntime#main.py


**Good Job! IF you are still confused, please contact part of the CS team.**

##### WELL DONE ON FINISHING THIS PRACTICE!

 

<img src="https://agiftidea.com/wp-content/uploads/2020/04/birthday-celebration.jpeg" width="350">

