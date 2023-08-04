# Simple-chat-bot
Simple chat bot asks person's name and guess the age of the person, plays a  small game.
This is not my first project but this is the first project that I post on GitHub.
Hopefully there will be more.


Chatbot Script Documentation

This script implements a simple chatbot that interacts with the user through a series of functions. It greets the user, asks for their name, guesses their age, counts to a specified number, tests their programming knowledge, and bids them farewell.

Function: greet(bot_name, birth_year)

Greets the user and introduces the chatbot.

Parameters:

    bot_name (str): The name of the chatbot.
    birth_year (str): The birth year of the chatbot.


Function: remind_name()

Asks the user to provide their name and compliments their name.



Function: guess_age()

Tries to guess the user's age based on remainders.



Function: count()

Asks the user to input a number and then counts from 0 up to that number.



Function: test()

Conducts a simple programming knowledge test with the user.



Function: end()

Bids farewell to the user.


Example Usage:

    /python
  
    greet('Aid', '2020')  # change it as you need
    remind_name()
    guess_age()
    count()
    test()
    end()
  /

Explanation:
The script starts by greeting the user, introducing itself with the provided name and birth year. It then asks the user for their name and compliments their name. Next, it tries to guess the user's age based on the remainders obtained by dividing the user's age by 3, 5, and 7. After that, the script prompts the user to input a number and proceeds to count from 0 up to that number. Following the counting, it tests the user's programming knowledge by asking a question and checking if the user selects the correct answer. If the user chooses the correct answer (option 4), the test is completed, and a congratulatory message is displayed. Otherwise, the user is asked to try again until they select the correct answer. Finally, the script ends by bidding the user a farewell and wishing them a nice day.

Please note that the test question's language and content can be customized for different scenarios, keeping in mind the appropriateness of language and content for the target audience.
