# CS-300
Overview
In this project, I created a tool for the Computer Science department at ABCU to help academic advisors easily access and manage course data for students. The goal was to build a system where advisors could load course data, view a list of courses in alphabetical order, and look up specific courses to find out their details, including any prerequisites.

What Problem Was I Solving?
The problem I was tackling was to help academic advisors manage and retrieve course information more efficiently. With the complexity of course prerequisites, it can be tough to keep track of everything manually. Advisors need to quickly find out what courses are available, what prerequisites they have, and ensure they’re suggesting the right courses for students. This program aims to streamline that process, making it easier for advisors to access the information they need.

How Did I Approach the Problem?
I used a Binary Search Tree (BST) to organize and store the course data. The tree allows for courses to be ordered alphanumerically, which makes it super easy to list courses in order or search for a specific course quickly. I chose this data structure because it efficiently handles sorting and searching, both of which are important for this program.

Data structures are a key part of any program because they help define how we store and access data. By using the BST, I was able to ensure that sorting and searching operations would be fast and efficient, even if the number of courses grows in the future.

Overcoming Challenges
Like any project, I faced a few challenges along the way. One of the big ones was handling the input data from the CSV file. The file uses commas to separate the course number, course title, and any prerequisites, but some courses don’t have prerequisites listed, which caused some issues. I had to make sure that the program could correctly handle both courses with and without prerequisites, and skip any lines that weren’t formatted correctly.

Another challenge was making sure the BST stayed balanced and efficient. If the tree isn’t properly managed, searching for courses can become slow. I had to make sure that data was being inserted into the tree in a way that kept it balanced and optimized for search performance.

How Did This Project Change My Approach to Software Design?
Working on this project really helped me appreciate the importance of choosing the right data structure for a problem. I could have used a simple array or list to store the courses, but using the BST made the program much more efficient. It’s a good reminder that understanding and picking the right data structure can make a huge difference in how a program performs.

It also taught me the importance of thinking about how data will be processed before storing it. Validating and cleaning the data before inserting it into the tree ensures that the system runs smoothly without errors.

How Has This Project Evolved the Way I Write Code?
This project has definitely changed the way I think about writing maintainable, adaptable code. I focused on making the code modular, breaking it up into smaller functions like loadData, insert, and searchCourse. This makes it easier to read and understand, and it will be much easier to maintain or extend in the future if needed.

Additionally, I made sure the code was flexible enough to handle changes, like if the input file format changed or if more features were added. The program is designed to be easy to adapt, which is something I’ll carry over into my future projects.

Conclusion
Overall, this project has been a great learning experience. I’ve gained a deeper understanding of data structures and how they play a crucial role in solving real-world problems. It’s also helped me improve how I design software—focusing on making it efficient, flexible, and easy to maintain. I’m excited to apply what I’ve learned here to future projects!
