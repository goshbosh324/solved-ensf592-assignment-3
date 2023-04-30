Download Link: https://assignmentchef.com/product/solved-ensf592-assignment-3
<br>
5/5 - (1 vote)

<header></header>



 <main></main>



<span style="font-size: 2em;">&#x1f4da; Learning Outcomes</span>

<ul>

 <li>Accept user input through varied menu options</li>

 <li>Validate user input through exception handling</li>

 <li>Process data according to specifications</li>

 <li>Iterate through varied values using compound data types</li>

 <li>Manipulate strings and apply regular expressions</li>

 <li>Develop and implement user-defined classes</li>

 <li>Print formatted output according to given specifications</li>

</ul>

<h2 id="programspecifications">&#x1f4bb; Program Specifications</h2>

A cipher is an algorithm used for encrypting or decrypting information. You are being asked to design a terminal-based application for encoding and decoding text based on a provided cipher algorithm. Your application must meet the following design specifications:

<ul>

 <li>Your user interface should prompt the user to input the following information:</li>

</ul>

<ol>

 <li>Whether they would like to encode or decode their text</li>

 <li>Enter their text to be encoded/decoded</li>

 <li>Enter their cipher</li>

</ol>

<ul>

 <li>You may prompt for the input to be entered in any form or order you like, but be sure to give the user clear instructions.</li>

 <li>You must validate that the provided cipher is exactly 26 elements long and only contains lowercase characters from a to z or digits from 0 to 9.</li>

 <li>If the cipher does not meet the criteria, you must handle a ValueError exception by providing a message back to the user and allow them to re-enter their cipher without terminating the program.</li>

 <li>Any entered string is valid for encoding/decoding, however:</li>

 <li>Any punctuation/spaces/etc. within the text should be removed- only letters are encoded/decoded.</li>

 <li>The resulting coded or decoded message must be all lowercase letters with no spaces in between.</li>

 <li>Your code should include and use at least two classes of your own creation, at least three user-defined functions aside from __init__ or main(), at least one iterable object, and at least one regular expression.</li>

 <li>Your code must follow the conventions discussed so far in the course (names<em>with</em>underscores, ClassNames, four spaces for indentations, spaces between variables/operators, comments throughout, etc.)</li>

 <li>All classes and functions must contain docstring documentation.</li>

 <li>Your code will be run by the TAs as your end user.</li>

 <li>FAQs about the assignment will be answered on the D2L discussion boards. Please check the boards for any clarifications before submitting.</li>

 <li>The grading rubric will be posted to D2L.</li>

</ul>

<h3 id="exampletests">Example Tests</h3>

Text to be encoded: “abcde”Cipher: “bcdefghijklmnopqrstuvwxyza”Code result: “bcdef”

Text to be decoded: “abcde”Cipher: “bcdefghijklmnopqrstuvwxyza”Code result: “zabcd”

Text to be encoded: “Tell me and I forget. Teach me and I remember. Involve me and I learn. – Benjamin Franklin”Cipher: “bcdefghijklmnopqrstuvwxyza”Code result: “ufmmnfboejgpshfuufbdinfboejsfnfncfsjowpmwfnfboejmfbsocfokbnjogsbolmjo”

Text to be decoded: “uifcftuboenptucfbvujgvmuijohtjouifxpsmedboopucftffopsfwfoupvdifeuifznvtucfgfmuxjuiuififbsuifmfolfmmfs”Cipher: “bcdefghijklmnopqrstuvwxyza”Code result: “thebestandmostbeautifulthingsintheworldcannotbeseenoreventouchedtheymustbefeltwiththehearthelenkeller”

<h2 id="assignmenttasks">&#x1f4dd; Assignment Tasks</h2>

<ul>

 <li>Make sure to watch video lessons 8 – 14 and review the corresponding Jupyter Notebooks and lab sessions.</li>

 <li>Clone this repository to your local computer.</li>

 <li>Open VSCode and start a new terminal. Make sure that your <code>ensf592</code> environment is activated.</li>

 <li><code>encryption.py</code> is provided as a starting point. Fill in the header with your own information.</li>

 <li>Remember to test your program execution via the terminal: <code>python encryption.py</code></li>

 <li>Take a screenshot of your successful program run and upload it to your assignment repository.</li>

 <li>Commit your screenshot and code.</li>

 <li>Push your local git history to github: <code>git push origin main</code></li>

 <li>Submit your repository HTTPS link to the Assignment 3 D2L dropbox.</li>

 <li>Tip: If you want to learn more about a specific aspect of a Python object, remember to take a look at the official documentation!</li>