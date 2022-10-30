# Mobile Physio - Testing

![Mobile Physio Site on multiple devices](/assets/images/README/response-design.png)

![GitHub last commit](https://img.shields.io/github/last-commit/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/CallumDennisIE/mobile-physio?style=for-the-badge)

[View the live project here.](https://callumdennisie.github.io/mobile-physio/)

[View the project README here.](README.md)

## Contents
* [Automated Testing](#automated-testing)
    * [W3C Validator](#w3c-validator)
    * [Lighthouse](#lighthouse)
    * [WAVE](#wave)
* [Manual Testing](#manual-testing)
    * [User Stories Testing](#user-stories-testing)
    * [Full Testing](#full-testing)
* [Bugs](#bugs)
    * [Known Bugs](#known-bugs)
    * [Full Bugs](#solved-bugs)

## Automated Testing:
### W3C Validator
The [W3C Validator](https://validator.w3.org/) was used to validate all HTML files used in the project. The results are shown below:

* 404.html - No errors or warnings to show.
* contact.html - No errors or warnings to show.
* index.html - No errors or warnings to show.
* submit.html - No errors or warnings to show.
* testimonial.html - No errors or warnings to show.

The [W3C Jigsaw Validator](https://jigsaw.w3.org/css-validator/) was used to validate the CSS file used in the project. The result is below:

* style.css - No Error Found.

### Lighthouse
The Chrome Developer Tool Lighthouse was used to test the following factors across the project: performance, accessibility, best practices and SEO.

#### Desktop Results:
About Page Results:

![Lighthouse About Page Results](/assets/images/TESTING/lighthouse-about-desktop.png)

Contact Page Results:

![Lighthouse Contact Page Results](/assets/images/TESTING/lighthouse-contact-desktop.png)

Testimonial Page Results:

![Lighthouse Testimonial Page Results](/assets/images/TESTING/lighthouse-testimonial-desktop.png)

Submit Page Results:

![Lighthouse Submit Page Results](/assets/images/TESTING/lighthouse-submit-desktop.png)

Custom 404 Page Results:

![Lighthouse Custom 404 Page Results](/assets/images/TESTING/lighthouse-404-desktop.png)

***
#### Mobile Results:
About Page Results:

![Lighthouse About Page Results](/assets/images/TESTING/lighthouse-about-mobile.png)

Contact Page Results:

![Lighthouse Contact Page Results](/assets/images/TESTING/lighthouse-contact-mobile.png)

Testimonial Page Results:

![Lighthouse Testimonial Page Results](/assets/images/TESTING/lighthouse-testimonial-mobile.png)

Submit Page Results:

![Lighthouse Submit Page Results](/assets/images/TESTING/lighthouse-submit-mobile.png)

Custom 404 Page Results:

![Lighthouse Custom 404 Page Results](/assets/images/TESTING/lighthouse-404-mobile.png)

### WAVE
The WAVE web accessibility evaluation tool was used on each of the pages of the project. The results are below:

About Page Results:

![WAVE About Page Results](/assets/images/TESTING/wave-about.png)

Contact Page Results:

![WAVE Contact Page Results](/assets/images/TESTING/wave-contact.png)

Testimonial Page Results:

![WAVE Testimonial Page Results](/assets/images/TESTING/wave-testimonial.png)

Submit Page Results:

![WAVE Submit Page Results](/assets/images/TESTING/wave-submit.png)

Custom 404 Page Results:

![WAVE Custom 404 Page Results](/assets/images/TESTING/wave-404.png)

[Back to top!](#mobile-physio---testing)

## Manual Testing:
### User Stories Testing
#### Goals of a First-Time Visitor:
| Goal          | Implementation      |
|:-------------|:-------------|
| As a first-time visitor, I want to know what Mobile Physio is and the services they provide.| The 'About' page is the landing page, meaning it is the first page a new user will see when they visit the Mobile Physio site.  The 'About' page contains text in the 'Who We Are' section describing the Mobile Physio company. The 'Hero-Image' also shows a Physiotherapist working on a patient, allowing a new user to visually understand the actions performed by Mobile Physio. The Service Cards each show one of the three services performed by Mobile Physio, with a description below the image, to allow the user to know what the services are.
| As a first-time visitor, I want to be able to easily navigate through the site.| The 'Navbar' allows for easy navigation of the site, the page title links back to the 'About' page and the navigation links allow the user to navigate to the 'About', 'Contact' and 'Testimonials' pages. The about page also contains a button that links to the 'Contact' page, allowing the user to easily book an appointment. Also, the 'Custom 404' and 'Form Submit' page contain a back button, allowing the user to return to their previously visited site.

***
#### Goals of a Returning Visitor:
| Goal          | Implementation      |
|:-------------|:-------------|
| As a returning visitor, I want to be able to contact Mobile Physio. | A user can contact Mobile Physio on the 'Contact' page. The 'Talk to Us' section contains the following details: address, email address, phone number and opening hours. These allow the user to have multiple ways to contact Mobile Physio.
| As a returning visitor, I want to be able to navigate to Mobile Physio's Social Media pages. | A user looking to visit the Mobile Physio social media pages, can use the Footer. The footer is located on all pages on the website. The Footer uses Font Awesome Icons for each of the links, these icons are the logos of the social media sites. The social media sites are Facebook, Instagram and Twitter.

***
#### Goals of a Frequent Visitor:
| Goal          | Implementation      |
|:-------------|:-------------|
| As a frequent visitor, I want to be able to book an appointment with Mobile Physio. | The users can also book an appointment using the form, this form requires that the user inputs the following fields: first name, last name, email address, phone number, appointment type and date of appointment. The required fields are useful as they ensure that the user inputs all the necessary information and can be contacted by Mobile Physio if necessary.
| As a frequent visitor, I want to know that my booking was successfully submitted. | A user will know that their booking is submitted, this is because when the form is submitted the user is taken to the 'Form Submit' page. This page informs the user that the form has been successfully submitted. This page also allows the user to return to the form page.

### Full Testing
The devices used to test are:
- iPhone 11 Pro Max
- MacBook Air (M1, 2020) - 13.3-inch (2560 × 1600) Built-in Retina Display
- MacBook Air (M1, 2020) - 27-inch (2560 × 1440) Display

These tests have been performed on the following browsers:
- Google Chrome - Desktop
- Google Chrome - Mobile
- Safari -  Mobile

The following exceptions have been made to the tests:
- On mobile, the page title is not shown. Therefore, during the mobile tests, the page title results do not apply.
- On mobile, the hover effect is not possible, as the user has to tap on the screen. Therefore, during the mobile tests, the hover effect results do not apply.

#### General Testing
The general tests are performed on all of the pages on the site, as these features are present on every page.

| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Navbar | Page Title is clicked | User is linked to the About page | User is linked to the About page | Pass |
| Navbar | About link is clicked | User is linked to the About page | User is linked to the About page | Pass |
| Navbar | Testimonial link is clicked | User is linked to the Testimonial page | User is linked to the Testimonial page | Pass |
| Navbar | Contact link is clicked | User is linked to the Contact page | User is linked to the Contact page | Pass |
| Navbar | Page title is hovered over | Page title is underlined | Page title is underlined | Pass |
| Navbar | About link is hovered over | About link is underlined | About link is underlined | Pass |
| Navbar | Contact link is hovered over | Contact link is underlined | Contact link is underlined | Pass |
| Navbar | Testimonial link is hovered over | Testimonial link is underlined | Testimonial link is underlined | Pass |
| Footer | Instagram icon is clicked | https://www.instagram.com/ opens in a new tab | https://www.instagram.com/ opens in a new tab | Pass |
| Footer | Facebook icon is clicked | https://www.facebook.com/ opens in a new tab | https://www.facebook.com/ opens in a new tab | Pass |
| Footer | Twitter icon is clicked | https://twitter.com/ opens in a new tab | https://twitter.com/ opens in a new tab | Pass |
| Footer | Instagram icon is hovered over | Instagram icon is enlarged | Instagram icon is enlarged | Pass |
| Footer | Facebook icon is hovered over | Facebook icon is enlarged | Facebook icon is enlarged | Pass |
| Footer | Twitter icon is hovered over | Twitter icon is enlarged | Twitter icon is enlarged | Pass |

#### Custom 404 Page
| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Custom 404 URL | Non-existent page URL used | User is linked to the Custom 404 page | User is linked to the Custom 404 page | Pass |
| Custom 404 Back Button | Back button is clicked | User is linked to their previously visited page | User is linked to their previously visited page | Pass |
| Custom 404 Back Button | Back button is hovered over | Back button text and background changes colour and the button enlarges | Back button text and background changes colour and the button enlarges | Pass |

#### Form Submit Page
| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Form Submit Redirect |  Contact form is submitted | User is linked to Form Submit page | User is linked to Form Submit page | Pass |
| Form Submit Back Button | Back button is clicked | User is linked to their previously visited page | User is linked to their previously visited page | Pass |
| Form Submit Back Button | Back button is hovered over | Back button text and background changes colour and the button enlarges | Back button text and background changes colour and the button enlarges | Pass |

#### Testimonials Page
| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Testimonial Card | Testimonial card is hovered over | Testimonial card enlarges | Testimonial card enlarges | Pass |
| Testimonial Review Stars | Review stars are hovered over | Review stars move up | Review stars move up | Pass |

#### About Page
| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Hero Image | Compared Hero Image on mobile and desktop | Hero image changes when on mobile screen size | Hero image changes when on mobile screen size | Pass |
| Service Cards | Deep Tissue Massage card hovered over | Deep Tissue Massage card enlarges |Deep Tissue Massage card enlarges | Pass |
| Service Cards | Injury Rehabilitation card hovered over | Injury Rehabilitation card enlarges | Injury Rehabilitation card enlarges | Pass |
| Service Cards | Sports Massage card hovered over | Sports Massage card enlarges | Sports Massage card enlarges | Pass |
| Contact Button | Contact button is clicked | User is linked to the Contact page | User is linked to the Contact page | Pass |
| Contact Button | Contact button is hovered over | Contact button text and background changes colour and the button enlarges | Contact button text and background changes colour and the button enlarges | Pass |

#### Contact Page
| Feature | Action Tested  | Expected Outcome | Test Outcome | Grade |
|-------------|-------------|-----|-----|-----| 
| Form Validation | Form is submitted without first name | User is prompted to fill out first name field | User is prompted to fill out first name field | Pass |
| Form Validation | Form is submitted without last name | User is prompted to fill out last name field | User is prompted to fill out last name field | Pass |
| Form Validation | Form is submitted without email address | User is prompted to fill out email address field | User is prompted to fill out email address field | Pass |
| Form Validation | Form is submitted  with an invalid email address | User is prompted to use a valid email address | User is prompted to use a valid email address | Pass |
| Form Validation | Form is submitted without phone number | User is prompted to fill out phone number field | User is prompted to fill out phone number field | Pass |
| Form Validation | Form is submitted without date of birth field | Form submits successfully | Form submits successfully | Pass |
| Form Validation | User tries to select multiple appointment types | Only one appointment type is selected at once | Only one appointment type is selected at once | Pass |
| Form Validation | Form is submitted without selecting an appointment type | User is prompted to select one of the appointment types | User is prompted to select one of the appointment types | Pass |
| Form Validation | Form is submitted  without selecting an appointment date | User is prompted to enter an appointment date | User is prompted to enter an appointment date  | Pass |
| Form Validation | Form is submitted without additional information provided | Form submits successfully | Form submits successfully | Pass |
| Reset Form Button | The Reset form button is pressed | The form fields are cleared | The form fields are cleared | Pass |
| Submit Form Button | The Submit form button is pressed | The user is linked to the form Submit page, the form contents is added to the URL as a query string | The user is linked to the form Submit page, the form contents is added to the URL as a query string | Pass |

[Back to top!](#mobile-physio---testing)

## Bugs:
### Known Bugs
None

### Solved Bugs
#### About & Contact Page: Re-used ID's
The ID: `contact-container` was used twice in the code, on the about page and the contact page. As the contact page used a media breakpoint to change the flex-direction to row, this meant that the contact text on the About page was also merged into a single row.

<details>
<summary>Click for Image: Re-used IDs bug - Initial Browser Output</summary>

![Re-used IDs bug inital in the browser](/assets/images/TESTING/bug-reused-id-initial.png)

</details> 

<details>
<summary>Click for Image: Re-used IDs bug - Initial CSS Code</summary>

![Re-used IDs bug inital CSS](/assets/images/TESTING/bug-reused-id-initial-css.png)

</details>  

This was fixed by renaming the ID of the About page contact section to `about-contact-container`.

<details>
<summary>Click for Image: Re-used IDs bug - Fixed Browser Output</summary>

![Re-used IDs bug fixed in the browser](/assets/images/TESTING/bug-reused-id-fix.png)

</details> 

<details>
<summary>Click for Image: Re-used IDs bug - Fixed CSS Code</summary>

![Re-used IDs bug fixed CSS](/assets/images/TESTING/bug-reused-id-fix-css.png)

</details>  

[Back to top!](#mobile-physio---testing)