# Introduction 

Here is the bad news: the new developer you hired has written some terrible, atrocious code. 
No one can understand what it does. 

The good news: at least there are unit tests to prove the code is working. 

You job is to refactor the code and make it readable, while keeping the code in working order (pass all tests). 

# How To Start

1. Clone this repository `git clone https://github.com/CodelyTV/finder-refactoring-kata-php`
2. Build the docker container which contains all the required dependencies with `make build`
3. Run the tests with `make test`
4. Start refactoring! 

The primary goal is to refactor the code in `src/Algorithm/Finder.php` - as it stands the code is incomprehensible. 

# Tips

* Start with simple rename refactors so you can better understand the abstractions you are working with. Rename any class or any variable. 
* Move on to extract methods and making the code more modular.
* See if you can also eliminate switch statements and multiple exit points from methods. 

Anything is fair game, create new classes, new methods, and rename tests. 
The only restriction is that the existing tests have to keep working. 
Lean on the tests and run them after every small change to make sure you are on the right path.

# How to End

You can stop when you feel the code is good enough, something you can come back to in 6 months and understand. 

# Helpful resources

## PHPUnit 8.5

* [Introduction to writing tests for PHPUnit](https://phpunit.readthedocs.io/en/8.5/writing-tests-for-phpunit.html)
* [Testing exceptions with PHPUnit](https://phpunit.readthedocs.io/en/8.5/writing-tests-for-phpunit.html#testing-php-errors-warnings-and-notices)
* [PHPUnit assertions](https://phpunit.readthedocs.io/en/8.5/assertions.html)

## Refactoring

* [Refactoring.guru Code Smells catalog](https://refactoring.guru/smells/smells)
* [Refactoring.guru Refactorings catalog](https://refactoring.guru/catalog)
* [SourceMaking Refactorings catalog](https://sourcemaking.com/refactoring)
* [Martin Fowler Refactorings catalog](http://refactoring.com/catalog/)
* [CodelyTV Refactoring videos (Spanish)](http://codely.tv/tag/refactoring/)

# Credits and other programming languages

You can also find the kata in different programming languages in isolated repositories just ready to clone and enjoy:

* 🐘 [PHP](https://github.com/CodelyTV/finder-refactoring-kata-php)
* 🦈 [C#](https://github.com/CodelyTV/finder-refactoring-kata-csharp)
* ☕  [Java](https://github.com/DoDevJutsu/incomprehensible-finder-refactoring-java)
* 🧬 [Scala](https://github.com/CodelyTV/finder-refactoring-kata-scala)

This kata is a Scala port of [the original Incomprehensible Finder Refactoring Kata](https://github.com/OdeToCode/Katas/tree/master/Refactoring) created by [K. Scott Allen](https://github.com/OdeToCode).

Port developed by [CodelyTV](https://codely.tv/) and [contributors](../../graphs/contributors). Migrated to PHP 7.4 and Docker by [Clean Design](https://github.com/Clean-Design)
