#  Online Drink Order by MAYURI CAFÉ 

Project Title: Online Drink Order by MAYURI CAFÉ 
Chosen Domain: Retail & E-commerce 
Real-World Problem Identified: Wastage of 
‘time’ in actually going and purchasing. 
Project Objectives: Reduce time wastage and 
make the process less stressful  
Requirement Analysis and Technology 
Stack 


Functional Requirements: The Program first 
offers the user a variety of items and then generates 
the bill according to the user's chosen items. 
Technology Stack and Tools: 
Course Applied: Fundamentals of Python 
Programming  
Programming Language(s): Python 
Development Environment: VS CODE editor 
Top-Down Design and Modularisation: 


High-Level Architecture:  
The "MAYURI CAFE Online Drink Order System" consists 
of three main logical components: 
1. Initialization: This component sets up the 
application by defining the menu (a dictionary 
holding drink names and prices), and initializing 
variables like order_total (to 0) and selected_items 
(an empty list). 
2. Order Processing Loop: This is the interactive core. 
It repeatedly: 
Takes User Input: Prompts the user for a drink 
choice or to indicate they are "done". 
Validates Input: Checks if the entered drink 
exists in the menu. 
Updates Order: If valid, it adds the drink's 
price to order_total and the drink name to 
selected_items. 
Continues/Exits: Asks if the user wants to add 
more items or if they are "done," controlling 
the loop's continuation. 
3. Order Summary Output: Once the user is done 
ordering, this component takes the selected_items


Implementation, Testing, and 
Refinement: 
Key Implementation Details: The use of the 
.lower() method on the user input ensures that the 
system accepts items regardless of capitalisation 
e.g., 'Cappucchino' or 'cappucchino' 
Testing Strategy: The program was tested by 
making it use to many students around the campus 


Results and Validation: The program offers 
correct results; validation depends on the professor  
Future Scope and Improvements: Can be 
developed at a higher level by including all the items of 
the café and taking the project to a web level. 
and order_total to print a personalized, itemized 
bill.
