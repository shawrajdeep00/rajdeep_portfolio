# Rajdeep Shaw - Portfolio Website

## Overview

Welcome to my professional portfolio, showcasing my expertise in Embedded Systems, IoT, and Software Development. This repository includes a responsive personal portfolio website that highlights my skills, experience, and recent projects. Built using modern web technologies like HTML5, CSS3, and JavaScript, this portfolio serves as an interactive platform for potential collaborators, employers, and clients to explore my work.

The portfolio is **hosted on Netlify**, ensuring fast load times and an optimized user experience across all devices.

### 🌐 Live Demo
You can view the live portfolio [here](https://shawportfolio.netlify.app/) on Netlify.

## Features

### 🖼️ Project Structure
This portfolio is composed of the following sections:
- **About Me**: A detailed introduction highlighting my background, education, and areas of expertise.
- **Experience**: A summary of my technical skills and experience in both software and hardware domains.
- **Projects**: A showcase of some of the most significant projects I’ve worked on, complete with links to GitHub repositories and live demos.
- **Contact**: A section for visitors to reach out to me directly via email or connect with me on LinkedIn.

---

## 💻 Technologies Used
This project leverages a combination of front-end technologies to deliver a responsive, interactive, and professional web portfolio.

- **HTML5**: The structure of the website, ensuring a clean and semantic layout.
- **CSS3**: Used for styling, including media queries to ensure the design is fully responsive across devices. Custom animations and transitions provide a smooth, polished user experience.
- **JavaScript**: Powers interactive elements like the hamburger menu for mobile navigation.
- **Netlify**: The portfolio is deployed and hosted on Netlify for optimal performance and accessibility.

### 🏗️ Detailed File Structure
The repository is structured as follows:

```bash
|-- assets/                   # Contains all images and icons used in the website
|   |-- profile-pic.png        # Profile picture for the About Me section
|   |-- linkedin.png           # LinkedIn icon for social links
|   |-- github.png             # GitHub icon for social links
|   |-- experience.png         # Icon for Experience section
|   |-- education.png          # Icon for Education section
|   |-- project-1.png          # Image for Project 1
|   |-- project-2.png          # Image for Project 2
|   |-- project-3.png          # Image for Project 3
|-- index.html                 # Main HTML file containing the website structure
|-- style.css                  # CSS file for global styles and section-specific styling
|-- mediaqueries.css           # Additional CSS for handling responsive design across different devices
|-- script.js                  # JavaScript file for interactive elements like the mobile menu
```

---

## 📚 Sections

### About Me
This section introduces who I am and highlights my background in **IoT**, **Embedded Systems**, and **AI**. It provides a professional overview of my skills, education, and professional objectives. Visitors can also download my CV directly from this section.

### Experience
In this section, I provide a breakdown of my key technical skills in both **Software Development** and **Embedded Systems**. This section is divided into two parts:
- **Software**: Showcases my proficiency in Python, JavaScript, HTML, CSS, SpringBoot, and MATLAB, among others.
- **Hardware**: Highlights my experience with IoT, FPGA programming, Digital Systems Design, and Verilog.

### Projects
This section features some of my recent work, which includes detailed descriptions, live demos, and links to their respective GitHub repositories. Key projects include:
1. **IoT-based ADAS Emergency Assistance System**  
   A system designed to enhance road safety using IoT technology and advanced driver assistance. [View GitHub Repository](https://github.com/shawrajdeep00/IoT_ADAS_system)

2. **K-Nearest Neighbors for Breast Cancer Classification**  
   A machine learning model built using the KNN algorithm to classify breast cancer data. [View GitHub Repository](https://github.com/shawrajdeep00/K-nearest-neighbour)

3. **UART Transmission using FPGA**  
   A project focused on serial communication via UART using FPGA programming. [View GitHub Repository](https://github.com/shawrajdeep00/UART-interfacing-with-FPGA)

### Contact
The contact section allows visitors to reach out via email or connect with me on LinkedIn. Social media icons provide quick access to my professional profiles.

---

## 🛠️ Technical Details

### Responsive Design
The portfolio is fully responsive and adapts seamlessly to devices of all sizes, from large desktop screens to mobile devices. This was achieved using **CSS media queries** found in `mediaqueries.css` to ensure the layout adjusts based on screen size.

Key design features include:
- **Dynamic Navigation**: A hamburger menu for mobile navigation, implemented with **JavaScript** to toggle the menu visibility.
- **Smooth Scrolling**: Enabled through the `scroll-behavior: smooth;` CSS property for a polished user experience.
- **Hover Effects and Transitions**: Custom hover effects on navigation links and buttons, providing visual feedback to users.

### JavaScript Functionality
The interactivity is powered by a small but efficient JavaScript function (`toggleMenu`) to manage the mobile navigation menu. This ensures the website is intuitive and easy to navigate, even on smaller screens.

```javascript
function toggleMenu() {
  const menu = document.querySelector(".menu-links");
  const icon = document.querySelector(".hamburger-icon");
  menu.classList.toggle("open");
  icon.classList.toggle("open");
}
```

---

## 🚀 Deployment
This portfolio is hosted on **Netlify**, a cloud-based platform that provides automated deployment and hosting for static websites. Netlify’s continuous deployment ensures that any changes made to the codebase are automatically reflected in the live site.

You can visit the live portfolio at: [Portfolio Hosted on Netlify](https://shawportfolio.netlify.app/)

---

## 📝 License
This project is open-source and available under the [MIT License]
```


