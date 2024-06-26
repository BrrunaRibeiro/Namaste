# Project 1 - Namaste

[Namaste](https://brrunaribeiro.github.io/Namaste/)

![Screenshot](assets/images/readmeimages/indexpagescreenshot.webp)

## Technologies Used

#### Languages Used

* HTML5
* CSS3

#### Frameworks, Libraries & Programs Used

* Hover.CSS
* Hover.CSS was used on the navigation elements in the header 
* Git - For version control.
* Github - To save and store the files for the website.
* Google Fonts - To import the fonts used on the website.
* Font Awesome - For the iconography on the website.
* Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling. 

## User Experience(UX)

##### Strategy

    The website initial goal is to show an updated schedule, facilitate the Sign-Up process and reach new clients. The company needs more online presence and to grow revenue. The competition has innovative methodology but offers limited classes in limited schedule options. The differential about Flow is the flexibility in schedule and a genuine care for the clients, besides offering more space and even private rooms. Also, the owner temporarily moved to India to learn the best practices and learn from the best. The company focuses on quality and constantly asks for feedback for improvements. 

##### Scope

    Based on the Strategy overview, the website will have a catching-eye home page; an easy to find sign-up page; an online schedule which can be updated and visible to all students at once. In a future release, a page to possibly leave a feedback/suggestions will be included.

##### Structure

    The home page will have a navigation menu ont he top, with the first link being the Home page link, followed by the sign-up, then the logo, followed by the schedule and contact. 

##### Skeleton

    Navigation bar will the fixed at the top for a visibility and to help user to efficiently move through content. Representational icons to help decode which item does. 

#### Surface

    The website will have calm colors, with a good contrast for accessibility. A light-weight font and images that bring a sense of peace.  

## Design & Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Slate Gray | ![#7F8F97](https://via.placeholder.com/10/7F8F97?text=+) #7F8F97 |
| Davy's Gray | ![#4E5353](https://via.placeholder.com/10/4E5353?text=+) #4E5353 |
| Buff | ![#D3997E](https://via.placeholder.com/10/D3997E?text=+) #D3997E |
| White | ![#FFFFFF](https://via.placeholder.com/10/FFFFFF?text=+) #FFFFFF |
| Payne's Gray | ![#58666C](https://via.placeholder.com/10/58666C?text=+) #58666C |

## Screenshots

![Screenshot Index](assets/images/readmeimages/screenshotindex.webp)

![Screenshots Index:Hover](assets/images/readmeimages/screenshotindexhover.webp)

![Screenshots Form Confirmation Page](assets/images/readmeimages/screenshotformconfirmation.webp)

## Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

* Log in (or sign up) to Github.
* Click on the Settings link.
* Click on the Pages link in the left hand side navigation bar.
* In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
* Click Save. Your live Github Pages site is now deployed at the URL shown.

## Tests

* The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.
  * W3C Markup Validator - Passed
  * W3C CSS Validator - Passed
* [WAVE](https://wave.webaim.org) - Web Accessibility Evaluation Tool
  * Contrast Ratio: 8.59:1
  * WCAG AA: Pass
  * WCAG AAA: Pass
  * WAVE does not detect contrast of background gradients, transparency, etc. For background images, WCAG requires a fallback background color in case the image does not display.
* Google Dev Tools - To troubleshoot and test features, solve issues with responsiveness and styling.

#### Manual Testing

| Test Case | Description | Expected Result | Actual Result | Pass/Fail |
|-----------|-------------|-----------------|---------------|-----------|
| 1         | Homepage    | Verify that the homepage loads without errors | Homepage is displayed with content and images | [x] Pass / [ ] Fail |
| 2         | Navigation Buttons | Test each button on the navigation bar/header | Each button correctly navigates to its respective page | [x] Pass / [ ] Fail |
| 3         | Contact Form | Fill out and submit the contact form | Form submission successful, user receives confirmation message | [x] Pass / [ ] Fail |
| 4         | Responsive Design | Test website on different devices (desktop, tablet, mobile) | Website layout adjusts correctly for different screen sizes | [x] Pass / [ ] Fail |
| 5         | Broken Links | Check for any broken links on the website 404 page created to handle it | No broken links found, 404 page created | [x] Pass / [ ] Fail |
| 6         | Image Loading | Verify that all images load correctly | All images display properly without any errors | [x] Pass / [ ] Fail |
| 7        | Form Validation | Test form validation for all input fields | Proper error messages display for required empty inputs | [x] Pass / [ ] Fail |
| 8        | Social Media Integration | Test social media links/buttons | Links/buttons correctly direct users to respective social media profiles/pages | [x] Pass / [ ] Fail |
| 9        | Accessibility | Website can be used by visually impaired users | Website is navigable and usable for users with disabilities | [x] Pass / [ ] Fail |
| 10         | Confirmation Page | After confirmation, user should be redirected to the main page | User is automatically redirected to the main page after 10 seconds |[x] Pass / [ ] Fail |

#### Further Testing

* The Website was tested on Google Chrome.
* The website was viewed on a variety of devices such as Desktop, Laptop, Mobile Phones and Tablets.
* A large amount of testing was done to ensure that all pages were linking correctly.
* Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.
* Responsiveness was checked in Google Chroms Dev Tools, as well as secondary websites, example: https://ui.dev/amiresponsive?url=https://brrunaribeiro.github.io/Namaste/


## Acknowledgements

* My Mentor for continuous helpful feedback.

### Credits

* Code credits: Bruna Ribeiro
* Content Credits: MindBodyGreen.com
* Media Credits: Unsplash.com
* Icons Credits: FontAwesome.com
* ReadMe Credits: https://github.com/kera-cudmore & https://github.com/Code-Institute-Solutions/SampleREADME
* FQA Credits: https://dev.to/felixdusengimana/lets-create-an-faq-section-with-html-and-css-only-detail-tag-explained-12gf

## Features & Explanation of what works

* Home page with sign-up button to possibly reach new clients.
* Nav menu with Keyframe(transform) to get user's attention.
* Form with a date picker for first class/trial lesson.
* Form confirmation page with time-based automatic redirection to the Home page.
* Footer with Social media opening in a new tab.
* Embedded Google Maps Iframe opening in a new tab.
* Expandable FQA(Frequently Asked Questions) in Contact page.
* Favicon in all pages.

### What you did not had time to do

* Add more content. As the project is fictitious I decided to focus on the features and learning rather than the content. 
* Invest more time in Readme file.
* Add more Media Queries.

### Functionalities you would like to add in the future

* Date picker starting from today's date and on(You can currently choose dates in the past).

### Bugs you found and solved along the way

* Google maps Iframe does not work. Output Error: "www.google.com refused to connect." - Fixed
* Navigation links are not working in SignUp page - Fixed
* Link to CSS sheets had wrong path. Style sheet does not load. - Fixed
* Header/Nav links were not clickable in Contact page at first. -Fixed
* Contact page has a style issue. -Fixed
* Link to whatsapp in contact page does not work. -Fixed
* Favicon was not loading. -Fixed