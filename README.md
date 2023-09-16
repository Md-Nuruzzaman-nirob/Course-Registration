#### answer to the question no-1 :

# Online Course Platform

Welcome to our online course platform, where you can access a variety of courses to enhance your programming skills. Below are the details of the three featured courses: C Programming, Data Structures, and Python Programming.

## C Programming Course

### Overview

- **Description**: Our C Programming course is designed for beginners and intermediate learners who want to master the C programming language.
- **Key Features**:
  - In-depth coverage of C language fundamentals.
  - Hands-on coding exercises and projects.
  - Access to a dedicated community forum for support and discussions.

### Course Curriculum

- Module 1: Introduction to C Programming
- Module 2: Variables, Data Types, and Operators
- Module 3: Control Structures and Functions
- Module 4: Arrays and Pointers
- Module 5: File Handling and Advanced Topics

## Data Structures Course

### Overview

- **Description**: Dive into the world of data structures with our comprehensive Data Structures course.
- **Key Features**:
  - Learn various data structures like arrays, linked lists, trees, and graphs.
  - Practical implementation of data structures in real-world scenarios.
  - Quizzes and assignments to test your knowledge.

### Course Curriculum

- Module 1: Introduction to Data Structures
- Module 2: Arrays and Linked Lists
- Module 3: Stacks and Queues
- Module 4: Trees and Graphs
- Module 5: Advanced Data Structures

## Python Programming Course

### Overview

- **Description**: Our Python Programming course is perfect for both beginners and experienced programmers looking to enhance their Python skills.
- **Key Features**:
  - Learn Python syntax, libraries, and best practices.
  - Build Python applications and projects.
  - Interactive coding challenges and solutions.

### Course Curriculum

- Module 1: Introduction to Python
- Module 2: Variables, Data Types, and Operators
- Module 3: Control Structures and Functions
- Module 4: File Handling and Python Libraries
- Module 5: Project Development with Python

## Getting Started

- To enroll in any of these courses, simply visit our website and sign up for an account.
- Once registered, browse the course catalog and choose the one that suits your interests.
- Click on the course, and you can purchase it to get started immediately.

We look forward to helping you on your journey to becoming a proficient programmer!

#### answer to the question no-2 :

"In the assignment project, I managed state using React's useState hook, which allowed me to handle and update state variables efficiently. There were two main pieces of state I needed to manage:

courseCartData: This state variable stored an array of selected courses that the user added to their cart. I initialized it as an empty array using useState([]) and updated it whenever a user clicked the 'Select' button to add a course to their cart. I used the setCourseCartData function to update this state.

credit: This state variable kept track of the total credit hours of the selected courses. I initialized it to 0 using useState(0) and updated it whenever a course was added or removed from the cart. This allowed me to ensure that the user did not exceed a maximum credit limit of 20 hours.

Here's a brief overview of how the state management worked:

When a user clicked the 'Select' button on a course card, it triggered the handleClickCartData function.
Inside this function, I checked if the selected course was already in the courseCartData. If it was, I displayed an error message using the toast library to notify the user that they had already selected that course.
Then, I calculated the new total credit hours by iterating through the courseCartData array and summing up the credits of all selected courses.
If the total credit hours exceeded the limit of 20, I displayed an error message.
Otherwise, I updated the courseCartData and credit state variables to reflect the user's selections.
This state management approach allowed me to dynamically update the user interface based on their actions while ensuring that they did not exceed the maximum credit hours. It provided a smooth and error-free user experience."
