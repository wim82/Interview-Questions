# Merge two different phone agendas

Imagine that you're organizing a party and you are creating a guest list. 
You're adding alphabetically all your friends from your agenda in a huge array you are creating in memory (you have a lot of friends) but you start from the beginning, you start with your best friend which is somewhere in the middle of your agenda.
When you reached the end of the agenda, you start from the beginning and do the same thing until you reach your best friend.

Now you have an array of names that are mostly alphabetical, except they start somewhere in the middle of the alphabet, reach the end, and start from the beginning of the alphabet.
Here is an example of your guest array:

```
String[] guests = new String[] {
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
}
``` 

***Write a method for finding the index of the "changing point,"*** which is where you start working from the beginning of the agenda. This array is huge (you have a lot of friends) so we want to be efficient here.