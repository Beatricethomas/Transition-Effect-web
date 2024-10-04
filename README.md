# Transition-Effect-web

### AIM : 
Create a smooth transition effect from a white section to a black section using HTML, CSS

### Requirements: 
Visual Studio Core with necessary extensions to run webpage.

### Source Code : 
```
HTML


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Transition Effect</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="navbar">
        <h2> WEB DEVELOPMENT </h2>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">People</a>
        <a href="#">Contact Us</a>
        <br>
    </div>
    <p> A Web Development Course is an educational program designed to teach individuals how to design, develop, and maintain websites and web applications. 
        <br>
        <br>
     The course typically covers a broad range of topics, from the basic building blocks of the web (HTML, CSS, and JavaScript) to more advanced concepts like back-end development, databases, frameworks, and deployment.
    <br>
    <br>
    A Web Development Course equips students with the practical skills and knowledge necessary to build functional, scalable, and interactive websites and web applications. 
    <br>
    <br>
    The course content varies from basic HTML/CSS to more advanced topics like back-end frameworks and APIs, making it suitable for both beginners and those looking to advance their development careers.
    </p>  
         <h3> Front End Tools Used : </h3>
         <div class="container">
            <!--frst circle-->
            <div class="circle-container">
                <div class="circle">
                  <img src="c:\Users\dell\Pictures\Screenshots\Screenshot 2024-10-02 201157.png" alt="Image 1">
                </div>
                <p class="description">HTML is the standard language used to structure content on the web. <br><br> Each tag provides meaning to the content, such as defining headings, paragraphs, or sections. HTML is essential for creating the skeleton of a website, but it doesn't handle the styling or behavior. </p>
              </div>
          
              <!-- Second Circle -->
              <div class="circle-container">
                <div class="circle">
                  <img src="c:\Users\dell\Pictures\Screenshots\Screenshot 2024-10-02 201309.png" alt="Image 2">
                </div>
                <p class="description">CSS is a stylesheet language used to control the appearance of a website. <br><br>It allows developers to style HTML elements by defining properties like colors, fonts, margins, and positioning. CSS enables responsive designs, making sure the website looks good on various devices</p>
              </div>

              <!-- third Circle -->
              <div class="circle-container">
                <div class="circle">
                  <img src="c:\Users\dell\Pictures\Screenshots\Screenshot 2024-10-02 201331.png" alt="Image 2">
                </div>
                <p class="description">JavaScript is a programming language that adds interactivity to websites. <br> <br>It allows developers to create dynamic content, like animations, form validations, and real-time updates. <br><br>JavaScript interacts with HTML and CSS through the Document Object Model (DOM), enabling changes in web page content and styles without reloading the page.</p>
              </div>
         </div>
</body>
</html>

CSS

body 
{
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-color:rgb(231, 217, 197);
}
.h2
{
     background-color:white;
     padding : 15px;
     text-align:left  ;
     
}

.navbar {
    background-color:black; 
    padding: 15px;
    text-align: center;
    color:white
}

.navbar:hover {
    transition: 1s ease;
    background-color:blanchedalmond;
    color:black;
    text-decoration: wavy;

}
.navbar a {
    color:rgb(229, 96, 96);
    text-decoration: none;
    font-size: 18px;
    margin: 0 15px;
    font-weight: bold;
}

.navbar a:hover {
    text-decoration: underline;
    color:black;
}
p{
    text-align:justify;
    display:flex;
    color:whitesmoke;
    text-decoration:solid;
    background-color:black;
}
p:hover 
{
    background-color:antiquewhite;
    color : black;
    text-decoration: wavy;
    transition: 1s ease;

}

.h3{
    color: black;
    font-size: 15px;
}

.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px; /* Space between the two circles */
  }
  
  .circle-container {
    display: flex;
    margin: left;
    justify-content: center;
    transition: transform 0.5s ease;
  }
  
  .circle {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    display: flex;
    justify-content: left;
    align-items: center;
    background-color: black;
    transition: transform 0.5s ease;
  }
  
  .circle img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.5s ease;
  }
  
  .description {
    margin-left: 20px;
    font-size: 16px;
    background-color:antiquewhite;
    color:white;
    opacity: 0;
    max-width: 300px;
    transition: opacity 0.5s ease;
  }
  
  /* Hover effect */
  .circle-container:hover .circle {
    transform: scale(1.1); /* Enlarge the circle */
  }
  
  .circle-container:hover .description {
    background-color:black;
    color:white;
    opacity: 1; /* Make the description visible */
    border-radius: 3%;
  }
  
  .circle-container:hover img {
    transform: scale(1.0); /* Slight zoom on the image */
  }

```

### OUTPUT : 

[Transition web.webm](https://github.com/user-attachments/assets/1aeb30ab-80a5-4062-a517-eabe7aa4025f)

![Screenshot 2024-10-04 190332](https://github.com/user-attachments/assets/0e5b9a6d-3720-42d9-88e1-9fed188b0c76)

![Screenshot 2024-10-04 190402](https://github.com/user-attachments/assets/40704224-d5c5-4d76-b5dd-4c4763900154)




