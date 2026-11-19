Kokan Bakes Website

A responsive website for a neighbourhood bakery in Vashi, Navi Mumbai, built with plain HTML, CSS and JavaScript. Customers can see if the shop is open, browse the menu and place an order on WhatsApp.

Screenshot of the Kokan Bakes homepage
<img width="1366" height="768" alt="bakes" src="https://github.com/user-attachments/assets/cb666eb3-9fe2-4ff7-b760-95600412c5b8" />


Features
Live open/closed status: JavaScript checks the current day and time and shows "Open now" or "Closed" with the weekly hours.\

Menu with filters: items are stored in a JavaScript list and can be filtered by Bread, Cakes and Snacks.

Order form: validates the name, Indian mobile number and message, then opens WhatsApp with the order filled in. No server needed.

Responsive design: works on mobile, tablet and desktop, with a mobile navigation menu.

SEO setup: page title, meta description and LocalBusiness structured data (JSON-LD) so search engines can understand the business.

Accessibility: keyboard focus styles, labelled form fields, error messages, and reduced-motion support.

Tech stack
HTML5
CSS3 (Grid, Flexbox, custom properties)
Vanilla JavaScript (no libraries)
Google Fonts, Google Maps embed
Run it locally

Download or clone this repository:
git clone 
Open index.html in your browser.
Customize it for another business
Search index.html for EDIT and update the name, address, phone and email.
In the script section, change WHATSAPP_NUMBER, HOURS and the MENU list.
Put your product photos in the images folder, using the file names in the MENU list.
Replace the Google Maps link with your own embed link.
Performance

Lighthouse scores (mobile):
Performance	Accessibility	Best Practices	SEO
add score	add score	add score	add score

What I learned
Building a page from data in JavaScript instead of hard-coding every card.
Form validation and passing data to WhatsApp using a URL.
Adding structured data and meta tags for local SEO.
Author

Alisha Khot 
