# The Mad Programming Language

## Overview
```
! this is a comment

! definitions:
isMad: true
count: 0
sum: ~ 0
peeps: ["yellow", "pink", "blue"]

! conditionals:
if {isMad} ( 
   "(╯°□°）╯︵ ┻━┻" 
)

if count = 0 (
   "nothing"
) else if count = 1 (
   "something"
) else (
   "things"
)

! loops:
while sum < 10 (
   sum +: 1
)

from 0...sum {i} (
  if i % 2 = 0 (
     "\{i} is even"
  )
)

from peeps {peep} (
   "\{peep} marshmellow chicks"
)

! functions: 
add: {a, b} (
   a + b
)

four: add{2, 2}

! objects from functions:
Person: {name, age, isMad} (
   talk: (
      if isMad (
         print{"Get off my lawn."}
      ) else (
         print{"Howdy, neighbor!"}
      )
   )
)

mack: Person{name: "Mack", age: 23, isMad: true}
mack.talk{} ! prints: "Get off my lawn."
```
## Definitions
To define something, use the ```:``` operator.
```
greeting: "Howdy"
score: 100
contains: true
```
By default, all definitions are immutable.
```
greeting: "Hi" ! Error: greeting already defined
```
To make definitions mutable, use the ```~``` operator
```
coins: ~ 33
coins: 7
```
## Conditonals

## Loops

## Functions

## Objects

