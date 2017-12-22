# Notes for Uncle Bob's clean code course.
---
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


