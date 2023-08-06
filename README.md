# Dabotics
Welcome to the official GitHub repository for my Web Development Internship at Dabotics India Pvt. Ltd. in 2023. This repository showcases my passion for web development and houses a collection of projects that highlight my skills, knowledge, and creativity in this field.


Documentation explaining design choices and instructions

The provided HTML code represents a web page that consists of different sections such as Home, 
About, Services, Portfolio, and Contact. It also includes a style switcher for changing the theme colors 
of the website. Let's go through the different parts of the code and their functionalities:

<!DOCTYPE html>: This declaration specifies the document type and version of the HTML used in the 
page.
<html lang="en">: The <html> element is the root element of the HTML document. The lang 
attribute indicates the language of the page, which is set to English ("en") in this case.
<head>: The head element contains metadata about the document, such as the character encoding, 
viewport settings, title, and links to external resources.
<meta charset="UTF-8">: This meta tag sets the character encoding of the document to UTF-8, which 
supports a wide range of characters and symbols.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: This meta tag sets the 
viewport settings for better responsiveness on different devices. The width=device-width ensures 
that the website adapts to the width of the device, and initial-scale=1.0 sets the initial zoom level.
<title>Document</title>: This element sets the title of the web page, which appears on the browser's 
tab.
CSS and Font Awesome Links: Several external CSS files and Font Awesome library are linked to the 
page. These files provide styles, icons, and color schemes for the website.
<body>: The body element contains the visible content of the web page.
<div class="main-container">: This is the main container that wraps the entire content of the page.
Sidebar Section (<div class="aside">): This section represents the sidebar that contains the logo and 
navigation menu.
Navigation Menu (<ul class="nav">): The navigation menu consists of links to different sections of the 
website such as Home, About, Services, Portfolio, and Contact.
Main Content Section (<div class="main-content">): This section contains all the main content of the 
website, including the Home, About, Services, Portfolio, and Contact sections.
Sections: Each section (e.g., Home, About, Services, Portfolio, and Contact) is represented by a 
<section> element with a unique id attribute.
Styling and Content: Various content elements such as headings (<h3>, <h4>, <h5>), paragraphs 
(<p>), images (<img>), and icons (<i>) are used to create the content and structure of the sections.
Progress Bars: The progress bars in the "About" section represent the skills in JS, PHP, HTML, and 
Bootstrap.
Timeline: The "Education" and "Experience" sections include timelines with descriptions of past 
educational and work experiences.
Contact Form: The "Contact Me" section contains a contact form with fields for name, email, subject, 
and message.
Style Switcher: The style switcher is a hidden section (<div class="style-switcher">) that allows users 
to change the theme colors of the website.
JavaScript: Two JavaScript files (script.js and style-switcher.js) are linked at the bottom to provide 
interactivity and functionality to the web page.
  
Overall Design:
The design is responsive and appears to be a one-page portfolio website for a web designer named 
Tannu Singh. The website is designed to be visually appealing, and it showcases the individual's skills, 
experiences, and contact information. The style switcher feature allows users to change the color 
theme of the website.

  
CSS DESIGN 

Importing Fonts:
The code imports two font families from Google Fonts: 'Clicker Script' and 'Poppins' with various font 
weights.
CSS Variables:
The code defines several custom CSS variables using the :root selector to store color values.
Body Styling:
General styling for the body element, setting line-height, font-size, and font-family to 'Poppins'.
Global Reset:
Universal reset styles to remove margins, padding, outlines, text decorations, and set box-sizing to 
'border-box'.
Section Styling:
Styles for the .section class, which represents a full-width section with background colors, fixed 
position, and transitions.
Hidden Class:
A utility class .hidden to hide an element with display: none !important.
Padding Class:
A utility class .padd-15 to add padding to the left and right of an element.
Container Styling:
Styles for a .container class, setting a maximum width and centering it.
Section Title Styling:
Styles for .section-title and its child heading elements, including font size, color, and positioning.
Row Styling:
Styles for .row class, which represents a flex container for arranging items in a row with margins.
Button Styling:
Styles for .btn class, creating a styled button with background color and hover effects.
Box Shadow:
A utility class .shadow-dark to add a box shadow with specific color and spread.
Aside Styling:
Styles for .aside, a fixed sidebar with a logo and navigation menu.
Home Section Styling:
Styles for the home section with a background image and text content.
About Section Styling:
Styles for the about section with personal information, skills, education, and experience.
Service Section Styling:
Styles for the service section with icons and content.
Portfolio Section Styling:
Styles for the portfolio section with images and content.
Contact Section Styling:
Styles for the contact section with contact form and information.
Media Queries:
Media queries for responsive design, adjusting layout and elements for different screen sizes.

Overall, the CSS code defines a cohesive styling system for different sections of a website, providing 
consistent font choices, color schemes, and responsive design for optimal viewing on various devices. 
The code leverages CSS variables for easy color theme changes, and it includes utility classes for 
quick modifications. The design appears to be clean and modern, with attention to detail in 
typography and layout.
