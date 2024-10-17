# MyGym Fitness Website

## Overview

MyGym is a fully responsive fitness center website that provides users with information about the gym, training classes, schedules, and membership options. The website offers an intuitive user interface, making it easy for users to navigate between sections, sign up for classes, and contact the gym.

## Features

- **Responsive Design**: Compatible across devices (desktop, tablet, mobile).
- **Smooth Scrolling**: All page sections are linked using smooth scrolling for a better user experience.
- **Class Information**: Lists various training classes offered by MyGym along with schedules.
- **Contact Form**: A simple contact form to get in touch with the gym.
- **Social Media Integration**: Links to social media profiles.
- **Membership Option**: Users can sign up for a membership through a pop-up modal.

## Technologies Used

- **HTML5**: For structuring the website content.
- **CSS3**: For styling the website, including animations and responsiveness.
  - Bootstrap: Utilized for layout and responsive grid system.
  - Font Awesome: Icons for social media and other UI elements.
  - AOS (Animate On Scroll): Adds scroll animations.
- **JavaScript**: For interactivity such as smooth scrolling and handling the contact form.
- **jQuery**: Simplifies DOM manipulation and event handling.
  
## Project Structure

/mygym-fitness/
│
├── /css/                     # Folder for stylesheets
│   ├── bootstrap.min.css      # Bootstrap CSS
│   ├── font-awesome.min.css   # Font Awesome CSS for icons
│   ├── aos.css                # Animate On Scroll CSS
│   └── main.css               # Custom CSS for the site
│
├── /images/                   # Folder for images
│   ├── /class/                # Images for classes
│   ├── /team/                 # Images for team members
│   ├── yoga-class.jpg         # Example class images
│   ├── crossfit-class.jpg     # Example class images
│   └── cardio-class.jpg       # Example class images
│
├── /js/                       # Folder for JavaScript files
│   ├── aos.js                 # Animate On Scroll JavaScript
│   ├── bootstrap.min.js       # Bootstrap JS
│   └── main.js                # Custom JavaScript
│
├── /fonts/                    # Folder for custom fonts (optional)
│
├── index.html                 # Main homepage
├── about.html                 # About page (if separate)
├── contact.html               # Contact page (if separate)
└── README.md                  # Project readme file
