# Typesetting the Book "Schnee im September"

## Introduction
Unlike most of the contributions here on Github, "Schnee im September" is not software.
It's a piece of open source literature.
That means that all the rules and the ideology of FOSS applies to this book too.
In turn you can do whatever you desire with this material from correcting spelling mistakes to writing own installations in its' fictional universe to forking the story if you didn't like the ending (see section "Canon").

## Language
My mother tongue is german so this is the language "Schnee im September" ("Snow in September" in english) is written in.
I'm not proficient enough in any other language to translate it.
But if you can: help is greatly appreciated.

## Typesetting
For ease of sharing and better structuring, I opted for LaTeX as the markdown language of this book.
So you need a working LaTeX distribution installed on your system.
In order to typeset your own copy of this book on linux or macOS first clone this repository.

    git clone https://github.com/MarkusYemisci/SiS.git

Then open up a terminal and navigate to the directory namend after the language in which you would like to typeset the book. E.g.:

    cd Deutsch

Now just type:

    pdflatex <Title of the Book>

This title is dependent on your chosen language. E.g. in german:

    pdflatex "Schnee im September.tex"    

## Canon
In fiction _canon_ is an important notion.
It answers the question as to what contributions, ideas and information in general is to be taken as "real" in a given story.
There are many stories about Sherlock Holmes for example.
But only a phew are considered to have "acutally happend" in Arthur Conan Doyles universe.

The following rules characterize canon for the fictional universe "Schnee im Septemer" takes place in.

### Alpha plus canon
The original stories written by the respective authors of a certain fork.
In this case works by me, Markus Yemişçi.

### Alpha canon
Works by a different author that do not contradict any alpha canon information and have some connection to alpha canon stories.
If a beta canon story is being referenced by a alpha canon work it automatically becomes alpha canon.

### Beta canon
Works that have no direct connection to alpha canon stories but also don't contradict information given by them.
Examples are spin offs an loose sequels.

### Reimaginations / Reboots / etc.
If you wish to tell your own version of this story you are free to do so.
Perhaps you want to use certain aspects of the universe but change others significantly.
Like "Battlestar Galactica" did in 2003.
The you should fork this repository and create an alternate version of the story.

## Collaboration
To manage teamwork on this project the following rules apply:
### Small corrections
Typos, missing words, etc. can be corrected without any comment.
### Grammar corrections
Fixing of grammar mistakes should be accompanied by a little comment.
Just to be sure that the intended meaning is preserved.
### Entire sentences / paragraphs
Larger corrections like striking out sentences or changing them completely should be motivated.
### Comments on a larger scale
Changes that would affect large portions of the work should be discussed in a seperate file.
Said file should be named like this:

    <name of scene>_discussion.tex
