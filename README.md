This README is a background information for each of the zip files stored in this repository.
Each zip file is a complete project, and the first line of the will share which IDE it was coded
in if the user wishes to open it the way I coded it.

CornerGrocerStockingApp:
This project was coded in C++ using Microsoft's Visual Studios 2019 as an IDE. This application
was coded during my attendence at SNHU as a practical examination of my coding skill. The task
provided was to generate a program that would load an input file, aggregate the objects on that
file into a frequency list, with no specified ordering, output that frequency list as a .dat,
and have a user interface that fetched information from that aggregated list. The user interface
was required to have 4 options in this order, 1: search the aggregated list for a specified item,
2: print the aggregated list with the frequency of each object as a number, 3: print the aggreg-
ated list as a histogram, and 4: quit the program.

For the aggregated list, I had decided to use a custom class in a vector, both to show my ability
in creating custom classes, and to mentally simplify later code. The custom class in the vector
was able to store 2 data types, an int containing the number of occurrances of the object, and a
string naming the object.

Looking back, there are a few changes I would make off the top of my head, but I would rather
leave the code as-is as a history piece. I will name those changes for posterity's sake, I
would change the vector of a custom class to a map. That should make the search and counting
sections significantly faster. I would code input sanitization and remove case sensitivity, from
the input file. Currently the program stores "Fries" and "fries" as two different objects, which
isn't the best for user legibility in a list that contains a large amount of items.

The toughest part of this project for me was sticking to my design plan. Early in my coding I
decided to code a custom class to show my proficiency and organization of my custom classes.
I thought that pairing that with my comments made during coding should make my thought process
during coding classes obvious, so I chose that over using a map. As I was coding the searching
and the for loops, I was heavily tempted to go back and re-code the aggregation method to be a
map instead.

Overall, I feel like this project went as easily as it did due to my early design documenting
and my planning before I sat down to code. Once I knew what my coding required and where it would
require it, I was able to draw up and organize my code around those requirements. Using this or-
ganization I can easily go back and re-code sections to debug, or add any additional sections
of coding. In case the hypothetical grocery store decided that they wanted additional UI options
or for the .dat file to be encrypted.
