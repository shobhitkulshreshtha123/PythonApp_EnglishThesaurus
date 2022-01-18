# PythonApp_EnglishThesaurus
A working thesaurus created using Python. Uses difflib to provide alternates if the word is not found.

App uses json file which is loaded every time the program is run in variable my_data_file. json file contains a dictionary of words and their definations. This was downloaded from free online resource.

Thereafter an indefinate loop starts which ends only if the user presses N at the end of a word search. User is asked to input a word to find its definations.

If the word is found in my_data_file as a key to dictionary, its corresponding value is displayed and user is asked to either continue searching for more words or exit the app.

If the word is not found, the app uses get_close_matches from difflib library to find similar words that are available in my_data_file and prompts the user to refer them.
