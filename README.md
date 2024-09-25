# FOODBLOG
This is a foodblog with Navigation that links to several of the pages section.
## Table of Contents
1. [About](#about)
2. [Feature](#feature)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## About
Foodie Haven is a multi-page food website that links to various sections (e.g., about, menu, contact, etc.), each on separate HTML files. The main page uses JavaScript to display an alert when a user visits and includes an image slider that loops through images every few seconds.
The website is designed to help users explore  food-related content with a simple, responsive and user-friendly layout.

## Feature
- JavaScript-powered welcome alert on the main page.
- Automatic image slider that loops through different images every few seconds.
- Easy navigation between different sections of the site via internal links to separate HTML files.

  # Main page features
- Alert Message: When you open the main page (index.html), a pop-up alert will appear saying "Welcome to Foodie Haven", welcoming users to the website.
- Image Slider: The main page features an automatic image slider that rotates through various food images in a loop. This is controlled by JavaScript and switches images every 3 seconds.

  # Folder structure:
  foodie-haven-website/
│
- ├── index.html          # Main page with alert and image slider
- ├── about.html        # about the page  section
- ├── menu.html           # Food menu section
- ├── contact.html        # Contact form section
- ├── styles.css          # Stylesheet for the website
- └── script.js           # JavaScript file for alert and image slider

## Usage
- The JavaScript code that powers the alert and image slider is located in the script.js file.
- The image slider uses the setTimeout function to loop through food-related images every 3 seconds, while the alert() function displays the welcome message.

   # Navigating to other sections:
- The website is split into multiple sections, each with its own HTML file (e.g., about.html, menu.html, contact.html).
- Users can navigate between these sections using the links in the navigation bar.
  ## Contributing
  Contributions are welcome! To contribute:

Fork the repository.
Create your feature branch
1. Fork the repository
   
2. Create your feature branch:
 - git checkout -b feature/amazing-feature
3. commit your changes:
 - git commit -m 'Add amazing feature'
4. Push to branch
    - git push origin feature/amazing-feature
5. Open a pull request.

  ## License
  This project is licensed under the MIT License. See the [LICENSE](https://github.com/marveeygoodlife/FOODBLOG/blob/main/LICENSE) file for details.


