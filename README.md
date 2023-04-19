# assignment-1
//Abdulrahamn Alaidaros
//1826053

 I created a MyApp widget that sets the title and theme of the app and sets the home page to the ProfilePage widget. The ProfilePage widget is a stateful widget that creates a form for the user to enter their name and age and to select a profile picture. I also added a button to submit the form and display the entered information on the page.

I used several helper methods to build different parts of the UI. For example, _buildProfilePicture creates a CircleAvatar that displays the selected image or a default icon if no image has been selected. _buildNameTextField and _buildAgeTextField create text fields for entering the name and age, respectively. _buildSubmitButton creates a button that submits the form when pressed. _buildDisplayWidgets displays the entered name and age, if they have been entered.

One unique aspect of my UI is that I used a GestureDetector to allow the user to select a profile picture by tapping on a CircleAvatar. I think this makes the UI more intuitive and user-friendly. Additionally, I tried to make my code as modular as possible by using a separate widget for each UI element, which makes the code more readable and easier to maintain.
