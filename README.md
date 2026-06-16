
The Film Management System is a lightweight, high-performance console application developed in Go (Golang) designed to facilitate core data administration tasks for media records. Built as a pedagogical tool to demonstrate fundamental computer science concepts, the application implements structured data management, explicit memory allocation constraints, and foundational sorting and searching algorithms. The system effectively showcases how low-level control structures and algorithmic design choices directly impact data manipulation efficiency within a strictly bounded memory space.


// How to Use the Film Management System

1.Prerequisites

a) Ensure you have a Go compiler installed on your system.
b) Save the code in a file named main.go.
c) Run the program in your terminal using the command: go run main.go.

2.Starting the Application
When you run the program, the Main Menu will appear. Use the numeric keys to select an
option:
a) [1] Add Film: Add a new movie to your collection.
b) [2] Show All Films: Display your films with sorting options (by Rating or Title).
c) [3] Find Film: Search for a film by Genre or exact Title.
d) [4] Edit Film: Update information for an existing entry.
e) [5] Delete Film: Remove a film from the list.
f) [0] Exit: Close the application.

3.Step-by-Step Instructions

3.1. Adding a Film

1. Select Option 1.
2. Enter the Title of the film.
3. Enter the Genre.
4. Enter a Rating (a decimal number from 0.0 to 10.0).

3.2. Sorting and Viewing Films
1. Select Option 2.
2. Choose your sorting preference:
a. 1 & 2: Sort by Rating (Highest to Lowest or vice versa).
b. 3 & 4: Sort by Title (A-Z or Z-A).

3. The system will display the sorted list automatically.
3.3. Searching for a Film
1. Select Option 3.
2. Choose your search method:
a. Search by Genre: Enter a genre name to see all matching films.
b. Search by Title: Enter the exact title. The system will automatically sort
the data and use Binary Search to locate your film quickly.
3.4. Editing a Film
1. Select Option 4.
2. The current list will be displayed. Enter the index number of the film you wish to
edit.
3. Follow the prompts to update the Title, Genre, Rating, and Status.
3.5. Deleting a Film
1. Select Option 5.
2. View the list and enter the index number of the film you want to remove.
3. The system will shift the remaining films to fill the gap and confirm the deletion.
