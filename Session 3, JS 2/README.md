# Javascript II - DOM Lab

## Objective: 
During this lab, you will be creating a page about yourself using Document Object Model! You will be using only Javascript for this lab.

Some useful links to learn more about DOM:
W3 Schools: https://www.w3schools.com/js/js_htmldom.asp 
Presentation: https://tinyurl.com/wgwaupt 






<img src="https://i.ytimg.com/vi/1IsL6g2ixak/maxresdefault.jpg" width="400">





## Instructions:
Copy and paste the code at the end into a new HTML file. Write code ONLY in the update() function. Do NOT edit any of the HTML.
The update() function will be called when the button is clicked.
Inside the function:
1. Update the text in “name” element to your name.
2. Update the text in “age” element to your age.
3. Update the text in “favorite_food” element to your food.
4. Update the “favorite_site” element to be your favorite website. Make sure to edit both the attribute AND the text.
(Make sure to include the https:// in the link)
5. Make a new `<p>` element with id “favorite_word”. Make the text in the element your favorite word. Add the element to the body of the HTML.
6. Make a new `<p>` element with id “favorite_drink” to replace element with id “favorite_food”.
7. Change the text color of all `<p>` tags into your favorite color.


## Bonus:
Create a button to change the “name”, “age”, “food”, “favorite_site”, “favorite_word”, and your newly added element to switch between your information and two other MEET students’ information.


## HTML Code to be copied:

<!DOCTYPE html>
<html>
<head>
	<title>DOM Lab</title>

	<script type="text/javascript">
		function update() {
			// YOUR JS CODE HERE

		}

	</script>
	
</head>
<!---------- DO NOT EDIT THE HTML BELOW --------->
<body>

	<h2 id="name">My name</h2>
	<p id="age">My age</p>
	<p id="favorite_food">My favorite food</p>
	<a id="favorite_site" href="https://www.google.com">google.com</a>

	<br>
	<button onclick="update()">Update my information</button>
</body>
</html>



##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 




<img src="https://www.c-sharpcorner.com/UploadFile/201fc1/programming-in-java-using-the-mvc-architecture/Images/mvc%20framework.jpg" width="350">
