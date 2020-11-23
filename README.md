 # RGB Bugged

For this assignment you will be doing something like the google developers debugging tutorial. The code has a bug and you’ll need to fix it. 
  * After forking my repository, use what you’ve learned to debug and fix the code.
  * In your commit message, describe the problem(s) you found and how you fixed it. 
  * Make a pull request with your changes. 
  * Links to materials used to complete the assignment: 
    * https://developer.mozilla.org/en-US/docs/Mozilla/Debugging/Debugging_JavaScript
    * https://developers.google.com/web/tools/chrome-devtools/javascript

    Errors:
    1. It has you win on the first try no matter what you pick.
    2. Problems with displaying all correct colors for Hard when the far right row and far left row.
    3. On easy one - not rendering the squares correctly. 
    4. Scoring problems: concatenating scores
    5. Scoring: minusing score when a square has already been selected.

    What I fixed:
    1. line 61: changed to absolutely equal
    2. Line 135: set i to 0 so it won't miss first square
    3. line 68: I had been messing around with the syntax, and it 
    is working now with score+=%:
    4. 

