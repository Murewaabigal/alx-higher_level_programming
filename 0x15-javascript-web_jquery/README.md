Requirements General Allowed editors: vi, vim, emacs All your files will be interpreted on Chrome (version 57.0) All your files should end with a new line A README.md file, at the root of the folder of the project, is mandatory Your code should be semistandard compliant with the flag --global  You must use JQuery version 3.x You are not allowed to use var HTML should not reload for each action: DOM manipulation, update values, fetch data… More Info Import JQuery

<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
Manual QA Review It is your responsibility to request a review for this project from a peer before the project’s deadline. If no peers have been reviewed, you should request a review from a TA or staff member.

Quiz questions Great! You've completed the quiz successfully! Keep going! (Show quiz) Tasks 0. No JQuery mandatory Write a JavaScript script that updates the text color of the

element to red (#FF0000):
You must use document.querySelector to select the HTML tag You can’t use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 0-main.html

<title>Holberton School</title> First HTML page Holberton School - 2017 <script type="text/javascript" src="0-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 0-script.js

With JQuery mandatory Write a JavaScript script that updates the text color of the element to red (#FF0000):
You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 1-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> First HTML page Holberton School - 2017 <script type="text/javascript" src="1-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 1-script.js

Click and turn red mandatory Write a JavaScript script that updates the text color of the element to red (#FF0000) when the user clicks on the tag DIV#red_header:
You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 2-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> First HTML page
Red header
Holberton School - 2017 <script type="text/javascript" src="2-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 2-script.js

Add .red class mandatory Write a JavaScript script that adds the class red to the element when the user clicks on the tag DIV#red_header
You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 3-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> <style> .red { color: #FF0000; } </style> First HTML page
Red header
Holberton School - 2017 <script type="text/javascript" src="3-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 3-script.js

Toggle classes mandatory Write a JavaScript script that toggles the class of the element when the user clicks on the tag DIV#toggle_header:
The

element must always have one class: red or green, never both in the same time and never empty. If the current class is red, when the user click on DIV#toggle_header, the class must be updated to green ; and the reverse. You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:
guillaume@ubuntu:~/0x15$ cat 4-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> <style> .red { color: #FF0000; } .green { color: #00FF00; } </style> First HTML page
Toggle header
Holberton School - 2017 <script type="text/javascript" src="4-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 4-script.js

List of elements mandatory Write a JavaScript script that adds a
element to a list when the user clicks on the tag DIV#add_item:
The new element must be:

Item
The new element must be added to UL.my_list You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:
guillaume@ubuntu:~/0x15$ cat 5-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> First HTML page
Add item

Item
Holberton School - 2017 <script type="text/javascript" src="5-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 5-script.js

Change the text mandatory Write a JavaScript script that updates the text of the element to New Header!!! when the user clicks on DIV#update_header
You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 6-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> First HTML page
Update the header

Holberton School - 2017 <script type="text/javascript" src="6-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 6-script.js

Star wars character mandatory Write a JavaScript script that fetches the character name from this URL: https://swapi-api.hbtn.io/api/people/5/?format=json
The name must be displayed in the HTML tag DIV#character You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 7-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> Star Wars character

Holberton School - 2017 <script type="text/javascript" src="7-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 7-script.js

Star Wars movies mandatory Write a JavaScript script that fetches and lists the title for all movies by using this URL: https://swapi-api.hbtn.io/api/films/?format=json
All movie titles must be list in the HTML tag UL#list_movies You can’t use document.querySelector to select the HTML tag You must use the JQuery API Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 8-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> Star Wars movies

Holberton School - 2017 <script type="text/javascript" src="8-script.js"></script> guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 8-script.js

Say Hello! mandatory Write a JavaScript script that fetches from https://fourtonfish.com/hellosalut/?lang=fr and displays the value of hello from that fetch in the HTML tag DIV#hello.
The translation of “hello” must be displayed in the HTML tag DIV#hello You can’t use document.querySelector to select the HTML tag You must use the JQuery API Your script must work when it is imported from the tag Please test with this HTML file in your browser:

guillaume@ubuntu:~/0x15$ cat 9-main.html

<title>Holberton School</title> <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script> <script type="text/javascript" src="9-script.js"></script> Say Hello!

Holberton School - 2017 guillaume@ubuntu:~/0x15$ Repo:
GitHub repository: alx-higher_level_programming Directory: 0x15-javascript-web_jquery File: 9-script.js
