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
  if i % 2 == 0 (
     i
  )
)

from peeps {peep} (
   "\{peep} marshmellow chicks"
)

! functions: 

! objects:
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
coins: 7 ! coins = 7
```
## Conditonals

## Loops

## Functions

## Objects

