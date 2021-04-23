# Machine Learning
## How to treath the Repository
1.  :no_entry: Never use `Upload files` directly on GitHub that only causes inconveniences and everything gets messy. :no_entry:

2. Be cool and use Git :sunglasses:.

3. Clone the repository to your own local directory
    - Navigate to an ordner of your choice, where you want to have the Repostiory located on your PC.
    - Use the green button `clone or download` and copy the given LINK to your clipboard.
    - Open `CMD` in the choosen folder and use `git clone LINK` to clone the repository to this destination.
    - Now you have an Up-to-date version of the BasicPython repo on your local machine.
    - If you want to move the folder to another place, just make sure to move the whole BasicPython directory at once. The `.git` file is the important one which keeps track of the versions, your changes, commits, ... (if you can't see that directory, go to `Ansicht` and make a tick at `Ausgeblendete Elemente`.) As long as that inner structure is ensured, you can move the BasicPython directory where ever you want and without destroying anything.

4. Before you start working on the next assignment or you want to do something, check for **updates**. Maybe someone has commited something while you where off. Simply use `git pull` and your local copy is again Up-to-date.

5. Start working on a task.

6. If you're done and your solution has no bugs (it compiles), go ahead and commit and push the task.

7. If you created a new file for this you at first have to add it to the version control by using `git add FILENAME`afterwards you can commit it using `git commit -m "A COOL MESSAGE"`to commit all changes you've made, or just do `git commit FILENAME -m "A COOL MESSAGE"`. If you commited all changes use `git push` to push it to GitHub from where we, the other contributors can pull it to our machines to be Up-to-date too.

8. I try to make a new directory for every week as soon as the assignment is published. If you are faster and can't wait, please stick to the naming convention `XX_Week`. Please be awear of the Upper 'W' otherwise GitHub and the other contributers might get problems since for example Windows is not case sensitive which then leads to akward mearging behaviours of GitHub. Therefore name it `XX_Week`.

9. If any errors occure while trying to `pull` or `push` don't hesitate to contact me or try to understand the error message. Often you just need to `pull` or `commit` something before you can `pull`/`push` again.

10. Use it and have fun. :kissing_heart:
