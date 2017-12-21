#Notes for Uncle Bob's clean code course.

##Names
* Classes:
    * noun (avoid 'noise', such as: Manager, Data...);
    * use shorter names for public classes and longer names for public classes

* Methods/functions:
    * mostly use verb or verb pharses (run, getPrive, setPrice);
    * if function return boolean use predicate with adjective (isEmpty, isFull...),
    * use shorter names for public functions and longer names for private functions

* Variables:
    * use noun;
    * use predicate for boolean: isPostable....;
    * use tiny names for variables in short scopes, and longer names for longer scopes;
    * use shorter names for public variables and longer names for public variables

* Enums
    * often adjectives:
    `enum Color {
        RED, GREEN, YELLOW
    }`
