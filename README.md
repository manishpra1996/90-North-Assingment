# Responsive Webpage

This project is a responsive webpage created using HTML, CSS, and JavaScript. It includes a fixed navbar, collapsible left menu, main content area, right-side panel, and a footer. The page dynamically adjusts its layout and scale based on the screen width for an optimal user experience.

Features

Fixed Navbar: A navigation bar at the top of the page that remains fixed during scrolling.

Three Main Sections:

Left Menu: Collapsible menu with a toggle button.

Main Content Area: The central section for displaying primary content.

Right-Side Panel: Additional content or widgets.

Footer: A footer at the bottom of the page that remains consistent across all screen sizes.

Responsive Scaling:

Shrinks the page dynamically based on the screen width.

Scaling rules:

992px to 1600px: Page shrinks to 90%.

700px to 767px: Page shrinks to 80%.

600px to 700px: Page shrinks to 75%.

<=600px: Page shrinks to 50%.

File Structure

index.html: Main HTML file containing the structure of the webpage.

Inline CSS: Styles are included within the <style> tag in the head section of the HTML file.

Inline JavaScript: Functions for interactivity and responsiveness are included within the <script> tag at the bottom of the HTML file.

How to Use

Clone or download this repository to your local machine.

Open the index.html file in any modern web browser.

Resize the browser window to observe the responsive behavior of the page.

JavaScript Functionality

toggleMenu()

Collapses or expands the left menu when the toggle button is clicked.

adjustPageScale()

Dynamically adjusts the page scale based on the screen width.

Automatically triggered on page load and window resize.

Compatibility

Tested on modern browsers including Chrome, Firefox, Edge, and Safari.

Fully responsive for desktop, tablet, and mobile devices.
