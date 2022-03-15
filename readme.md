
# Hiking In Switzerland
Hiking In Switzerland is a website where young and old can get some information about hiking in Switzerland and sign up for guided hikes.

This site is aimed at people who are looking for guided hiking tours throughout Switzerland. Users will find details of where and when to meet, what equipment they need, a sign-up form and contact information.

![Screenshot of the website on several screen sizes](assets/images/screenshot_responsivedesign.PNG?raw=true)

## Features
---

### - Navigation
- Is located at the top of the page and contains on the left side the name of the website as a logo, which is linked to the top of the page.
- On the right side you will find 3 more navigation links (Discover, Join Us and Contact) which lead to different sections of the page.
- The navigation is in a font that is softly curved and in black so that it stands out well from the background.
- The navigation clearly shows the name of the page and makes the individual sections easy to find.

![Screenshot of the header](assets/images/screenshot_nav.PNG?raw=true)

### - Heading
- The heading consists of 2 parts, one directly under the hero image and the second after the 3 text sections.
- It  clearly shows what this page is for and to whom this page is addressed.

![Screenshot of heading1](assets/images/screenshot_heading1.PNG?raw=true)
![Screenshot of heading2](assets/images/screenshot_heading2.PNG?raw=true)

### - Discover Section
- The Discover section is the main section of the site. It informs the user what we offer, what is needed, and gives exact meeting points and times.
- The upper part informs the users about: Hiking in summer, hiking in winter and that we offer guided tours for free.
- The lower part contains detailed information about where we meet, at what time and what equipment is needed.

![Screenshot of discover section](assets/images/screenshot_discover.PNG?raw=true)

### - Join Us Section
- The join us section has a form where users who want to join our guided hiking tours can sign up.
- The form collects: First name, last name and email address of the user.
- The feature is valuable because it allows you to register for the guided hiking tours.

![Screenshot of join us section](assets/images/screenshot_joinus.PNG?raw=true)

### - Contact Section
- The contact section encourages the user to get in touch with us.
- The contact section contains phone number and email address.
- Below you will find icons which lead to our social media channels from: Facebook, Instagram and Twitter.
- The contact section is valuable for the user as it offers the possibility to contact us on demand.

![Screenshot of contact section](assets/images/screenshot_contact.PNG?raw=true)

## Testing
---

- I tested that this page work in different browsers: Chrome Firefox & Microsoft Edge.
- I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the DevTools device toolbar.
- I confirmed that the navigation, header, discover, join us and contact text are all rideable and easy to understand.
- I confirmed that the form works. It requires entries in every field, will only accept an email in the email field, and the submit button works.

### Bugs

- Unsolved

In Chrome & Microsoft Edge, in the Discover section, no bullet points appear in the list. I tried to fix via list-style-type and used DevTools to check where it could come from, but no success. 

- Solved

I wanted the headings of the 3 divs (class: discover-switzerland-outer)I have aligned with display: inline-block; to appear in a horizontal line. Depending on how many lines the content of the paragraphs extends to, the headings appeared at different heights. I tried to fix this via min-height, but to no avail. In the end, vertical-align: top; solved the problem.

### Validator Testing

- HTML

The warning can be ignored, as no heading is required for this section.

![Screenshot HTML Validator](assets/images/screenshot_html_val.PNG?raw=true)

- CSS

![Screenshot CSS Validator](assets/images/screenshot_css_val.PNG?raw=true)

- Accessibility

I confirmed that the colors and fonts chosen are easy to read and accessible by running lighthouse in DevTools.

![Screenshot lighthouse, DevTools](assets/images/screenshot_lighthouse.PNG?raw=true)

## Deployment
---

The site was deployed to GitHub pages. The steps to deploy are:
- In the GitHub repository, navigate to the Settings tab.
- From the source section drop-down menu, select the Master Branch.
- Once the Master Branch has been selected, the page provided the link to the completed website.

The live link ca be found here - [Hiking In Switzerland](https://lucanoah.github.io/Portfolio-Project-1/)

## Credits
---

The hero image was taken from here - [Pexels](https://www.pexels.com/)
