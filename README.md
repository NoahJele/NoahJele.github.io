# Welcome!
This is my E-Portfolio for my SNHU CS-499 Capstone Course, and will show off multiple enhancements of artifacts that I've worked on in the past. Each enhancement will include a narrative explaining the enhancement, and also an initial code review of each artifact. The first work to appear on this portfolio will be a Professional Self Assessment. After that, a code review that analyzes each of my artifacts. Then, finally, all of my artifact narratives and enhancements.

# Professional Self-Assessment
Throughout my experience in the Computer Science program at Southern New Hampshire University, I’ve learned a ton about programming, testing, and the ability to interact with real world situations. I believe that completing my coursework (and then enhancing three key artifacts in this e-Portfolio) showcases my problem solving abilities, my ability to thoroughly test programs and find issues/fix them, and my ability to optimize programs. I’ve had several courses which have contributed to me becoming well-rounded in the computer science field, based on key aspects of the field. For example, I’ve engaged in several classes relating to **collaborating in a team environment**, such as my *CS 250: Software Development Lifecycle course*, which focused on Agile development and working concisely with a team. I learned key skills about how to work together with others in order to complete projects and solve problems. This expands to the concept of **communicating to stakeholders**, which I learned a lot about in my *DAT 220: Fundamentals of Data Mining course*, which focused on accurately analyzing sections of information and explaining my findings/recommendations to a company based off of the information. This happens all of the time within the industry, and it’s really important to know how to make key business recommendations based off of relevant information. In regard to **data structures and algorithms**, I have a lot of classes under this section, including *CS 260: Data Structures and Algorithms*, and *IT 365: Operating Environments*. In these courses, I learned a lot about optimization for programs, while still maintaining secure code for each program I worked on. In today’s world of increasing optimization and speed, having this under my belt is necessary. Next, for **software engineering**, the vast majority of my classes have focused on code development, but my favorite course was *CS 320: Software Testing, Automation, and Quality Assurance*. This course taught me so much about the importance of constantly and consistently testing code, and taught me about the importance of Unit Tests, which can be a huge help, especially with complicated programs. For **databases**, I learned a lot about mySQL and MongoDB through my *DAD 220: Introduction to SQL* and *CS 340: Advanced Programming Concepts* courses. I’m most comfortable working with databases, and was able to pick up on the concepts of these courses very quickly. Lastly, for **security**, all of my courses related to developing secure code, but I did learn a lot specifically through my *CS 405: Secure Coding* class, which was integral in teaching me about how to find different types of bugs and errors, as well as how to fix them. It also taught me a lot about potential security risks and how to mitigate them. With all of that said, these combined skills make me prepared for the Computer Science field because they’ve made me extremely well-rounded, and in conjunction with my drive and motivation, along with my problem solving abilities, I feel extremely confident that I’ll be able to make a positive impact wherever I go within the field.

Before we get started with the contents of the e-Portfolio itself, I want to first summarize what each artifact will do, and how they fit together to show off my skills. My software design enhancement refers to a medical program, but the bigger point of it is to show off my skills in creating Unit Tests in order to verify that each function works as intended. In my enhancement, I greatly optimized the program and added more Unit Tests. For my algorithms enhancement, I fixed/added a few different functions within the Linked List program, which takes data from a CSV folder and loads it, as well as letting the user search through it, add content to it, etc. Lastly, my databases enhancement is essentially a showcase of my ability to utilize SQL commands, ranging from simple to relatively complicated. The reason I chose these three specific artifacts was to demonstrate the full range of my computer science abilities, and to show that I’m well rounded in the field. Without further ado, let’s begin with the code review. 


# Code Review
My code review was the first step I took to enhancing my projects. In my review, I spend about 30 minutes on each artifact, and succinctly describe what each artifact does. I thoroughly went through each artifact in order to determine its functionality, as well as room for improvement for each one.

[Click on this link to view the code review.](https://youtu.be/ZAZzl17PZ5k?t=0)

# Software Design Narrative/Enhancement Link
The artifact used for my software design/engineering enhancement is a project I worked on in my CS 320: Software Testing, Automation, and Quality Assurance course. The name of this artifact is medicalApplication. The point of this program is to represent a medical system that can add patients/doctors, add medical records, and more. The bigger point of this project in the context of our course was to develop JUnit tests for each relevant function. I originally developed this project several months ago. The reason I selected this artifact for my software design/engineering enhancement is because it had a lot of room for improvement. The components of the artifact that showcase my skills in software development include the ability to perform relevant JUnit tests, discover and fix bugs (some variables were misnamed – passwordAttepts instead of passwordAttempts, for example), my ability to handle exceptions, and my ability to optimize a program. The main problems with the original project was that it was not extensively commented, the main class was cluttered, and the JUnit tests weren’t fully fleshed out. For example, every function had an assertTrue test associated with it, but only some had assertFalse tests, which can be just as important. In this enhancement, I completely fleshed out the JUnit tests, thoroughly commented my code throughout all classes, added several exception handling statements, and fixed the issue of the main class being cluttered. Basically, the main class (App.java) originally contained the logic for prompting the user to enter a password, and if it were correct, then showing the main menu of options. While this is fine, I decided to create a main menu class that is simply referenced in the main class when the program is ran. It just looks cleaner. Overall, this program was improved and optimized greatly with the enhancements I’ve made. I met all of the objectives that I planned to meet with this enhancement in my ePortfolio plan laid out in module one. Specifically, I met the Computer Science program outcomes ‘Develop a security mindset’ (JUnit tests and bug finding/fixing), ‘Demonstrate an ability to use well-founded and innovative techniques’ (Exception handling/optimizing classes), etc. I think that the biggest thing I learned while enhancing this artifact is that everything can be improved and optimized when looking at a specific program through the mindset of perfecting it rather than just finishing it. While this program originally did accurately perform the functions it was intended to fulfill, there was a ton of room for optimization and improvement, which is what I focused on. I had some challenges regarding figuring out exception handling, and separating a big chunk of the main class into its own class that is simply referenced in the main method. Once I figured these things out, though, the rest of it felt really natural. The JUnit tests were very simple to expand on, and finding bugs like misnamed classes/variables were fun (I enjoy software testing/finding bugs a lot). Overall, enhancing this artifact was a great experience. 

[Click on this link to view the Software Design enhancement in GitHub.](https://github.com/NoahJele/NoahJele.github.io/blob/main/Software%20Design%20Enhancement.zip)

# Algorithms/Data Structures Narrative/Enhancement Link
The project I used for my algorithms/data structure portion of the ePortfolio is one I worked on in my CS 260: Data Structures and Algorithms course last year. This project is called LinkedList, and the point of this artifact is that a .csv file with ‘bids’ is taken as an input, and the program quickly loads in the bids, allowing the user to add new bids, view all bids, etc. I included this artifact in my ePortfolio because it simply had unfinished features that always bothered me. First off, it wasn’t commented to the best extent in the past, and the two features that were unfinished are the FindBid() and RemoveBid() functions. The idea of these functions is that they take a bidID and quickly find the row where it exists in the csv file and then returns the info of the bid or removes it, depending on the function. The problem is that these features weren’t developed with user input in mind, and instead just used a predetermined ID to search for/remove. This artifact shows my skills in algorithms and data structures by showing off my ability to develop code that quickly loads in large lists of data, with the ability to develop relevant features for the program. It also shows my skills to develop secure code, as I created logic to require a password from the user to be able to utilize the program. This gives the user 3 attempts to enter the password “Open”, and if the password attempts run out the program closes. To summarize, this artifact was improved by more thoroughly commenting it, by promoting secure code through password usage, and by fully developing the unfinished features FindBid and RemoveBid. I met the course objectives that I planned to meet with this enhancement. Specifically, I met the objectives ‘Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices’ (finishing the FindBid and RemoveBid methods), and ‘Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities (Creating more secure code/requiring a password). I think the lesson I learned from this particular enhancement is to not settle if you know that something can be improved. Back when I take the course where this assignment was dealt with, our instructor told us to not bother to develop the FindBid and RemoveBid functions, which never sat right with me. I learned through improving this artifact that I’m decent at plotting things out in my head before executing them in code, as I was able to pretty easily finish the relevant functions to provide the utility that I wanted. By proxy, I also learned how useful these types of applications are in the real world, specifically how in a program like Excel the user can search for specific things all the time. The biggest challenge I faced was actually in implementing the password logic, as I had some trouble getting the loop correct for it, but I eventually was able to figure it out.

[Click on this link to view the Algorithms/Data Structures enhancement in GitHub.](https://github.com/NoahJele/NoahJele.github.io/blob/main/Algorithm%20Enhancement.zip)

# Databases Narrative/Enhancement Link
This artifact was originally my final project in the course DAD 220: Introduction to SQL, and was created about a year ago. This project involves the MESSAGING database, which has tables referring to people, contact lists, images, etc. The idea with this database is that the user can perform select queries that display how many messages a person has sent, an associated image to the message, etc. This refinement focused on making the select queries more efficient and expanding the database as well. This was a great inclusion in my ePortfolio because it really shows off my comfortability with core SQL concepts. I specifically chose this project because of how in depth and expansive it is. The specific components of the artifact that show my skills and abilities include my ability to concisely perform specific SQL tasks, the ability to expand upon a finished project in order to show off more functionality, and my skills in logically pairing different tables together within select queries in order to show my competence within this aspect of Computer Science. I improved this artifact by making my select queries more efficient, and by adding a brand new table into the database entirely (the advanced_info table) which is used to reference other tables and display key info for people within the tables (someone’s phone number, zip code, etc). I also improved this artifact by expanding upon my explanation for each SQL task I performed within the artifact, to make my thought process absolutely clear. I met the course objectives that I planned to meet with this enhancement. Specifically, I met the outcome “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals”, because these SQL concepts are constantly used within the industry to achieve real-world objectives, and demonstrating the ability to be comfortable with executing those concepts is a key part of nailing this outcome. I also met the outcome “Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.” I met this outcome because of the SQL Milestone Document I created for this enhancement, which clearly describes my thought process and methods for each task I completed, which can be really important within any industry/profession, as it’s important to explain to your team/project manager HOW you made a certain improvement/change, and WHY you made it. I had a blast refining this artifact and improving it. SQL is my favorite thing to work with in the field of Computer Science, and learning new things about it genuinely gets me giddy. The biggest thing I learned is that even when something is already efficient, it can ALWAYS be expanded upon and improved upon. Even when improving it, though, it should be noted that this is the only enhancement that I literally had zero challenges with. It felt really natural to come back to this project and to enhance it, and even though I originally completed this project a year ago, it felt like I was just working on it yesterday, as seemingly none of the core SQL concepts have left my head since the last time I worked on this. This genuinely felt like a really successful and product enhancement.

[Click on this link to view the Databases enhancement in GitHub.](https://github.com/NoahJele/NoahJele.github.io/blob/main/Database%20Enhancement.docx)
