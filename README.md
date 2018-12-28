<<<<<<< HEAD
# GitHub Graffiti Creator

## Inspiration
So, there is a friend of mine and she had her birthday. I noticed that she has not created a github user account yet, so I went ahead to create one for her. And wrote this application, to design and create a special birthday message for her. 

![The birthday message](https://github.com/mavrk/github-graffiti/blob/master/images/demo.png "The birthday message")

### What do you need ?
1. Java runtime environment (https://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html)
2. A bash terminal (https://gitforwindows.org/ will work like a charm for Windows users)

### How to get started ?

**Step-1** Clone this repository
`git clone https://github.com/mavrk/github-graffiti`

**Step-2** Open the GUI editor
```
cd github-graffiti
cd dist
java -jar Selectable_Grid.jar
```
Click on any cell to color it, click again to cycle through colors
![Sample Design](https://github.com/mavrk/github-graffiti/blob/master/images/demo2.png "Sample Design")

**Step-3** Once done with making your design, right clicking anywhere inside the designer window. Enter the date (when you want this pattern to be displayed). A `dates.txt` file will be generated.

`If dates.txt isn't generated for you. Run the jar file using a terminal and copy the content generated in the terminal to a new file dates.txt`

**Step-4**  Create a new repository (or use an old one). Let us call this 'myrepo'

**Step-5** `git clone https://github.com/myuser/myrepo`

**Step-6** If the repository is not initialised `git init`

**Step-7** To make sure that your commits are reflected in the contributions chart add the email address 

`git config --local user.email mysuer@xyz.com`

NOTE : This email should be assosciated to the same github account you created the repo in.

**Step-8** Copy `dates.txt` and `paint.sh` into `myrepo` where 'myrepo' is your repository.

```
cd /your_path/github-graffiti/dist
cp dates.txt /your_path/myrepo
cd /your_path/github-graffiti
cp paint.sh /your_path/myrepo
```
**Step-9** Run the script
`bash paint.sh dates.txt`



=======
# gitfiti

**Letting artistic tendencies shine since 2016.**

Sponsored by Eclipse and .jar files, with a special shoutout to https://github.com/gelstudios/gitfiti for all the incredible foundational work.

### Next Steps:
- Creating a mobile/web app to automatically abuse github commit history.
>>>>>>> a65bcdb8a8836c4e6d341a9f9f35b4641303edad
