Student Information

Name: Gosiame Moatshe

Student Number: ST10448523

Module: WEDE5020 — Web Development

Assignment: Part 3 — Functionality, Enhancement and Optimization

Project Title: Society for the Prevention of Cruelty to Animals (SPCA) Website
1. Website Overview

The SPCA website was developed to promote animal welfare and educate the public about adoption, volunteering, and donation opportunities.
It consists of multiple pages: Home, About, Adoption, Volunteer, Donate, Gallery, Resources, and Contact.

The site is built using:

HTML5 for structure

CSS3 for styling and responsiveness

JavaScript (main.js) for interactivity and validation

The design is responsive and accessible on desktop and mobile devices.

⚙️ 2. JavaScript Enhancements

JavaScript was used to add interactivity and functionality across the site:

Form Validation:
The contact form validates required fields, email format, and message length before submission. Invalid fields display error messages.

Lightbox Gallery:
The gallery allows users to click on images to view them in a modal overlay. Navigation arrows and keyboard controls are included.

Smooth Scroll and Navigation:
Buttons and links use smooth scrolling and highlight active menu sections.

File: /javascript/main.js

💬 3. Contact Form Functionality

Located on contact.html

Includes the following fields: Name, Email, Subject, and Message.

JavaScript ensures that no field is empty and that the email follows a valid format.

The form’s action is linked to process-contact.php, which stores messages in the /documents/messages.txt file for demonstration purposes.

✅ This satisfies the functional form requirement (client-side + server-side logic).

📸 4. Gallery and Media

gallery.html contains a photo gallery of animals available for adoption.

Each image opens in a lightbox when clicked.

Images are stored in the /images/ folder and can easily be replaced with real animal photos.

Alt attributes are used for accessibility and descriptive SEO.

✅ Meets the multimedia requirement.

🎨 5. Design and Layout

Consistent header and footer on all pages.

Uses CSS Grid and Flexbox for responsive layouts.

Color scheme: Blue and white — reflecting SPCA’s identity.

Fonts: Simple, readable sans-serif typography.

Navigation bar links all pages clearly.

File: /css/style.css

✅ Meets layout and accessibility requirements.

🔐 6. SEO and Accessibility Considerations

Although robots.txt and sitemap.xml were not included, SEO has been considered through:

Descriptive <title> and <meta name="description"> tags.

Use of alt text on all images.

Proper heading hierarchy (<h1>, <h2>, <h3>).

Mobile responsiveness (<meta name="viewport">).

✅ Meets minimum SEO requirements.

🔁 7. Version Control and Hosting

The project was managed using Git and uploaded to GitHub for version control and hosting.
Commit messages document each development stage (structure, styling, interactivity, optimization).

Example commits:

“Initial website structure created”

“Added gallery and lightbox feature”

“Implemented form validation and PHP handler”

“Finalized Part 3 documentation”

8. Change Log Summary

See the separate CHANGELOG.md file for detailed version notes.
Key updates:

v1.0: Basic HTML structure created

v1.1: CSS styling and layout added

v1.2: JavaScript interactivity and validation implemented

v1.3: Gallery lightbox completed

v1.4: Final optimization and documentation added
✅ Meets the version control and hosting requirement.

🧾 8. Change Log Summary
