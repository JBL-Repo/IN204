# IN204 - Course recap #

**Course 1-2, Groundwork: Class, methods, CTors/DTors, heritage, references.**
* How to be generic in C++ using classes
* Changing the behavior of a class with heritage.
* `c.inc();` // +1, +2 or +8 depending on the class instanciated

**Course 3, Templates:**
* How to be generic, compile time with templates + function polymorphism
* What are traits (a way to get code genericity by programming behaviors with different implementations)
* `concatDigits(int,int); // Append the first and second parameters (as if they were put next to each others visually, in base 10)`
  * Several implem: Basic one (int, then size_t), then template one, then specialized one
  * Explicit instanciation + build chain
  * Special case for doubles/floats, modulo doesn't works on them (using now `snprintf()`)

**ourse 4, STL: Containers, iterators and presets.**
* The goal of containers, setters/getters.
* `class number; class MyArray;`

**Course 5: Operators and streams on class.**
* What are streams (and `<iostream>`)
* `operator<<()` is nothing more than an other operator
* Extended the `class number` pretty printing stuff to work with the DoStuff test function

**Course 6, C++20: Contracts, specialization and adv notions**
* Upgraded addition class + concepts
* A practical example: How to make a 3,4 and 5 dial generic class
* A 3D coordinate vector class (for the raytracer) + more templates
* Color in a terminal + toying with preprocessing  (to make code less redundant + easier to read)

**Course 7: Exceptions**
* What is error management and safety ?
* https://isocpp.org/wiki/faq/exceptions#why-exceptions
* `class Screen; class Pixel;`

**Course 8:** Adv heritage and polymorphism
**Course 9:** Parallel and asynchronous programming
**Course 10:** Project good practices
**Course 11:** Smart pointers

**Exam 2020 original subject and manual correction with comments:**
* https://perso.ensta-paris.fr/~bmonsuez/Cours/lib/exe/fetch.php?media=in204:8_-_in204_-_examen.pdf (link on pdf is broken)

