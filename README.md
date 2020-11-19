# SeamlessMD-Coding-Test-QAA
SeamlessMD's Coding Test for the QAA position (19 November, 2020)


To run the project on your local machine:
1. Download contents. Ensure that all files (.json & .html) in the repo are in the same directory on your local machine.
2. Open up Terminal (or a CLI fo your choosing), navigate to the directory that you saved the files. Run the command "python -m http.server" to host on your local machine.
3. Open up a web browser (I used Mozilla Firefox during development) and navigate to: http://localhost:8000/index.html
4. Enjoy the mini web-app!


About my design process:
-For the sake of simplicity, I approached this problem in vanilla JavaScript. As mentioned in the code I ran into an issue when listing out the conditions (and simultaneously parsing as HTML). In hindsight, it would have been more efficient to use a library like jQuery which is designed to handle exactly this. I overcame the aforementioned hurdle by pre-processing the list of conditions as a parsed HTML variable and THEN displaying them (as opposed to doing this all in one step).
-Readability is very important when collaborating or sharing code. I have maintained clean code for your viewing pleasure!
