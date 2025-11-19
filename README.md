# ST10491015_WEDE5020_PART3
1. Part 3 Overview

In Part 3, the website was upgraded with the use of JavaScript-powered interactivity, form validation, SEO optimisation, and external service integration.
The following key functional features were added:

JAVASCRIPT INTERACTIVE FEATURES

Contact form with real-time validation
Success overlay modal
AJAX POST submission using Formspree API
Fallback to mailto email when network/API fails
Improved Help page tab interaction
Smooth scrolling and basic DOM enhancements

SEO BEST PRACTICES

Added <title> + <meta description> to all pages
Added alt text for all images
Improved internal linking structure
Clean URL structure maintained
Mobile-friendly layout (from Part 2) improved
Added robots.txt
Added sitemap.xml
Optimised heading structure (H1 → H2 → H3)

EXTERNAL SERVICES

Google Maps embeds on the Locations section
Formspree integration for Contact Form
Optional email fallback

FORMS

contact.html fully implemented
JavaScript client-side validation
Success modal
Formspree email sending
Styled with CSS
Error-handling with inline messages

2. JavaScript Functionality Added
2.1 Contact Form Enhancements

A complete JavaScript module was created to handle:

Feature	Description
Input validation : Checks email, name, minimum characters, required fields
Error messages : User-friendly inline errors
Loading state	: Custom “Sending…” indicator
AJAX submission :	Sends to Formspree endpoint via Fetch API
Success modal :	Overlay UI confirming successful message
Fallback method	: If submission fails, opens user’s email client with prefilled message

I created a new Formspree endpoint:
https://formspree.io/f/mwpyvnbg

2.2 Help Page Tabs

Improved click handling
Activated panels now toggle correctly
Added ARIA attributes for accessibility

2.3 Misc JavaScript Enhancements

Year auto-updates dynamically in footer
Navigation states improved
Buttons and interactive elements optimised for keyboard access

3. SEO Optimisation Implemented
3.1 On-Page SEO

Every page now has:
Correct <title>
Unique <meta name="description">
Proper <h1> heading structure

Added alt text to all images
Improved semantic HTML (sections, landmarks, aria-labels)

3.2 Robots File

A new robots.txt was added:

User-agent: *
Allow: /
Sitemap: https://your-domain.com/sitemap.xml

3.3 Sitemap File

A basic XML sitemap was added:

<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url><loc>https://your-domain.com/index.html</loc></url>
  <url><loc>https://your-domain.com/shop.html</loc></url>
  <url><loc>https://your-domain.com/discover.html</loc></url>
  <url><loc>https://your-domain.com/about.html</loc></url>
  <url><loc>https://your-domain.com/help.html</loc></url>
  <url><loc>https://your-domain.com/contact.html</loc></url>
</urlset>


3.4 Image Optimisation

Renamed images to descriptive filenames
Added alt="" attributes
Ensured all images load responsively

4. Forms (Enquiry + Contact)
 contact.html

Fully rebuilt and implemented with:
Name, email, message-type, subject, message fields
Formspree integration
JavaScript validation
Success popup overlay
Error messages
Styled input fields

help.html "Contact" tab

Updated to match new form structure
Works with the same validation system
More compact layout for contextual support

5. External Services Integrated
Service	Purpose
Google Maps iFrame :	Store locations (Cape Town, Johannesburg, Durban)
Formspree	: Email handling for Contact Form
Mailto Fallback :	Ensures email works even without internet

6. GitHub Repository Update Check

All required updates have been committed in separate commits with descriptive messages, such as:

Added contact form with JS validation and Formspree integration
Improved SEO meta tags and alt attributes
Added robots.txt and sitemap.xml
Updated navigation across site
Fixed tab functionality in help page
Added overlay success modal for forms


9. References

W3C HTML & CSS guidelines
MDN Web Docs — HTML, CSS Grid, JavaScript
Formspree.io documentation
Google Maps Embed documentation
Lighthouse SEO guidelines
