## Speed Typing Test with Python

This is a CLI application, which mainly uses `curses` library. 

Parameters:

* application should load a random sample test from a .txt file
* it should append an empty list with every character typed by the user
* compare the original random text and the text typed by the user
* highlight in green if the text matches, otherwise highlight in red
* not let users type more than the length of the original text
* count `elapsed_time` and calculate the speed based on # of characters per minute, and # of words per minute (considering an average word is 5 characters)
* give user an option to exit test, promt them to start another test without leaving the application 