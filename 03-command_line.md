# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> 1. pwd
> 2. mkdir
> 3. rm -R
> 4. touch filename
> 5. rm filename
> 6. mv oldname newname
> 7. ls -a
> 8. cp file directory
> 9. vim ~/.bash_profile can change settings to your profile, source makes changes available
> 10. ~ is home directory

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> 1. lists files in directory
> 2. lists files including hidden
> 3. lists in long format
> 4. lists in long format and formats sizes
> 5. lists in long format, including hidden, and formats sizes
> 6. lists files based on time last modified
> 7. lists files with color, long format, and shows slash after files that are directory

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> 1. -d showing only directories can be useful depending how you organize your directory
> 2. -m can be useful if you need to create a csv file or something
> 3. -q can be useful when dealing with certain characters
> 4. -r useful to flip around any of the flags (e.g. with -t)
> 5. -1 useful (maybe with xargs)


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > you can create a list of arguments to pipe into a command so that you can apply that same command to all the arguments instead of doing them individually.

> > find . -name '*.py' | xargs rm

you can remove all .py files.

 

