# Whats new in Swift
------
## Naming Guidelines
* ```array.appendContentOf(0)``` goes to ```array.append(contentsOf:)``` for example
* ```array.insert()```
* Improved generics as generic types
* Stringly types Objective-C Constants

## Core Language
* Arguments label now are required to all parameters
* Generic constrains at the end of the function 😀
* Warn on Unused results by default! Turn of with `@discartableResult`


## Removed Features
* ++ and -- are gone
* C-Style `for` loop
* Etc, etc etc

## Type System
* Unsafe pointers cant not be nil
* Unsafe pointers use optionals
* Inplicity Unwrapped Optional is only forced

## Standard Library
* Now we have Float.pi 😳 or anyNumeric.pi for that matter


# Swift Tools
-------
## Tools
* Dictionary is 3x faster
* WMO on by Default in all projects
* Right click is now improved and can now navigate nicer
* It also has nicer groupings
* You get to choose between 2.3 and 3.0 so you can migrate when you can
* You can conditionally compile with 2.3 and 3.0
* You can migrate any time you want.
