## how you alter code
1 parse
2 parse execute
3 parse execute use-result

## flocking rules
1 find the things that are most alike
2 identify the smallest difference between them
3 make the smallest change we can to remove the difference
4 delete the unused code

## step-wise refactor
  "quick green removes all sin"
  "stay out of the red"
  "horizontal vs vertical refactoring" - kent beck
  "not making detours while refactoring"
  "send a message to get things more similar"
  "make the change easy (which is hard), and then make the easy change" - kent beck?
  "When you find you have to add a feature to a program, and the program's code is not
    structured in a convenient way to add the feature, first refactor the program to make it
    easy to add the feature, then add the feature." - Fowler
  "separate the arrangement of the code from adding features, or making the code open"
  "Before you start refactoring, check that you have a solid suite of tests."

## shameless green
  don't worry about drying things up/refactoring before getting all the requirements
  solve the whole problem
  don't worry about changeability
  will you have a better idea now how to change or later?
  you should get something when drying up

## open/close process outside of inheritance
open is the holy grail, you can add new features by adding only new code, not changing existing code, you will add only new tests
is it open for the new requirements?
  if yes, make the change
do you know how to make it open?
  if yes, make it open
fix simplest/best understood code smell
  this should eventually open up the design

## dependency inversion
  if I call class.new then I cannot use another class without modifying my code.

## liskov extended
  if you promise me to be a thing, be a thing
  be what I expect, I shouldn't have to ask what you are

## code smells
primitive obsession - null object pattern
data clump - things that appear together all the time, tend to be an object

## Curriculum
1. refactor book, looking for code smells
2. Growing Object-Oriented Software, Guided by Tests
3. Designing Object-Oriented Software, Rebecca Wirfs-Brock 
4. DDD Quickly pdf

## Single Responsability Principle
  if you had to split the class in half, where whould you? does it make sense? does this denote more than a single responsability?

## Inheritance
  dont use when you only have to implement a small subset
  ask if the child as either a new version or a small collaborator
  want shallow and narrow, not for sharing code, but specializing behaviour, high % of super class is rewritten
  if subclasses are leaf nodes of your dependency graph, stands better chance of time
  if inheritance has been proven wrong then modules isn't going to solve it

## Random words of wisdom
once you have a factory (hidden creation logic) you must use the factory, the class names should be hidden
solve for the else case
echo chamber (duplication, repetition, etc)
"dyanmic oo is to create a new language(dsl) for your domain" - Avdi Grimm
avdi grim conversion function
don't pass something that needs to be immediately converted, it is the responsability of the caller
what would it cost the customer?

