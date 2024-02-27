# My-CV-using-html-and-CSS.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - CV</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <div class="container">
    <header>
      <img src="owaispic.jpeg"height alt="Your Profile Picture" class="profile-picture" >
      <div class="header-text">
        <h1 class="name">Muhammad Owais</h1>
        <h3>Web Developer</h3>
      
      </div>
    </header>
  
    <section>
      <h1>Contact Information</h1>
      <ul>
        <li><b>Email: </b> moowais638@gmail.com</li>
        <li><b>Phone: </b>03264917496</li>
        <li><b>LinkedIn: </b> MuhammadOwaisGUll</li>
      </ul>
    </section>
  
    <section>
      <h1>Education</h1>
      <ul>
        <li>
          <div class="education">
            <h3>COMSATS University Islamabad , Lahore</h3>
            <p><b>Degree :</b>  BS Software Engineering  <br><b>Graduation Year :</b> 2026</p>
          </div>
        </li>
        <li>
          <div class="education">
            <h3>Punjab College Of Science</h3>
            <p><b>Degree : </b>Intermediate (Pre Engineering)  <br><b>Graduation Year :</b> 2022</p>
          </div>
        </li>
        <li>
          <div class="education">
            <h3>Workers Welfare Higher Secondary School</h3>
            <p><b>Degree : </b>Matriculation (Science)  <br><b>Graduation Year :</b> 2020</p>
          </div>
        </li>
      </ul>
    </section>
    
    <section>
      <h1>Technical Skills</h1>
      <ul>
        <li>
          <div class="Programming Languages">
            <h3>Programming Languages</h3>
            <p>Java, Python, C, JavaScript<br></p>
          </div>
        </li>
      </ul>

      <h1>Hobbies</h1>
      <ul>
        <li>
          <div class="Programming Languages">
            <p>Cricket, Book Reading<br></p>
          </div>
        </li>
      </ul>
    </section>
  </div>
</body>
</html>


.name{
    margin: 20px auto;
   width: 1250px ;
   text-align: center;

}
.container
{
    background-color: grey;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
  }
  
  header {
    background-color:grey;
    color: black;
    border-bottom: 5px solid;
    text-align: center;
    padding: 2em 0;
  }
  
  .profile-picture {
    width: 120px; 
    height: auto;
    border-radius: 50%;
    float: left;
    margin-right: 20px; 
  }
  
  .header-text {
    text-align: left;
  }
  
  section {
    margin: 2em;
  }
  
  h1 {
    color:black;
    border-bottom: 5px solid;
    border-bottom-color: black;
    width:120px;
    
  }
  
  .info {
    display: flex;
    justify-content: space-between;
  }
  
  .education{
    margin-top: 1em;
    color: black;
 
  }
  
