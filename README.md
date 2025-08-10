**Personal Portfolio Website**
=======================================

**1\. Project Overview**
------------------------

This project is a two-page personal portfolio website designed to serve as a professional introduction. It consists of a main **Biography Page** that details the subject's personal and academic journey, and a **Contact Page** that provides a functional form for professional inquiries.

The website is built with modern HTML and CSS, featuring a clean, responsive design and a touch of interactive JavaScript to create an engaging user experience.

**2\. Pages and Functionality**
-------------------------------

The project is composed of two primary HTML files:

### **2.1. Biography Page (`index.html`)**

This is the main landing page of the portfolio.

-   **Content**: It presents a detailed biography of Guilherme Oliveira Araujo, covering his personal background, academic achievements in various Olympiads, and future career aspirations in Systems Development.

-   **Layout**: The page uses a modern, single-column layout with a distinct header, a profile image, and well-structured text content. It is fully responsive and adapts to different screen sizes.

-   **Interactive Feature**: A unique "Activate Gravity" button is located at the bottom-left corner. When clicked, it triggers a JavaScript animation that applies a simulated gravitational pull to the profile image, causing it to fall off the screen.

### **2.2. Contact Page (`index2.html`)**

This page provides a direct line of communication.

-   **Functionality**: It features a clean and user-friendly contact form that allows visitors to send a message. The form is designed for professional contact and includes fields for a name/company, email address, and a message.

-   **Navigation**: A "Back" button allows for easy navigation to the main biography page.

-   **Links**: The footer includes direct links to the subject's GitHub profile and email address.

**3\. Technical Implementation**
--------------------------------

-   **Structure**: The project is built entirely with **HTML5** and styled using **CSS3**. The layout avoids outdated practices like `<table>` for structure, instead opting for modern CSS techniques.

-   **Styling**:

    -   CSS is embedded directly within the `<style>` tags in each HTML file.

    -   The design is responsive, utilizing **Flexbox** for content alignment and **`@media` queries** to ensure optimal viewing on both desktop and mobile devices.

    -   Visual enhancements include `box-shadow` for depth, `border-radius` for soft edges, and `transition` effects for smooth button interactions.

-   **JavaScript**:

    -   The biography page includes a small, self-contained script to handle the "gravity" animation.

    -   It uses `requestAnimationFrame` for a smooth and efficient animation loop, which is more performant than older methods like `setInterval`.

**4\. File Structure**
----------------------

The project is organized as follows:

```
/
|-- index.html       (The main Biography Page)
|-- index2.html      (The Contact Form Page)
|-- img/
|   |-- ... (All image assets used on the pages)

```

**5\. How to Use**
------------------

1.  Open the `index.html` file in any modern web browser to view the main biography.

2.  Click the "Where to Find Me" button at the bottom of the biography page to navigate to the contact form (`index2.html`).

3.  On the contact page, use the "Back" button to return to the biography.
