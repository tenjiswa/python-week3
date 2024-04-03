# python-week3
USER STORIES: Are brief, simple and informal, perfect for jotting down on index cards.
Format "As a [user/role] i want[goal] so that[reason/benefit]" [who?,what?,why? of a task or goal]
when writing user stories,focus on the user's goals and reasons,rather than specific interface details or implementation methods.
USE CASE:Typically include a title, an actor(a user/system) and a scenario that describes how a goal is achieved(what?,who and how?)
TRADITIONAL REQUIREMENTS:Describes what the application should or should not do and are written as sentences staring with"the application must" or "the application shall"
NON-FUNCTIONAL REQUIREMENTS: describes how the application should accomplish its tasks.They focus on qualities like maintainability, reliability and usability.
Architecture: the class is responsible for generating and retrieving content,the email class handles formatting content and sending email, gui class manages configuration-related behaviours
SUB CODE
1.dd_content.py:Independent functions to retrieve random quotes, allowing easy expansion
2.dd_email.py:Contains the skeleton for the daily digest email class, with placeholder method using the pass statement.
3.dd_gui.py:Handles the gui for the email digest administrator and utilizes the Tkinter module.Import statement for Tkinter included.
DAILY INSPIRATIONAL QUOTES
To implement the "get_random_quotes" function, the source of random quotes needs to be determined.
Storing the quotes and their authors can be done using the different file formats like CSV,JSON or XML.
The   CSV file is opened and a list of dictionaries is created using list comprehension, where each dictionary represents an author and their quote.
API(Application programming interface) is a way for 2 or more computer programs or components to communicate with each other.
It is important to use actively maintained libraries when working with APIs since they can change over time.

