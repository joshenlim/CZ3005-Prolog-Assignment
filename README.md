# CZ3005 - Artificial Intelligence Assignment 2

This assignment aims to mimic a small real-world scenario through the use of [Prolog](https://www.swi-prolog.org/), a logic programming language. SWI-Prolog version 7.6.4 was used and tested in this project.

## Assignment Context

The prolog script offers different meal options, sandwich options, meat options, salad options, sauce options, top-up options, sides options etc to create a customized list of a person's choice. The options should be intelligently selected based on previous choices. For example, if the person chose a veggie meal, meat options should not be offered. If a person chose healthy meal, fatty sauces should not be offered. If a person chose vegan meal, cheese top-up should not be offered. If a person chose value meal, no top-up should be offered.,

## Setup

Download and install SWI-Prolog if you've yet to do so. If Chrome complains about a possible malware, an alternative way to download is through the use of `curl`

`curl -O https://www.swi-prolog.org/download/stable/bin/SWI-Prolog-7.6.4.dmg`

Open the SWI-Prolog terminal and change the working directory to the root of this folder

`working_directory(_, 'PATH_TO_ROOT_OF_FOLDER/subway-sandwich-interactor.pl').`

Load the prolog script into the current session

`['subway-sandwich-interactor.pl'].`

Start the program by typing the following command

`ask(0).`