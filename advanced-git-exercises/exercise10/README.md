this exercise is about how to use pre-commit

however, with windows-user, it is denied to use /chmod command
the solution is to use /icacls command for windows
read in links below:

- https://stackabuse.com/guide-to-understanding-chmod/
- https://petri.com/icacls-command/

another problem is about pre-commit file, maybe it have problem that not found file when you run

solution: 
- add #!/bin/sh to the first line of the file pre-commit then re-do the exercise 10
- bonus: change your pre-commit file by my file