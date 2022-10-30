# Mobile Physio

![Mobile Physio Site on multiple devices](/assets/images/README/response-design.png)

![GitHub last commit](https://img.shields.io/github/last-commit/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/CallumDennisIE/mobile-physio?style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/CallumDennisIE/mobile-physio?style=for-the-badge)

[View the live project here.](https://callumdennisie.github.io/mobile-physio/)

## Contents
* [About](#about)
* [User Experience](#user-experience)
    * [User Stories](#user-stories)
* [Design](#design)
    * [Colour Scheme](#colour-scheme)
    * [Typography](#typography)
    * [Imagery](#imagery)
    * [Wireframes](#wireframes)
* [Features](#features)
    * [Navber](#navbar)
    * [Footer](#footer)
    * [Custom 404 Page](#custom-404-page)
    * [Form Submit Page](#form-submit-page)
    * [Testimonials Page](#testimonials-page)
    * [About Page](#about-page)
    * [Contact Page](#contact-page)
* [Technologies Used](#technologies-used)
    * [Languages Used](#languages-used)
    * [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
* [Deployment & Local Development](#deployment--local-development)
    * [Deployment](#deployment)
    * [Local Development](#local-development)
* [Testing](#testing)
* [Credits](#credits)
    * [Code](#code)
    * [Media](#media)

## About
Mobile Physio is a site for a Dublin based Physiotherapy Clinic. The target audeince for this site are people with injuries looking for physiotherapy treaments to asssit in recovery. This site will allow users to see the services offered by Mobile Physio, allow them to read reviews from previous pateints and book an appointment.

[Back to top!](#mobile-physio)

## User Experience

### User Stories

#### Goals of a First Time Visitor:
* As a first time visitor, I want to know what Mobile Physio is and the services they provide.
* As a first time visitor, I want to be able to easily naviaget through the site.

#### Goals of a Returning Visitor:
* As a returning visitor, I want to be able to contact Mobile Physio.
* As a returning visitor, I want to be able to navigate to Mobile Physio's Social Media pages.

#### Goals of a Frequent Visitor:
* As a frequent visitor, I want to be able to book an appointment with Mobile Physio.
* As a frequent visitor, I want to know that my booking was successfully submited.

To view the testing of the User Stories, check the TESTING.md file, located [here](TESTING.md).

[Back to top!](#mobile-physio)

## Design

### Colour Scheme

The website uses mostly white and light grey colours, to create a clean and modern design. The blue colour (`#4EB7DA`) was taken from the blue tape used in the Hero Image, this creates a theme thorughout the project as reoccuring colours are used.

<details>
<summary>Click for Image: Colour Palette</summary>

![Coolors Colour Palette](/assets/images/README/design-colour-palette.png)

</details>

### Typography

### Imagery

### Wireframes

About Page Wireframes:
<details>
<summary>Click for Image: About Page - Mobile Wireframe</summary>

![About Page Mobile Wireframe](/assets/images/README/wireframe-about-mobile.png)

</details>

<details>
<summary>Click for Image: About Page - Desktop Wireframe</summary>

![About Page Mobile Wireframe](/assets/images/README/wireframe-about-desktop.png)

</details>

***
Testimonial Page Wireframes:
<details>
<summary>Click for Image: Testimonial Page - Mobile Wireframe</summary>

![Testimonial Page Mobile Wireframe](/assets/images/README/wireframe-testimonial-mobile.png)

</details>

<details>
<summary>Click for Image: Testimonial Page - Desktop Wireframe</summary>

![Testimonial Page Mobile Wireframe](/assets/images/README/wireframe-testimonial-desktop.png)

</details>

***
Contact Page Wireframes:
<details>
<summary>Click for Image: Contact Page - Mobile Wireframe</summary>

![Contact Page Mobile Wireframe](/assets/images/README/wireframe-contact-mobile.png)

</details>

<details>
<summary>Click for Image: Contact Page - Desktop Wireframe</summary>

![Contact Page Mobile Wireframe](/assets/images/README/wireframe-contact-desktop.png)

</details>

[Back to top!](#mobile-physio)

## Features
### Navbar:
Included on all pages throughout the website. Design is consistent on all pages to provde a consitent user experience.
Contains the Website title (which links to the index.html page) and links to the About, Testimonials and Contact Pages.

<details>
<summary>Click for Image: Navbar - Desktop</summary>

![Navbar displayed on the desktop](/assets/images/README/navbar-desktop.png)

</details>
     
On mobile devices, the page title is hidden to allow the navigation links to fit on the screen.

<details>
<summary>Click for Image: Navbar - Mobile</summary>

![Navbar displayed on a mobile device](/assets/images/README/navbar-mobile.png)

</details>

Website title and links are underlined when hovered over, this provides extra feedback to the user that these words are links.    
    
<details>
<summary>Click for Image: Navbar - Hover Effects</summary>

![Navbar with About page link underlined](/assets/images/README/navbar-ul-link.png)

![Navbar with Page title link underlined](/assets/images/README/navbar-ul-title.png)

</details>
        
***  
### Footer:
The footer is located at the bottom of each page. It contains social media links to Instagram, Facebook and Twitter.
The footer links open in a new tab, to allow the user to remain on the Mobile Physio site without having to navigate back through their search history.
Footer uses Font Awesome Icons that are widely recognisable with the associated Social Media sites.

<details>
<summary>Click for Image: Footer - Mobile</summary>

![Footer on a mobile device](/assets/images/README/footer-mobile.png)

</details>

<details>
<summary>Click for Image: Footer - Desktop</summary>

![Footer on a desktop device](/assets/images/README/footer-desktop.png)

</details>
        
Footer icons will enlarge when hovered over, allowing users to get feedback that these are links that can be clicked.

<details>
<summary>Click for Image: Footer - Hover</summary>

![Footer icon being enlarged when hovered over](/assets/images/README/footer-enlarge.png)

</details>

***  
### Custom 404 Page:
This page will display when a requested when the requested page is not able to be displayed. For example a user who navigates to 'https://callumdennisie.github.io/mobile-physio/help.html', will be connected to the custom 404 page, as help.html does not exist within this project.


<details>
<summary>Click for Image: Custom 404 - Mobile</summary>

![404 Page on a mobile device](/assets/images/README/404-mobile.png)

</details>

<details>
<summary>Click for Image: Custom 404 - Desktop</summary>

![404 Page on a desktop](/assets/images/README/404-desktop.png)

</details>

This custom page replaces the default GitHub Pages 404 page, the default page does not follow the theme of the other Mobile Physio page, which could disorientate users. The custom page also includes the nabar and footer elemnts, to allow the user to continue site navigation.

<details>
<summary>Click for Image: Default GitHub Pages 404 Page</summary>

![404 Page on a mobile device](/assets/images/README/404-default.png)

The custom 404 page also includes a 'Go Back' button which will return the user to the previous page in their history. Allowing the user to quickly and easily continue site navigation.

</details>

<details>
<summary>Click for Image: Custom 404 - Back Button</summary>

 ![404 Page back button](/assets/images/README/404-button.png)

</details>

***  
### Form Submit Page:
This page will display when the form has been successfully submited.
This provides the user feedback and informs them that the form has been successfully sent.

<details>
<summary>Click for Image: Form Submit - Desktop</summary>

![Form Submit Page on desktop](/assets/images/README/submit-desktop.png)

</details>

<details>
<summary>Click for Image: Form Submit - Mobile</summary>

![Form Submit Page on mobile](/assets/images/README/submit-mobile.png)

</details>

The page contains a back button, allowing the user to return to their previous page, which would be the contact page.

<details>
<summary>Click for Image: Form Submit - Back Button</summary>

![Form Submit back button](/assets/images/README/submit-button.png)

</details>

***  
### Testimonials Page:
This page shows reviews from previous pateints, creating trust between the user and the Mobile Physio company.

<details>
<summary>Click for Image: Testimonials - Desktop</summary>

![Testimonial page on desktop](/assets/images/README/testimonial-desktop.png)

</details>

<details>
<summary>Click for Image: Testimonials - Mobile</summary>

 ![Testimonial page on mobile](/assets/images/README/testimonial-mobile.png)

</details>
       
The individual review sections expand when hovered over, this highlights to the user the review that they are looking at.

<details>
<summary>Click for Image: Testimonials - Hover</summary>

![Testimonial items enlarging when hovered over](/assets/images/README/testimonial-hover.png)

</details>
        
The review stars also animate when hovered over, this makes the website appear more dynamic and less flat.

<details>
<summary>Click for Image: Testimonials Star - Hover</summary>

![Animation of review stars on testimonial page when hovered over](/assets/images/README/testimonial-star-hover.png)

</details>

***         
### About Page:
This page is intended as a landing page for users. It provides infomration about the Mobile Physiocompany and the services they provide.
A large hero image shows the user a physiotherpaist working on a patient, allowing them to understand the service provided.

<details>
<summary>Click for Image: About Page Hero Image - Desktop</summary>

![About Page hero image on desktop](/assets/images/README/about-hero-desktop.png)

</details>

<details>
<summary>Click for Image: About Page Hero Image - Mobile</summary>

 ![About Page hero image on mobile](/assets/images/README/about-hero-mobile.png)

</details>

The service cards show the three different services that Mobile Physio provides, these cards are enlarged on hover.

<details>
<summary>Click for Image: About Page Service Cards - Hover</summary>

![Service cards when hovered over](/assets/images/README/about-card-hover.png)

</details>

<details>
<summary>Click for Image: About Page Service Cards - Mobile</summary>

![Service cards on Mobile](/assets/images/README/about-card-mobile.png)

</details>

The contact section is used to allow users to easily navigate to the contact page. This has a button that enlarges and changes colur on hover.

<details>
<summary>Click for Image: About Page Contact Section - Hover</summary>

![Contact button enlarged as mouse hovers on it](/assets/images/README/about-contact-hover.png)

</details>

***        
### Contact Page:
This page is split between two elemtns, the clinic information card and the form card.
       
<details>
<summary>Click for Image: Contact Page - Desktop</summary>

![Contact page on desktop](/assets/images/README/contact-desktop.png)

</details>       
       
<details>
<summary>Click for Image: Contact Page - Mobile</summary>

![Contact page on desktop](/assets/images/README/contact-mobile.png)

</details>         
       
The clinic information card provides the user the necessary details to visit Mobile Physio ushc as address and opening hours. It uses widely recognised Font Awesome icons to highlight the use meaning of the text.

The form card allows the user to input the necessary details to book an appointment. Most of the inputs are required to submit the form (except for additional info and date of birth), this stops the user from trying to book an appointment, without the necessary information.

<details>
<summary>Click for Image: Contact Page Form - Required Fields</summary>

![Contact page form showing required fields](/assets/images/README/contact-required.png)

</details>  

The form card also has a submit and reset button that enlarge on hover. When the submit button is pressed and the required fields are filled, the user is sent to the Form Submit page, when the reset button is pressed, the form is cleared.

<details>
<summary>Click for Image: Contact Page Form - Hover</summary>

![Contact page form with buttons enlarged on hover](/assets/images/README/contact-hover.png)

</details>  

The additional info text box is resizable vertically, to allow users to type more info if they require it. The reason horizontal resizablity is not allowed, is due to the fact that it would bring the text off of the screen, whic would look un-professional.

[Back to top!](#mobile-physio)

## Technologies Used
### Languages Used
- HTML5
- CSS3

### Frameworks, Libraries & Programs Used
- [Font Awesome](https://fontawesome.com/):
    - Font Awesome Icons were used for the contact form, social media footer and the testimonial stars.
- [Git](https://git-scm.com/):
    - Version control was performed through the use of Git commands
- [GitHub](https://github.com/):
    - GitHub was used for the hosting of the project. GitHub Pages was also used to host the live website link.
- [Gitpod](https://www.gitpod.io/):
    - Gitpod was used as a a browser based cloud development environment.
- [TinyPNG](https://tinypng.com/):
    - TinyPNG was used to compress all images in the project and REAME, that had an original file size below 5MB.
- [Compressor.io](https://compressor.io/):
    - Compressor.io was used to compress all images in the project and REAME, that had an original file size above 5MB.
- [Balsamiq](https://balsamiq.com/):
    - The wireframes were created using the Balsamiq software.
- [Google Fonts](https://fonts.google.com/):
    - The fonts 'Cabin' and 'Nunito' were imported from Google Fonts, Cabin was used for the headings and Favicon, Nunito was used for the remaining text.
- [Favicon](https://favicon.io/):
    - A favicon was generated and was used in the project files.
- [Coolers](https://coolors.co/):
    - The colour palette was created using coolers.
- [W3C Validator](https://validator.w3.org/)
    - The W3C HTML validator was used to validate all HTML used in the project.
- [W3C Jigsaw Validator](https://jigsaw.w3.org/css-validator/)
    - The W3C CSS validator was used to validate the CSS file used in the project.
- [Chrome Developer Tool - Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/)
    - Lighthouse was used to test performance, accessibility, best practices and SEO across the project.

[Back to top!](#mobile-physio)

## Deployment & Local Development

### Deployment
The Mobile Physio project was deployed using GitHub Pages.

[You can view the live site through this link.](https://callumdennisie.github.io/mobile-physio/)

Steps to deploy this project using GitHub Pages:
1. Navigate to the GitHub repository for this project: [CallumDennisIE/mobile-physio](https://github.com/CallumDennisIE/mobile-physio).
2. Click on the 'Settings' tab: [CallumDennisIE/mobile-physio/settings](https://github.com/CallumDennisIE/mobile-physio/settings).
3. Click on the 'Pages' section: [CallumDennisIE/mobile-physio/settings/pages](https://github.com/CallumDennisIE/mobile-physio/settings/pages)
4. Select the 'Main' source from the dropdown.
5. Wait a few minutes for the site to deploy.
6. The project will be published and a link will be provided to the live site: [Example link](https://callumdennisie.github.io/mobile-physio/).

For more infomration on how to deploy a site with GitHub pages, plaease click [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

***
### Local Development

Steps to fork this project using GitHub:
1. Navigate to the GitHub repository for this project: [CallumDennisIE/mobile-physio](https://github.com/CallumDennisIE/mobile-physio).
2. Click the 'Fork' button (top right-hand side of the repository page).

For more infomration on how to fork a GitHub repository plaease click [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

Steps to clone this project using GitHub:
1. Navigate to the GitHub repository for this project: [CallumDennisIE/mobile-physio](https://github.com/CallumDennisIE/mobile-physio).
2. Click on the 'Code' button, located above the project files.
3. Select 'HTTPS' as the method to clone the repositoy.
4. Copy the link provided, located under 'HTTPS': https://github.com/CallumDennisIE/mobile-physio.git
5. Open the Terminal in the location you would like the reposityo to be cloned to.
6. Type `git clone` and then the link provided in step 4:

``` $ git clone  https://github.com/CallumDennisIE/mobile-physio.git ```


For more infomration on how to clone a GitHub repository plaease click [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)


[Back to top!](#mobile-physio)

## Testing
[View the project testing document here.](TESTING.md)

## Credits

### Code

The back buttons used on both the Form Submit page and the Custom 404 page, used code from W3Schools.

[Link to code used](https://www.w3schools.com/jsref/met_his_back.asp).

### Media

The images for this project were taken from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/).

[Back to top!](#mobile-physio)