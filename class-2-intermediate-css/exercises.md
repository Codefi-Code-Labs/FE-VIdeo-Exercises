# Intermediate CSS Exercises

## Commit your Progress to Github

Every update you are proud to show off or accomplished is worth a commit even if it means it's not done!

## Exercise: FluidBiz Co. 
**Objective**: Create a responsive, fluid layout for a fictional business website. The website should contain a header, three columns (services, main content, testimonials), and a footer.

Instructions:
Setup: Create a new folder named fluid-layout-exercise. Inside this folder, create two files: index.html and styles.css.

HTML Structure: Open index.html in VS Code and add the following elements:

A `<header>` with the title "FluidBiz Co." and a navigation bar containing links: Home, Services, Testimonials, and Contact.
Three `<div>` elements with the classes .services, .main-content, and .testimonials.
A `<footer>` mentioning "Copyright © 2023 FluidBiz Co."
Basic Styling: Link your styles.css in your HTML. Set a basic style:

Set a background color for the body and different background colors for the header, columns, and footer to distinguish them.
Fluid Layout:

Set the width of the .services and .testimonials columns to 25% and the .main-content to 50%.
Float the .services to the left, .testimonials to the right, and .main-content to the left.
Ensure that the columns sit side by side.
Populate Content:

Inside the .services column, list down at least 3 fictional services offered by FluidBiz Co.
For the .main-content, write a brief introduction about FluidBiz Co. and what they specialize in.
In .testimonials, include 3 fictional testimonials from satisfied customers.
Responsiveness:

Ensure your layout is fluid. Test by resizing your browser window.
Bonus: Add media queries to stack the columns vertically when the screen width goes below 768px.
Review:

Make sure there's no horizontal scrollbar at any screen size.

**Tips**:
Remember to clear floats after your columns to prevent layout issues.
Ensure proper content hierarchy with the use of `<h1>`, `<h2>`, and so on.
If you finish early, enhance your design by adding images, hover effects, or any other additional styling.


---

## Exercise: Responsive Website with Media Queries
**Objective**: Build a fictional online portfolio website that's responsive using media queries. The portfolio should display differently on desktop, tablet, and mobile devices.

**Instructions**:
Setup: Create a new folder named media-query-exercise. Inside this folder, create two files: index.html and styles.css.

HTML Structure:

A `<header>` with the title "John Doe's Portfolio" and a navigation bar with links: About, Projects, and Contact.
Three `<section>` elements with the classes .about, .projects, and .contact.
A `<footer>` mentioning "© 2023 John Doe".
Basic Styling: Link your styles.css in your HTML. Add base styles:

Use a clean, readable font from Fonts.
Define a pleasant color scheme for your site.
Style the header, sections, and footer with padding and margins for a clean look.
Desktop Layout:

By default (for desktops/large screens):
.about and .contact sections should take up 25% of the container's width and float to the left and right respectively.
.projects section should take up 50% of the container's width and float in the middle.
Populate Content:

Inside the .about section, include a short biography and a profile picture.
For the .projects, list down at least 3 fictional projects with images and brief descriptions.
In the .contact section, place fictional contact details or a contact form.
Media Queries:

For tablets (screen widths from 481px to 768px):
Change the .about and .contact sections to occupy 33% of the container's width.
The .projects section should now be 34% wide.
For mobile devices (screen widths up to 480px):
Each section should occupy 100% of the container's width and should stack on top of one another.
Test:

View your website in a browser and adjust the screen size to see how your media queries alter the layout.

**Tips**:
Clear floats after sections to avoid layout breakages.
Ensure that images are responsive, using max-width: 100% and height: auto.
For added challenge, make the navigation bar responsive too – maybe converting it into a dropdown for mobile devices.

---

## Exercise: Building a Flexbox Photo Gallery
**Objective**: Design a responsive photo gallery utilizing Flexbox to ensure an adaptive layout across various screen sizes.

**Instructions**:
Setup: Create a new folder called flexbox-exercise. Within this folder, establish two files: index.html and styles.css.

HTML Structure: In index.html, set up the following:

A `<header>` with the title "Flexbox Photo Gallery".
A `<main>` section with a class of .gallery.
Inside the .gallery, insert nine `<div>` elements with the class .photo-card. Each .photo-card should contain:
An `<img>` displaying a photo of your choice.
A `<h3>` with a fictional photo title.
A `<p>` with a short description of the photo.
Base Styling: Link your styles.css to your HTML. Implement the following basic styles:

A cohesive color palette.
Margins and padding for a polished appearance.
A universal font from Google Fonts for consistency.
Flexbox Implementation:

Convert .gallery into a Flex container.
By default, .photo-card elements should be displayed in a row format. Allow wrapping so they can shift to a new line if there's not enough space.
Space out the .photo-card elements evenly and align them to the center of the .gallery container.
Responsive Design:

On wider screens (greater than 900px): Display the .photo-card elements in three rows, each row containing three photos.
On medium screens (between 600px and 900px): Display the .photo-card elements in three rows, each row containing two photos and the last row containing just one photo.
On smaller screens (less than 600px): Display each .photo-card in its row.
Extra Features (for added challenge):

Make the photos grow slightly when hovered upon.
Implement a quick transition effect for hover effects.
Display the .photo-card details (title and description) in a neat overlay when the photo is hovered upon.
Test:

View your gallery in different browsers and adjust the screen size to verify that the Flexbox layout is responsive.
Optionally, try using browser dev tools to emulate various devices.

**Tips**:
Remember to use flex-wrap: wrap on the .gallery to ensure .photo-card elements can break onto the next line.
Use flex: 1 on .photo-card elements to make them grow and occupy available space.
To enhance the challenge, consider introducing nested Flex containers within the .photo-card for the title, image, and description layout.