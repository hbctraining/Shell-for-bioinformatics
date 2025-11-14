# Shell for Bioinformatics

## Learning Objectives

- Navigate around the command line interface (bash/shell)
- Create and manipulate text files
- Submit jobs to a high-performance computing cluster

## Installations

***Mac users:***
No installation requirements.  
***Windows users:***
[GitBash](https://git-scm.com/download/win)  

## Notes
* These materials focus on the use of local computational resources at Harvard, which are **only accessible to Harvard affiliates**
* Non-Harvard folks can [download the data](https://www.dropbox.com/scl/fi/sfuftv7qx2fdi37wytep3/unix_lesson.zip?rlkey=hdx8yq1ppp80mqurrxcxj67tz&e=1&st=51v17xlz&dl=1) and set up to work on their local clusters (with the help of local system administrators)

### Instructions for Harvard researchers with access to HMS-RC's O2 cluster

To run through the code in the lessons below, you will need to be **logged into O2** and **working on a compute node** (i.e. your command prompt should have the word `compute` in it).

1. Log in using `ssh ecommonsID@o2.hms.harvard.edu` and enter your password.
2. Once you are on the login node, use `srun --pty -p interactive -t 0-2:30 --mem 1G /bin/bash` to get on a compute node or as specified in the lesson.
3. Proceed only once your command prompt has the word `compute` in it.
4. If you log out between lessons (using the `exit` command twice), please follow points 1. and 2. above to log back in and get on a compute node when you restart with the self learning.

## Lessons

### Part I
1. [Introduction to Shell](../lessons/01_the_filesystem.md)
2. [Wildcards and shortcuts in Shell](../lessons/02_wildcards_shortcuts.md)
3. [Examining and creating files](../lessons/03_working_with_files.md)
4. [Searching and redirection](../lessons/04_searching_files.md)

#### Answer Key 
[Solution to exercises](../homework/Day1_answer_key.txt)

***

### Part II
1. [Shell scripts and variables in Shell](../lessons/05_shell-scripts_variable.md)
2. [Loops and automation](../lessons/06_loops_and_automation.md)
3. [Permissions and Environment Variables](../lessons/07_permissions_and_environment_variables.md)

#### Answer Key 
[Solution to exercises](../homework/Day2_answer_key.txt)

***

### Part III
1. [Introduction to High-performance computing](../lessons/08_HPC_intro_and_terms.md)
1. [Introduction to the O2 cluster](../lectures/HPC_intro_O2_Feb2021.pdf)

***
 
## Building on this workshop

- [Accelerate with Automation - Making your code work for you](https://hbctraining.github.io/Training-modules/Accelerate_with_automation/)
- [Needle in a Haystack: Finding and summarizing data from colossal files](https://hbctraining.github.io/Training-modules/Finding_and_summarizing_colossal_files/)
- [Tips and Tricks for the O2 cluster](https://hbctraining.github.io/Training-modules/Tips_and_Tricks_on_O2/)

***

## Resources

Cheat sheets:
* [http://fosswire.com/post/2007/08/unixlinux-command-cheat-sheet/](http://fosswire.com/post/2007/08/unixlinux-command-cheat-sheet/)
* [https://github.com/swcarpentry/boot-camps/blob/master/shell/shell_cheatsheet.md](https://github.com/swcarpentry/boot-camps/blob/master/shell/shell_cheatsheet.md)
* [tldr_ : Simplified version of the `man` pages (online and searchable)](https://tldr.ostera.io/)

Online tutorials:
* [Explain Shell](http://explainshell.com)
* [Introduction to the Command Line for Genomics](https://datacarpentry.org/shell-genomics/)
* [BASH Programming - Introduction HOW-TO](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* [Bioinformatics from the Command Line](https://medium.com/ngs-sh)

General help:
* Google it! - if you don't know how to do something, try Googling it, other people have probably had the same question.
* Learn by doing! There's no real other way to learn this than by trying it out.
  * Use vim on your laptop
  * Move around the directory structure on your laptop using the Terminal/Shell counts
  * Open folders and files using the command `open`
  * Automate something you don't really need to automate
* Use `man bash` to get more information about bash (bourne-again shell)

***

*These materials have been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*
