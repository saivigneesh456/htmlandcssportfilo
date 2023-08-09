<html>
<style>
/* Global Styles */
body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f9f9f9;
}

.container {
  max-width: 100%;
  margin: 0 auto;
  padding: 20px;
}

a {
  color: yellow;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* Header Section */
#header {
  text-align: center;
  background-color: #007bff;
  color: #fff;
  padding: 20px 0;
}

#name {
  font-size: 32px;
  margin-bottom: 10px;
}

#email {
  font-size: 20px;
  margin-bottom: 10px;
  color: red;
}

.resume-link {
    display: inline-block;
    background-color: #fff;
    color: #007bff;
    padding: 8px 16px;
    border: 2px solid #007bff;
    border-radius: 4px;
    text-decoration: none;
    font-weight: bold;
}

.resume-link:hover {
    background-color: #007bff;
    color: #fff;
}

/* Left and Right Columns */
.left,
.right {
  width: 100%;
  padding: 10px;
  box-sizing: border-box;
}

.left {
  background-color: white;
}

.right {
  background-color: white;
}

/* CV Highlights */
ul {
  list-style: disc;
  padding-left: 20px;
}

/* Professional Experience */
#company-name {
  color: #007bff;
  font-size: 24px;
  margin-bottom: 5px;
}

#job-title {
  font-size: 20px;
  font-weight: bold;
}

#job-responsibilities {
  font-weight: bold;
  color: #007bff;
}

/* Educational Qualifications */
table {
  width: 100%;
  border-collapse: collapse;
  margin-bottom: 20px;
}


th,
td {
  border: 1px solid #ccc;
  padding: 12px;
  text-align: left;
}

#heading {
  font-weight: bold;
  background-color: #f9f9f9;
}

/* Independent Courses */
#course-name {
  font-weight: bold;
}

/* Projects */
ul li {
  margin-bottom: 10px;
}

/* Personal Information and Declaration */
h3 {
  color: #007bff;
}

/* Footer Section */
#footer {
  text-align: center;
  background-color: #007bff;
  color: #fff;
  padding: 10px 0;
}

/* Media Queries for Responsive Design */
@media (min-width: 600px) {
  .container {
    max-width: 800px;
  }

  #name {
    font-size: 32px;
  }

  #email {
    font-size: 20px;
    color: red;
  }
}


</style>
 <head>
<title>InfySkill portfolio</title> 
</head>
<body>
<div id="header">
<p id="name">InfySkill</p>
         <a href="mailto:hr@infyskill.in" target="_blank"><p id="email">hr@infyskill.in</p></a>
         <a href="https://drive.google.com/file/d/1z9jK3L6sEP8EMoCxYRAvA4g-zRxUh47i/view?usp=sharing">View Resume</a>
     </div>
     <div class="left">
     </div>
     <div class="right">
            <h3>CV Highlights</h3>
            <p>
            <ul>
                <li>HTML – Hypertext Markup Language & css</li>
                <li>Learnt basic Python, JavaScript, HTML, CSS on infyskill edutech</li>
                <li>A self-sufficient, committed, and efficient individual. These characteristics are demonstrated through a number of courses I have taken or am now taking independently via online platforms.</li>
                <li>Good communication skills, presentation skills, leadership attitude, authorization and delegating, dispute resolution and negotiation, and a great team player.
</li></ul>
            </p>
            <h3>Professional Experience</h3>
            <h4 id="company-name">InfySkill Edutech Pvt Ltd</h4>
            <p id="job-title"><strong>Full Stack Developer</strong></p>
            <p id="job-responsibilities">Job Responsbilities</p>
            <p>
            <ul>
                <li>Front-end Development:</li>
                <li>Back-end Development</li>
                <li>Full Stack Development</li>
                <li>Version Control and Deployment</li>
                <li>Testing and Debugging</li>
                <li>Collaboration and Communication</li>
                <li>Continuous Learning and Improvement</li>
                <li>Project Management</li>
                </ul>
            </p>
            <h3>Educational Qualifications</h3>
            <table>
                <tr id="heading">
                    <td>Qualification</td>
                    <td>Board</td>
                    <td>Percentage / Grades</td>
                    <td>Year</td>
                </tr>
                <tr>
                    <td>S.S.C</td>
                    <td>Monterssori english medium school</td>
                    <td>93%</td>
                    <td>2017</td>
                </tr>
                <tr>
                    <td>H.S.C</td>
                    <td>Sri Chaitanya Junior College Vijayawada</td>
                    <td>91.5%</td>
                    <td>2019</td>
                </tr>
        
                <tr>
                    <td>Vel Tech Unversity (Computer Science and Engineering)</td>
                    <td>University</td>
                    <td>85</td>
                    <td>2023</td>
                </tr>
                
            </table>
            <h3>Independent Courses</h3>
            <p>
            <ul>
                <li>
                <span id="course-name">HTML & CSS for Beginners – Web Fundamentals</span> – infyskill.in</li>
                <li>
                <span id="course-name">Python – Fundamentals and Dynamic Programming </span> - infyskill.in</li>
                <li>
                <span id="course-name">JavaScript – Programming Basics, JS Apps and Build Games </span> - infyskill.in</li>
                <li>
                <span id="course-name">CS101: Introduction to Computer Science - Building a Web Crawler</span> - infyskill.in</li>
               
            </ul>
            <h3>Internships</h3>
            <p>
            <ul>
                <li>
                <span id="course-name">Java Full Stack Internship</span> Virtusa Student Ambassador Program Internship -JUN 2022-APR 2023</li>
                <li>
                <span id="course-name">HR - Coordinator Internship</span> AICTE Internships NOV 2022-MAR 2023</li>
                <li>
                <span id="course-name">Cybersecurity Virtual Internship</span> AICTE Internships MAR 2022-MAY 2022 </li></ul>
            </p>
            <h3>Project  </h3>
            <p>
            <ul>
                <li><b>Phd Admission Portal</b> – The Ph.D. Admission Portal is a web application developed using Java as the backend language and the
Spring Boot framework for server-side development. The front end of the application is built using React, for
building user interfaces.</li>
                <li><b> Responsive Portfolio Website</b> The Responsive Portfolio Website is a project aimed at creating a visually appealing and user-friendly website
to showcase your portfolio, skills, and accomplishments. The website is designed to adapt and provide an
optimal viewing experience across different devices and screen sizes, ensuring that your portfolio is accessible
and visually appealing to a wide range of users.</li>

<li><b>Ride Sharing Application</b> TThe Ride Sharing Application is a Java-based project developed using the Spring Boot framework. It is
designed to provide a convenient and efficient platform for users to share rides, making transportation more
accessible and cost-effective.</li></ul>
            </p>
            <h3>Personal Information:</h3>
            <p>
            <ul>
                <li>
                A young, determined hard and smart working person. </li>
                <li>
              I believe in task based roles and complete ownership of work.</li>
                <li><span id="course-name"><b> Languages Known:</b></span>English and Telugu</li>
                <li>
                <span id="course-name"><b> Hobbies: </b></span>I love reading Finance and IT related books / magazines, playing Chess, swimming, listening music, surfing Internet, self-learning through e-courses.</li> </ul>
            </p>
            <h3>Other Information</h3>
            <p>
            <ul>
                <li>
                <span id="course-name"><b> Area of Interest: </b></span>Software Development, Programming, Start-ups, Coding etc.</li>
                <li>
                <span id="course-name"><b> Joining Date:</b></span>Immediate</li></ul>
            </p>
            <h3>Declaration</h3>
            <p>
                       <li> I hereby declare that the details furnished above are true and correct to the best of my knowledge and belief.</p> </li>          
     </div>
     <div id="footer"></div>
    </body>
</html>
