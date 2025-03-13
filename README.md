<img width="332" alt="Screenshot 2025-03-13 at 05 47 53" src="https://github.com/user-attachments/assets/6f67bb4d-8e26-4648-837b-b4a921433b33" /># cs50x-final-project
A comprehensive full-stack application integrating core CS concepts to deliver a scalable solution


Overview
This repository contains my final project for CS50’s Final Problem Set. The project is a full-stack application that integrates core computer science concepts to solve a real-world problem. It demonstrates my skills in software development, problem-solving, and the practical application of various algorithms.



Technologies Used
- Programming Language: Python
- Frameworks & Libraries: Flask 
- Front-end: HTML, CSS, JavaScript
- Tools: Git, GitHub, VS Code

 
 
 Installation & How to Run
Follow these steps to set up and run the project locally:


1. Clone the Repository:
   
   git clone https://github.com/ImaadhRenosh/cs50-final-problem-set.git
   cd cs50-final-problem-set

2. Install Dependencies: Ensure you have Python installed. Then, install the required packages:

   pip install -r requirements.txt
   
3. Run the Application: Start the Flask development server:
   
   python app.py

4. Access the Project:

   Open your browser and navigate to http://localhost:5000 to view the application.



Screenshots / Demo

An email can be opened in a wide variety of devices and email applications.
So, you’re coding not just for desktop, phone, or tablet but also for various applications that your email recipients can open your email on. For example, your email can be read on a desktop computer Windows Mail app, but it can also be opened on an iPhone 11 mail app. And, no, unfortunately, there isn’t one standard across them all.
Different email applications support different subsets of HTML and CSS. That support, in some cases, is on the opposite ends of the spectrum. If you talk to an email marketer, you will get to understand the pains of making an email render well in, for example, Outlook or Lotus Notes.

This is an email project meant to demonstrate and replicate my skills in saving, deleting, and updating data via SQL in culmination with both front and back-end programming languages, which in this case was python, HTML, CSS and SQL as mentioned before. in the app.py file we have created a flux activation for a basic email system. The whole gist of this project is to replicate existing emails like gmail, yahoo etc.

This project took some inspiration from the week 9, finance project., in terms of layout and structure

In the app.py file, initially the vital imports are made, including the flux and mandatory libraries. In the first few lines of code, the flux activation is generated, and a constructor is stored in the app variable. Another task done is the auto reloading of templates and session management using the file system, session has been configured to use the SQL Lite database.

<img width="621" alt="Screenshot 2025-03-13 at 05 03 18" src="https://github.com/user-attachments/assets/72a9eca8-e90b-4a1c-994f-1d5bed16beb9" />



The after-app request route is used to ensure that responses are not caught, after approval we can define various routes. This route shows all received emails. furthermore, there are various other routes, each associated with a function to the corresponding request. Inside routes, there are database queries, which can be utilized to store data as required.

<img width="736" alt="Screenshot 2025-03-13 at 05 23 42" src="https://github.com/user-attachments/assets/677680ee-49bb-41e5-86f4-04942f275a07" />



The HTML Templates are rendered via the render-template function. That's everything to do with the app.py file.

The layout.html file holds the backbone structure and style of the webpage with the navigation bar, main content area as well as the footer. ALL the child templates can extend the layout.html file and fill in the dynamic content as needed, using this block {% block title %}.

<img width="1128" alt="Screenshot 2025-03-13 at 05 28 35" src="https://github.com/user-attachments/assets/5168e254-ef9e-44d5-b577-eac825c1ecda" />



To wrap it all up, it’s been an honour to learn from the some of the best teachers in the world, I would like to thank David.J.Malan, Dug Lloyd and all the corresponding teachers and staff for their exemplary performance. I wish to indulge in more courses like this in the future, it’s been a pleasure learning CS50.



Usage
After launching the application, you can:

Navigate through the interface using the provided menu.
Interact with various features designed to solve the problem set.


<img width="1512" alt="Screenshot 2025-03-13 at 05 31 15" src="https://github.com/user-attachments/assets/8ac82f68-da8e-4de0-ba9b-447955caf3c6" />

<img width="148" alt="Screenshot 2025-03-13 at 05 32 39" src="https://github.com/user-attachments/assets/5ca23136-125c-4790-a46e-eaf96c699bed" />

<img width="1510" alt="Screenshot 2025-03-13 at 05 32 00" src="https://github.com/user-attachments/assets/49fc717b-60fd-4020-b9f5-e96afa23e165" />



<img width="332" alt="Screenshot 2025-03-13 at 05 47 53" src="https://github.com/user-attachments/assets/e231efeb-1805-4513-b884-0445a11cf6ae" />

<img width="362" alt="Screenshot 2025-03-13 at 05 42 03" src="https://github.com/user-attachments/assets/dc5ee1c1-66cb-406a-b6bf-d51dead701f7" />




Contributing
Contributions are welcome! If you’d like to improve this project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Commit your changes and push the branch.
Open a pull request detailing your changes.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or suggestions, feel free to reach out:

Email: imaadhrenosh@gmail.com
LinkedIn: linkedin.com/in/yourprofile

   


