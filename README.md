# CS-300-Project-Two
Final project to create a course planner.

[1] What was the problem you were solving in the projects for this course?
--------------------------------------------------------------------------
We were tasked with crating a program that would load a course list into a data structure from a text file.
I chose to implement a binary search tree to perform the necessary functions. These functions include: creating
the data structure, load data into the structure (with a variable number of items) by parsing through the text
file, and printing the items (either individually or sorted alphanumerically). This program must be able to take 
any text file that is formatted appropriately.

[2] How did you approach the problem? Consider why data structures are important to understand.
-----------------------------------------------------------------------------------------------
In project one, I determined that a binary search tree would be the appropriate data structure for this task. 
I was able to successfully load a file into the program and load it into the data structure. I created a binary
search tree. I passed the appropriate data by creating a temporary vector to hold each line of the text file. 
I separated the data using commas as a delimiter. The items of each line were added to the vector and then assigned
as course variables to be loaded into the binary search tree. My inOrder function traverses the tree down the left 
side and then prints up to the root and then down the right side. This produces output that shows the contents of the
file in alphanumeric order. I was also able to search a course by course number by searching the binary search tree recursively
until the matching course was found. Using abinary search tree allowed us to perform these processes in an intuitive and 
efficient manner. 

[3] How did you overcome any roadblocks you encountered while going through the activities or project?
------------------------------------------------------------------------------------------------------
Throughout this course and all project related activities, I had difficulty appropriately loading the data into data structures. 
I had a lot of trial and error before I landed on an effective method to parse and assign each data item. I learned a lot about 
using substring functions to parse through data through my efforts. In the end I still failed to properly validate prerequisites
and account for lines that had fewer than 2 items. However, I think that given more time to work on the project, I would be able 
to implement these mechanics. 

[4] How has your work on this project expanded your approach to designing software and developing programs?
-----------------------------------------------------------------------------------------------------------
Through working on this project, I was able to implement code in a way that I had not been able to previously. I had parsed data
using other programming languages, but this was my first experience doing so using C++. Prior to taking this course, I was unfamiliar
with creating and implementing data structures. I am happy to have been able to add these skills to my coding lexicon.

[5] How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?
------------------------------------------------------------------------------------------------------------------------
Each program that we write allows us to continue developing our individual coding styles and conventions. I have been able to further
define how I like to organize and create code. This project has let me practice the passing of files into programs and the efficient 
handling of data. I will certainly be carrying these skills forward into subsequent courses and my future career.
