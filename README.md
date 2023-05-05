Download Link: https://assignmentchef.com/product/solved-csis3280-lab-02-hangman-a-simple-console-version
<br>
Visual Studio Code

<ol>

 <li>Download the lab template from Blackboard 2. Extract it to a directory.</li>

 <li>Rename the files/folders in accordance with the naming convention.</li>

</ol>

<h1>Solution</h1>

The flow of the program is as follows:

<ol>

 <li>The user is prompted for a random pizza type to guess out of the list included in the getWord function.</li>

 <li>The user is then given double the number of tries as their are letters in the random word chosen to guess the word.</li>

 <li>Each time the user tries a letter, the counter is decreased by one and a masked version of the word is displayed, if the user has previously selected a character that is part of the word that is displayed in clear text (See Appendix for example).</li>

 <li>If the user has inputed all the characters for the word then they are congratulated and the program exits.</li>

 <li>If the user uses up all their tries then the program displays “Sorry out of tries! and exits.</li>

</ol>

Requirements:

The program must accept upper and lower case letters

$hangman is the ONLY array you are allowed to modify in the program. This means you are only allowed one array. You may not modify the $pizzaTypes array.

You must use pass by reference anytime you pass the hangman array to a function. All your functions should be in a file called inc/hangman.inc.php.

You must implement the following functions: <strong>printMasked()</strong> – Pass the hangman variable and print the masked version of the word

<strong>guessChar()</strong> – Pass the character that the user guessed and set the appropriate data in the hangman, this function can take the character that the user inputted

<strong>checkStatus()</strong> – This checks if the user has guessed all the characters in the word, if they have then it congratulates them and exits <strong>getWord()</strong> – This function returns a random word from the array provided of Pizza Types. <strong>getArray()</strong> – This function builds the “hangman” array and returns it.

<strong>getTries()</strong> – This function returns the number of tries based on the word that was randomly selected (noOfCharacters * 2)

1 / 2

Lab 02.md                                                                                                                                                                                                 1/17/2019

Hints:

The hangman array is the most important part of this program, how you structure it will dictate how clean your code is and how easy it is to modify.

Think about structure and about how you can use one array to keep track of letters of the randomly selected word and of the letters the user has guessed. (You may want to use a flag or switch of some kind!)

You will likely have to do a bit of planning for this Lab before you start programming, this will help you have a clear idea as to how the program will be structured. Remember, focus on the structure of the Array, this is the most important part of the lab. Arrays are everywhere in PHP!

<h1>Appendix</h1>