Features

Responsive navigation with hamburger menu for mobile
Profile section with image and introduction
About section with education, skills, and hobbies
Project gallery with images and descriptions
Resume download link
Contact form
Smooth scrolling navigation
Mobile-friendly design
Dark header and footer

Files

personal_port.html - Main page structure with all sections
personal_port.js - Navigation toggle functionality
personal_port.css - Styling and responsive layout

Sections
Home

Profile picture
Name and title
Brief introduction

About

Education details
Skills listing
Hobbies and interests

Projects

Project gallery with images
Project titles and descriptions
Add your own projects easily

Resume

Download button for resume PDF

Contact

Contact form with fields for name, email, subject, and message
Form submission handling

How to Use

Open personal_port.html in a web browser
Navigate through sections using the menu
On mobile, click the hamburger icon to toggle menu
Click links to jump to different sections
Download resume from the Resume section

Customization
Update Personal Information
Edit in personal_port.html:

Replace profile image path in the <img> tag
Update name, title, and introduction
Modify education, skills, and hobbies in the About section

Add Projects
In the Projects section, add new project divs:
html<div class="project">
  <img src="your-image-url.jpg" alt="Project Name" />
  <h3>Project Title</h3>
  <p>Project description here.</p>
</div>
Update Resume Link
Replace the resume path in the Resume section:
html<a href="path/to/your/resume.pdf" ...>
Change Colors
Edit in personal_port.css:
cssheader {
  background: #222;  /* Header color */
}

.resume-btn {
  background: #007bff;  /* Button color */
}
Modify Contact Form
Add form submission logic in personal_port.js or connect to a backend service.
Installation

Download all three files
Place them in the same folder
Update image paths and resume link to your local files
Open personal_port.html in any browser

Important Notes

Image Paths: Update the profile picture path from local path to either:

Relative path: images/profile.jpg
Online URL: https://example.com/image.jpg


Resume Path: Update resume path from local path to:

Relative path: files/resume.pdf
Or host it online


Contact Form: Currently, the form has no backend. To make it functional:

Add JavaScript to handle form submission
Connect to a backend service (PHP, Node.js, etc.)
Use services like Formspree or EmailJS



Browser Compatibility
Works on Chrome, Firefox, Safari, Edge, and Opera.
