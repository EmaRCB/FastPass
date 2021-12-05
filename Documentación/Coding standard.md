# Standard of coding

## Design of the code

Use 1 (a) indentation space. This is the default working on the replit tool.

Avoid the accumulation of 'if' sentences. In case you have any code of the form 'if - elif - ... - elif - else' or 'if; if; if; if; else' this must be replaced by alternatives such as the use of cycles for with the handling of lists. 

For the appointment of functions, variables, keys and others that merit it. The camelCase will be used.

For the case of functions the names of these must correspond to verbs, the language of these can vary.

In the case of classes the names of these must correspond to nouns, the language of these must be in Spanish.

You can switch between the use of Spanish and English in the code, this to solve the problems that can have using special characters like the 'ñ'


Imports

More than one import can be on the same line as another.

Imports are made in this order based on their importance:
- Imports that are vital to the operation of the bot.
- Import of the database, if used.
- Importation of classes.
- Import of local functions.


## Blank spaces

Lines of code can be left to differentiate the beginning of one process from another. 

Unnecessary blanks in sentences should be avoided at all costs.


## Use of functions

If a code block occupies at least 20 different statements. Use of functions should be deeply considered. In the case of the main file 'main' yes or yes arrived the 20 lines of code must be grouped in a function.


## Use of classes

Consider using classes to group functions that work the same way either in other parts of the code or even in other classes.


## Text

All text that is used as a constant must be stored in the database.


## Use of the database

In case of having constant text this must be stored in the database.

Before deleting any element from the database you must compile the code by printing the keys, after this you must make a second compilation but this time directly using the key you are looking to delete. This is to check its contents.

If you have 'variables' that are constant (such as dictionaries or lists) they are stored in the database. 


## Changes in the code

Before making a change it is important to notify the rest of the team. But speaking of the proposed standard for this, when making a change it is commented on the beginning of the change the author of such change as well as the date. 

In case you change large amounts of code back the old code in a.pyfile.

At the end of a 'day' work on the code, make sure it continues to work, by which I mean the code continues to compile.

If you want to update the code repository when making changes, these must be substantial. Enough to be considered another version of the bot.


## Use of comments

Comments must be of a maximum duration of two days (unless they explain the basic functioning of functions or code blocks). After this they are removed to have more cleaning in the code.

Comments are made in these situations:
- The code block following the comment is complex and its understanding is not intimate.
- Important changes were made to code blocks.
- Some important process is concluded, so a priori you will not receive more changes.
