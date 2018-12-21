---
title: "Εισαγωγή"
author: ["IOANNIS ZANNOS"]
lastmod: 2018-12-21T05:43:51+02:00
draft: false
weight: 1
---

## Αντικείμενο και εφαρμογές {#αντικείμενο-και-εφαρμογές}

Μουσική Πληροφορική είναι το πεδίο έρευνας που ασχολείται με τις εφαρμογές της Πληροφορικής στην Μουσική.  Η Μουσική Πληροφορική βρίσκει ερευνητικές εφαρμογές στην μουσική ανάλυση, την σημειογραφία, την ψυχοακουστική και ακουστική, και δημιουργικές εφαρμοτές στην μουσική σύνθεση, την εκτέλεση και τον αυτοσχεδιασμό, τον ηχητικός σχεδιασμό, καθώς και όπου επεισέρχεται ο ήχος σε άλλες μορφές τέχνης όπως στον κινηματογράφο την βινεο-τέχνη και τις  εγκαταστάσεις.

Το πρακτικό αντικείμενο του μαθήματος είναι: Αντικείμενο: Programming interactive audio and music applications in SuperCollider.  Γύρω από αυτό όμως γινεται και εισαγωγή σε βασικές έννοιες της μουσικής πληροφορικής και του προγραμματισμού.  Για παράδειγμα, δείτε το επόμενο κεφάλαιο.


## Εργαλεία {#εργαλεία}

Συστήνεται η εξοικείωση με τις εξής τεχνολογίες. Αυτές θα ειχαχθούν διαδοχικά κατα την διάρκεια του εξαμήνου όσο επιτρέπει ο χρόνος.

-   Unix shell (bash, zsh)
-   [SuperCollider](https://supercollider.github.io/)
-   [EMACS](https://www.gnu.org/software/emacs/manual/html%5Fnode/emacs/Intro.html)
-   Git (see github)
-   gist @ github: <https://gist.github.com/iani>
-   hangouts
-   [etherpad](http://etherpad.org/)
-   [sox](http://sox.sourceforge.net/)


## Εισαγωγή: Θεωρητικές Έννοιες {#εισαγωγή-θεωρητικές-έννοιες}

Εδώ είναι μια λίστα των εννοιών που σημειώθηκαν στο 3ο μάθημα.  Σχόλια για τις έννοιες αυτές θα συμπληρωθούν διαδοχικά κατά την εξέλιξη του εξαμήνου.


#### Types of programming styles (Paradigms) {#types-of-programming-styles--paradigms}

See: <https://www.geeksforgeeks.org/introduction-of-programming-paradigms/>

-   Imperative
-   Declarative

Some of the types below can be classified under _imperative_ or _declarative_:

-   Procedural
-   Logic
-   Object Oriented
-   Functional
-   Other (Subject oriented, aspect oriented, etc.)


#### Object Oriented Programming (OOP, Αντικειμενοστραφής Προγραμματισμός) {#object-oriented-programming--oop-αντικειμενοστραφής-προγραμματισμός}

-    "Everything is an object".

    Examples of objects:

    ```javascript
    1               // an integer
    1.0             // a floating point number ("Float")
    \alpha          // a Symbol
    'alpha'         // another way to write the same Symbol as above
    "alpha"         // a String
    $a              // a Character
    [1, 2, 3]       // an Array
    (1..3)          // Shortcut notation for the same Array as above
    \a -> 1         // an Association
    (a: 1, b: 2.0)  // an Event
    Synth(\default) // A Synth
    Server.default  // A Server
    Server          // The Server Class
    ```

-    Objects communicate by sending messages

-    Variables and methods

    -   An object can store data in _variables_, and code its actions as _methods_.  Data is also called _state_ and method content is called _behavior_.
    -   A variable is defined by its name (Names in computer languages are often called [Identifier](#identifier)s.

-    A _Class_ defines the structure and behavior of an object

    The definition of an object type is called its _Class_.  An object created according to the definition of a Class is called an _instance_ of that class.  A class specifies which variables each of its instance will have, and which methods all of its instances share.


#### Basic concepts {#basic-concepts}

-    Function

-    Arguments

-    Recursion

-    Iteration

-    Closure

-    Function callback

-    Asynchronous programming

-    Scheduling, multitasking, threads

-    Namespace

-    OOP concepts

    -    Object

    -    Method

    -    Message

    -    Class

    -    Superclass, subclass, meta class

    -    Inheritance

    -    Polymorphism

    -    Encapsulation

-    Introspection - Reflexive programming

-    Identifier

-    Type / Datastructure

-    Variable

-    Directive (?)

-    Compiler

-    Interpreter

-    Read-Eval-Print-Loop (REPL)

-    Sound related

    -    Signal

        -    Audio and Control rate signals

    -    Buffer

    -    Bus

    -    Unit generator

    -    Synth Process

-    Music related / advanced

    -    Stream and Pattern

-    GUI

-    Types of Intrerfaces


#### Some deeper fundamental concepts {#some-deeper-fundamental-concepts}

-    Human based approach to the concept of information

    -    Signal

    -    Sign

    -    Signifier / Signified

    -    Linguistics / Cognitive Science

    -    Semantics / Semotics

    -    Information ????

    -    Language

-    Non-Human based approach to the concept of information

    -    Data science

    -    Big data

    -    Statistics

    -    Bayesian reasoning


## Ιστογραφία {#ιστογραφία}

-   The Royal Institution, Youtube Channel <https://www.youtube.com/user/TheRoyalInstitution/videos?app=desktop>
