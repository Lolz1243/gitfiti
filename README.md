# gitfiti

## **Letting artistic tendencies shine since 20XX**

### Setup Instructions
- a Java Runtime Environment (check out Oracle's official [JRE](https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html).)
- a Bash Terminal (check out [Git Bash](https://git-scm.com/downloads).)

**Part 1:**


Clone this repo
`git clone https://github.com/Lolz1243/gitfiti`

**Part 2:**


Open the .jar (GUI editor for gitfiti)
```
cd gitfiti
cd dist
java -jar Selectable_Grid.jar
```
- Click on any cell to color it and scroll through for more colors (browse through [gelstudios](https://github.com/gelstudios/gitfiti)'s work for more details)

**Part 3:**


Finished committing your heart out? Right click anywhere within the GUI editor window to enter the end date *DD/MM/YYYY* (ex. inputting 01/01/2017 will start your gitfiti in late 2015/early 2016). A `dates.txt` file should be generated right after and stored within the gitfiti folder.

NOTE: If **dates.txt** isn't generated for you, run `Selectable_Grid.jar` in your terminal, and copy the content into a new file of the same name. 

**Part 4:**


Create a new repo or find an existing one that you don't mind sacrificing. We'll refer to this as `user_repo`

**Part 5:**


Clone this repository
`git clone https://github.com/user_name/user_repo`

**Part 6:**


`git init` if you haven't initialized your repo yet.

**Part 7:**


Configure your email address (and name) if you want to by `git config --local user.name user_name user.email user@abc.com`

NOTE: This email should be linked to the same github account you created the repo in.

**Part 8:**


Copy `dates.txt` and `paint.sh` into `user_repo` where `user_repo` is your repository within your folder on your local computer.

Either:
```
cd /your_path/github-graffiti/dist
cp dates.txt /your_path/myrepo
cd /your_path/github-graffiti
cp paint.sh /your_path/myrepo
```
Or:
`Ctrl+C` and `Ctrl+V` should work just fine.

**Part 9:**


Run the shell script in your bash
`bash paint.sh dates.txt`

**Part 10:**


Enjoy! All your hard work will be committed and presented to the world in less time than it took me to get out of bed. If you want to jump in and help us out with our work, feel free to fork this repo and go wild. I'm excited to see what kinds of creations you all come up with.

Sponsored by Eclipse and the infamous .jar extension, with a special shoutout to [gelstudios](https://github.com/gelstudios) for all the incredible foundational work and naming creds.


### Next Steps:
- Creating a mobile/web app to automatically abuse github commit history.
- Utilizing OpenCV to instantly analyze real-time images/videos/media and subsequently converting them to bitmaps to be displayed on GitHub commit history calendars as true `gitfiti`.
