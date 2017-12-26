# Notes for Uncle Bob's clean code course.
## Names
* Classes:
    * noun (avoid 'noise', such as: Manager, Data...);
    * use shorter names for public classes and longer names for private classes

* Methods/functions:
    * mostly use verb or verb pharses (run, getPrise, setPrice);
    * if function return boolean use predicate (isEmpty, isFull...),
    * use shorter names for public functions and longer names for private functions

* Variables:
    * use noun;
    * use predicate for boolean: isPostable....;
    * use tiny names for variables in short scopes, and longer names for longer scopes;

* Enums
    * often adjectives:
    `enum Color {
        RED, GREEN, YELLOW
    }`
---
## Functions
* Functions should be small, about 4-7 lines.
* Function should one thing, do it well and do it only.
* Large function should be refactored into class/module.
* Extract function from another till you drop (till it possible).

## Function stucture
* No more than 3 arguments.
* Do not pass boolean arguments.
* No output arguments.
* Do not check arguments for `null` in your system (except you are developing public API).

## Class/module structure
* Put most important stuff and less detailed on top,
and less important (and more detailed) to bottom.
* Switch statement
    * Minimaze usage of switch statement.
    * Replace it with pylymorphism.
* Make dependencies on abstraction (interfaces).
* Switch case can be used in main partition.
* Resolve temporal coupling with passing a block.

## CQS
* Command - setters (change state).
* Query - getters (should not change state).
* functions that return value, should not change state.
* functions that change state, should not return values.


## Loops
* Avoid mid-loop returns and breaks.

## Catching Errors
* Write error code before another code.
* `try` word should be in the first line of function and contain
only function call.



## Thesaurus
Tempolar coupling - function that should be called one after another.
CQS - Command Query Separation.

## Law of Demeter:
* You may call methods of objects that are:
    1. Passed as arguments
    2. Created locally
    3. Instance variables
    4. Globals
* You man NOT call methods of objects that are:
    1. Returned from a previous method call. (point.getx().gety().getz().doSmth())

