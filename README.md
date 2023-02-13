# FillBlanksAssignment

Description: A Wikipedia Fill-in-the-blanks app


When the user opens the app, it displays the text from a random Wikipedia page. 10 random words from the text are replaced by blanks and the user needs to guess what those words are. When the user taps / clicks on a blank, a list of all the 10 words are shown and the user can choose one of them. The UI updates to show that the user has filled up that blank. The user can tap / click a submit button once he’s done and the app shows him his score out of 10. If the user does not fill any particular blank, then he does not get points for it. Along with the user score, a button to “Replay” the game is displayed. Upon tapping / clicking it, the game begins again.

Code:
The game makes use of the following ideas, implemented in Swift 4.0, and xCode9.3 -

[URLSession] - To call RESTful API to fetch data from Wikipedia, the URL and the search word is time being hard coded for testing purpose.

[Arc4Random] - To generate a random number to select random words

[UIButtons] - These buttons are placed over the randomly chosen words so that when the user taps one of them, the system knows where to replace which words. UIGestureRecognizer is not used in this, and instead a logic with hidden buttons is built

[textView text positioning] - These lines of code help us to determine the location of the randomly selected words so that we could place the invisible button over them.

[UIPickerView] - This is used to display the hidden words to the user so that the user can select on of them for each location.

[UITableView] - This table is used to show the user their score card along with their choices against the correct answers.


