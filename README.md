# Intro to Git and GitLab


## Course description

Git is a popular version control system that allows you to easily track code changes and collaborate on projects with any number of people. In this workshop, we will go over the basics of version control, Git, and how to use GitLab to collaborate with other developers.

### Prerequisites:

We won't be working on actual code in this class so there is no need for you to know any particular programming language. We will be using the command line to change directories, list directory contents, and using git from the command line throughout the class, so it is important that you feel comfortable with that. You should bring your own computer to class as we will be installing software and you will need administrator privileges.


### What you'll need (tech):

 - A laptop (Mac, PC, or Linux are all okay).
 - A modern web browser - either Chrome or Firefox with Firebug installed.
 - A code editor. We recommend Visual Studio Code (free; available for Mac, PC, and Linux).


### What we'll cover:

In this workshop we'll cover:

 - the basic concepts of git version control
 - installing git
 - git commands to track changes to a small project
 - set up a free gitlab account
 - create an SSH Key
 - the basics of collaborating on projects with other developers
 - 

### To view the presentation in gitlab pages:

Go to the following URL: [https://women-who-code.gitlab.io/intro-to-git-and-gitlab](https://women-who-code.gitlab.io/intro-to-git-and-gitlab)

Use the 'Instructor Notes' located in the [Wiki of this project](https://gitlab.com/women-who-code/intro-to-git-and-gitlab/wikis/instructor-notes) to walk through the exercises.


### To run the presentation locally:

This course was developed using [reveal.js](https://github.com/hakimel/reveal.js/). 

Some reveal.js features, like external Markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install Node.js (4.0.0 or later)

2. Clone the reveal.js repository

```sh
  $ git clone git@gitlab.com:sarrahvesselov/intro-to-git-gitlab.git
```

3. Navigate to the reveal.js folder

```sh
$ cd reveal.js
```

4. Install dependencies

```sh
$ npm install
```

5. Serve the presentation and monitor source files for changes

```sh
$ npm start
```

6. Open http://localhost:8000 to view your presentation

You can change the port by using npm start -- --port=8001.

### Instructions for Directors

Please clone this project into your own 'Women Who Code' group before holding your class. This will allow you to add personalized slides and to update Instructor Notes if you wish.

Reveal JS support instructor notes (you will see them in the index file.) Documentation on how to edit these notes can be found here: https://github.com/hakimel/reveal.js#speaker-notes

Once running, you can open the slides in presentation mode, allowing you to see the notes. Simply press the `s` key to open the slide notes.
