# CS 171 Homework 0



**Due Thursday January 30st 2013 11:59 pm.**

Welcome to CS171.  In this class, we will be using a variety of tools that will require some initial configuration. To ensure everything goes smoothly moving forward, we will setup the majority of those tools in this homework.  While some of this will likely be dull, doing it now will enable us to do more exciting work in the weeks that follow without getting bogged down in further software configuration.  This homework will not be graded and this homework has no group reflection phase, however it is essential that you complete it timely since it will enable us to set up your accounts. You do not have to hand anything in, with the exception of filling out the online survey. 

## Problem 1 - Class Survey, Signups, and Introduction

### Sign up to github

We will be using (github)[http://github.com] to manage our repositories. Sign up to github with your **.edu e-mail address** and request 6 repositories. You can use this text to ask for the repositories:

```
I will be using my educational micro account for CS 171 - visualization at Harvard (http://cs171.org). We will use github and github pages for the code in our homeworks and for our final projects. I will need 6 private repositories (4 for homeworks, 2 for projects) for the class. Thank you!
```

### Class Survey
Please complete the [mandatory course survey located here]([https://docs.google.com/spreadsheet/viewform?formkey=dDJrMGpiNWMtM2NEdHI4YUdsalJnU3c6MA]). It should only take a few moments of your time. Once you fill in the survey we will sign you up to the course forum on Piazza, Learning Catalytics, and the CS50 submission system which you will use to hand in the homework. It is imperative that you fill out the survey on time as we use the provided information to sign you up for other services. 

### Piazza
Go to [Piazza](https://piazza.com/harvard/cs171) and sign up for the class using your Harvard e-mail address. If you don't (yet) have a Harvard e-mail address, send an e-mail to (staff@cs171.org)[mailto:staff@cs171.org] with the subject "Piazza Access: your@e.mail".  

You will use Piazza as a forum for discussion, to find team members, to arrange appointments, and to ask questions. Piazza should be your primary form of communication with the staff. Use the staff e-mail only for individual requests, e.g., to excuse yourself from a mandatory guest lecture. All readings, homeworks, and project descriptions will be posted on Piazza first. 

### Introduction

Once you are signed up to the Piazza course forum, introduce yourself to your classmates and course staff, as a follow-up to the introduction thread. Include your name/nickname, your affiliation, why you are taking this course, and tell us something interesting about yourself (e.g., an unusual hobby, past travels, or a cool project you did, etc.). Also tell us whether you have experience with visualization. 

## Problem 2 - Introduction to Git

We will be using git for version control and collaboration, and github as a host for our git repositories. Linux and (recent) Macs have git command line clients pre-installed. On Windows you can [go here to download and install it](http://git-scm.com/download).

Alternatively, you can use one of the git clients listed on the [resource page](http://www.cs171.org/#!resources.md#Git_Clients).

Read and follow along the mandatory reading - [Understanding Git Conceptually](http://www.sbf5.com/~cduan/technical/git/git-5.shtml). You should use the command line interface to understand what's going on. Then, create your own repository on github with the following name:

```
cs171-hw0-LASTNAME-FIRSTNAME
```
while replacing LASTNAME and FIRSTNAME with your actual last and first name. Clone this repository to your local computer using something like:

```
git clone https://github.com/GITHUBUSERNAME/cs171-hw0-LASTNAME-FIRSTNAME.git 
```

Open or create the README.md file, put your name, harvard ID and e-mail address in it. Then, commit and push to github. Now you should be able to see the changed file in the repository on github.

Next, share the repository with the user **cs171tf**, giving this user read permission. You will be asked to share all your projects and homeworks with this user account, plus the account of your grading TF, starting with HW1. 

## Problem 3 - Introduction to D3

Read the mandatory readings, and follow along with the examples in the D3 book (chapters 1-4, for week 1, chapters 5-8, for week 2). You can put the code you are producing into your github repository for HW0. 

Once you're done with the readings, answer the following questions with regard to this code snippet (assume the variables used are sensibly defined):

```
svg.selectAll(".bar")
  .data(data)
  .enter()
  .append("rect")
  .attr({
    class : "bar",
    width : function(d) {return d;},
    height: "10",
    y : function(d, i) {return i*5;},
    x : textWidth
   });
```
 * What does this snippet do?
 * What is .bar? What am I selecting?
 * Given that data is an array with [3, 4, 9, 1], what values do *d* and *i* take while this program executes. Why?
 * What does append("rect") do?





