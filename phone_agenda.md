# Merge two different phone agendas

Imagine that you need to organize a party and to create a guest list. 
You're adding alphabetically all your friends from your phone agenda in a huge array you create in memory (you have a lot of friends). You start your list with your best friend who is somewhere in the middle of your agenda. When you've reached the end of the agenda, you start from the beginning and do the same thing until you reach your best friend.

Now you have an array of names that are mostly alphabetical, except they start somewhere in the middle of the alphabet, reach the end, and start from the beginning of the alphabet.
Here is an example of your guest array:

```javascript
var guests = [
    "George",
    "Gregory",
    "Hugo",
    "James",
    "Julia",
    "Lara",
    "Noah",
    "Pamela"
    "Paul",
    "Pauline",
    "Sandra",
    "Salima",
    "Tudor",
    "Adam",  // <-- changing point!
    "Alesia",
    "Bridget",
    "Charlie",
    "Celine",
    "Diane",
    "Fabio"
]
``` 

***Write a method for finding the index of the "changing point,"*** which is where you start adding guests from the beginning of your agenda. This array is huge (you have a lot of friends) so we want to be efficient here.