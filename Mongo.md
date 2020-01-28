connection String: mongodb://localhost/bookAPI

When you run mongo, you open up the mongo client prompt.

This error

2019-03-28T15:44:21.820-0400 E QUERY [js] SyntaxError: missing ; before statement @(shell):1:6 
is caused when you run mongo bookAPI < booksJson.js inside the mongo client prompt.
Don't do that!
You can likely type exit in the mongo client prompt to get out of it and back to the Windows prompt.

Instead, run mongo bookAPI < booksJson.js in the Windows prompt, in the directory where booksJson.js is.

First add the mongodb bin folder to the environment variables for windows
then:
Git Bash here in the folder and then run.