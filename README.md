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
* [Design](#design)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Deployment & Local Development](#deployment--local-development)
* [Testing](#testing)
* [Credits](#credits)

## About
Mobile Physio is a site for a Dublin based Physiotherapy Clinic. The target audeince for this site are people with injuries looking for physiotherapy treaments to asssit in recovery. This site will allow users to see the services offered by Mobile Physio, allow them to read reviews from previous pateints and book an appointment.

## User Experience

## Design

## Features
- Navbar:
    - Included on all pages throughout the website. Design is consistent on all pages to provde a consitent user experience.
    - Contains the Website title (which links to the index.html page) and links to the About, Testimonials and Contact Pages.

        ![Navbar displayed on the desktop](/assets/images/README/navbar-desktop.png)
    - On mobile devices, the page title is hidden to allow the navigation links to fit on the screen.

        ![Navbar displayed on a mobile device](/assets/images/README/navbar-mobile.png)
    - Website title and links are underlined when hovered over, this provides extra feedback to the user that these words are links.

        ![Navbar with About page link underlined](/assets/images/README/navbar-ul-link.png)

        ![Navbar with Page title link underlined](/assets/images/README/navbar-ul-title.png)
- Footer:
    - The footer is located at the bottom of each page. It contains social media links to Instagram, Facebook and Twitter.
    - The footer links open in a new tab, to allow the user to remain on the Mobile Physio site without having to navigate back through their search history.
    - Footer uses Font Awesome Icons that are widely recognisable with the associated Social Media sites.
    - Footer Mobile:

        ![Footer on a mobile device](/assets/images/README/footer-mobile.png)
    - Footer Desktop:

        ![Footer on a desktop device](/assets/images/README/footer-desktop.png)
    - Footer icons will enlarge when hovered over, allowing users to get feedback that these are links that can be clicked.

        ![Footer icon being enlarged when hovered over](/assets/images/README/footer-enlarge.png)
- Custom 404 Page:
    - This page will display when a requested when the requested page is not able to be displayed. For example a user who navigates to 'https://callumdennisie.github.io/mobile-physio/help.html', will be connected to the custom 404 page, as help.html does not exist within this project.
    - This custom page replaces the default GitHub Pages 404 page, the default page does not follow the theme of the other Mobile Physio page, which could disorientate users. The custom page also includes the nabar and footer elemnts, to allow the user to continue site navigation.
    - Default GitHub Pages 404 Page:

        ![404 Page on a mobile device](/assets/images/README/404-default.png)
    - Mobile View:

        ![404 Page on a mobile device](/assets/images/README/404-mobile.png)
    - Desktop View:

        ![404 Page on a desktop](/assets/images/README/404-desktop.png)

    - The custom 404 page also includes a 'Go Back' button which will return the user to the previous page in their history. Allowing the user to quickly and easily continue site navigation.

        ![404 Page back button](/assets/images/README/404-button.png)
- Form Submit Page:
    - This page will display when the form has been successfully submited.
    - This provides the user feedback and informs them that the form has been successfully sent.

        ![Form Submit Page on mobile](/assets/images/README/submit-mobile.png)

        ![Form Submit Page on desktop](/assets/images/README/submit-desktop.png)
    - The page contains a back button, allowing the user to return to their previous page, which would be the contact page.

        ![Form Submit back button](/assets/images/README/submit-button.png)
- Testimonials Page:
    - This page shows reviews from previous pateints, creating trust between the user and the Mobile Physio company.
    - Desktop View:

        ![Testimonial page on desktop](/assets/images/README/testimonial-desktop.png)
    - Mobile View:

        ![Testimonial page on desktop](/assets/images/README/testimonial-mobile.png)
    - The individual review sections expand when hovered over, this highlights to the user the review that they are looking at.

        ![Testimonial items enlarging when hovered over](/assets/images/README/testimonial-hover.png)
    - The review stars also animate when hovered over, this makes the website appear more dynamic and less flat.

        ![Animation of review stars on testimonial page when hovered over](/assets/images/README/testimonial-star-hover.png)
- About Page:
    - This page is intended as a landing page for users. It provides infomration about the Mobile Physiocompany and the services they provide.
    - A large hero image shows the user a physiotherpaist working on a patient, allowing them to understand the service provided.
        - Hero Desktop:

        ![Testimonial items enlarging when hovered over](/assets/images/README/about-hero-desktop.png)
        - Hero Mobile:
        
        ![Testimonial items enlarging when hovered over](/assets/images/README/about-hero-mobile.png)
    - The service cards show the three different services that Mobile Physio provides, these cards are enlarged on hover.
    - The contact section is used to allow users to easily navigate to the contact page. This has a button that enlarges and changes colur on hover.
## Technologies Used

## Deployment & Local Development

## Testing
### Bugs:
About page, contact section uses the same id as the main contact section div.

![CSS Image](bug1_css.png)
![CSS Image](bug1_browser.png)
![CSS Image](bug1_media.png)
![CSS Image](bug1_browser_fix.png)
![CSS Image](bug1_css_fix.png)

## Credits