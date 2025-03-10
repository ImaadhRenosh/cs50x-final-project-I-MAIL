# cs50x-final-project
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

The after-app request route is used to ensure that responses are not caught, after approval we can define various routes. This route shows all received emails. furthermore, there are various other routes, each associated with a function to the corresponding request. Inside routes, there are database queries, which can be utilized to store data as required.

The HTML Templates are rendered via the render-template function. That's everything to do with the app.py file.

The layout.html file holds the backbone structure and style of the webpage with the navigation bar, main content area as well as the footer. ALL the child templates can extend the alyout.html file and fill in the dynamic content as needed, using this block {% block title %}.

To wrap it all up, it’s been an honour to learn from the some of the best teachers in the world, I would like to thank David.J.Malan, Dug Lloyd and all the corresponding teachers and staff for their exemplary performance. I wish to indulge in more courses like this in the future, it’s been a pleasure learning CS50.



Usage
After launching the application, you can:

Navigate through the interface using the provided menu.
Interact with various features designed to solve the problem set.
[Add any additional usage instructions specific to your project.]




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

   


