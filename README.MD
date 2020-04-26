Unit 02 CSS and Bootstrap Homework: Responsive Portfolio
Responsive design ensures that web applications render well on a variety of devices and window or screen sizes. As a developer, you will likely be asked to create a mobile-first application or add responsive design to an existing application.

Directions
First, you will use the Bootstrap CSS Framework to create a mobile responsive portfolio. How do you deliver this? Here are some guidelines:


Create the following files files: index.html, portfolio.html and contact.html.


Using Bootstrap, develop your portfolio site with the following items:


A navbar


A responsive layout


Responsive images




The Bootstrap portfolio should minimize the use of media queries.


Screenshots are provided as a reference in the Assets/Images folder. Your app does not need to be exactly like the images. Use Bootstrap to create a similar, responsive layout.



Hints


Use Bootstrap's grid system (containers, rows, and columns).


On an xs screen, content should take up the entire screen. On sm and larger screens, you should have some margins on the left and right sides of the screen. Check out various sites on your mobile device vs. your computer to see examples of these differences.


Use an HTML validation service to ensure that each page has valid HTML.



Minimum Requirements


Functional, deployed application


GitHub repository with README describing the project


Navbar must be consistent on each page.


Navbar on each page must contain links to Home/About, Contact, and Portfolio pages.


All links must work.


Must use semantic html.


Each page must have valid and correct HTML. (use a validation service)


Must contain your personalized information. (bio, name, images, links to social media, etc.)


Must properly utilize Bootstrap components and grid system.



Bonus

Using Bootstrap, make a sticky footer and use sub-rows and sub-columns on your portfolio site (Hint: Check out the Bootstrap documentation).


Commit Early and Often
One of the most important skills to master as a web developer is version control. Building the habit of committing via Git is important for two reasons:


Your commit history is a signal to employers that you are actively working on projects and learning new skills.


Your commit history allows you to revert your codebase in the event that you need to return to a previous state.


Follow these guidelines for committing:


Make single-purpose commits for related changes to ensure a clean, manageable history. If you are fixing two issues, make two commits.


Write descriptive, meaningful commit messages so that you and anyone else looking at your repository can easily understand its history.


Don't commit half-done work, for the sake of your collaborators (and your future self!).


Test your application before you commit to ensure functionality at every step in the development process.


We would like you to have well over 200 commits by graduation, so commit early and often!

Submission on BCS
You are required to submit the following:


The URLs of the deployed applications


The URLs of the GitHub repositories



<!--!DOCTYPE html>
<html>
  <head>
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css">
  </head>



  <body>

    <nav style="background-color:gray; box-sizing: border-box; color: white; text-align: center;">
        <ul>
            <a href="html/about.html">About  &nbsp; &nbsp; &nbsp;</a>>   &nbsp; &nbsp; &nbsp;
            <a href="Portfolio.html"> Portfolio  &nbsp; &nbsp; &nbsp; </a> >  &nbsp; &nbsp; &nbsp;
            <a href="html/contact.html">Contact  &nbsp; &nbsp; &nbsp;</a> >  &nbsp; &nbsp; &nbsp;


          <!--li><a href="#">Home</a> &nbsp; &nbsp; &nbsp; <a href="#">About Me</a> &nbsp; &nbsp; &nbsp; <a href="#">Contact</a>
        </ul-->
      </nav>


    <header class='masthead'>
    
        <img src="" class="responsive" width="100%" height="auto">
    <a href="https://www.instagram.com/leonardesere/?hl=en">
        <img src="United nation.jpg" class="responsive" width="33%" height="20%"  alt="Leonard Esere"/>
    <!--h1 style="text-align: center;">Leonard A Esere </h1-->
    </a>

</header>


        <div class="ex2" style="float: left;">
        </div>

    <div id="absolute">
        <aside> <h1> Leonard Esere</h1>
            <P>             My name is Leonard Osakpolor Aigbokhaevbo <br> 
                I'm an Information Technology Specialist with concentration <br> 
                on Cyber-SECURITY. I have experience in computer repair and small office network <br>
                setup and configurations, with little expertise in cyber security. <br>
                Highly intellectual and curious to finding how one thing inter-connects to another. </p>
                 <br>

        </aside>
    </div>

  </body-->


  p {
  font-size: 45;
  font-family: 'MyWebFont', verdana, sans-serif;
  font-weight: 700;
  font-style: italic;
  color: rgb(41, 20, 175);
  text-align: center;
  letter-spacing: 7px;
  text-indent: 10%;
  hyphens: auto;
  text-shadow: purple 1px 0 10px;
}