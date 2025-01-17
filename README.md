# **_Food Forest Foraging Recipes - Portfolio Project 1_**

This document contains all the issues necessary to create and develop a website in HTML5 and CSS3 for the website: <a href="https://css-angie.github.io/Food-Forest-Foraging/" rel="noopener" target="_blank">Food Forest Foraging Recipes</a>. The website is a part of the course “Full Stack Software Development” at Code Institute and showcases the knowledge I have gained so far.

<Screenshot of all 3 devices>
</Screenshot>

#table-of-content
* [The objective of the website](#the-objective-of-the-website)	1
The UX part of creation	1
Creating user stories	1
Designing the layout and structure	1
Colour Palette	1
Typography	1
Images	2
Basic Setup	2
Set up of the repository	2
Set up of the basics of the website	2
External sources	2
Features	3
Generic features	3
Homepage	3
Plant page	3
Contact page	4
Technology used	4
Deployment	4
Testing	4
Lessons learned and failures	4
Credits	4





# The objective of the website

The food forest hype keeps continuing to conquer the world. Many people are looking at their garden, wondering what they can do to make the world a better place. The ones doing this are willing to start a food forest with native plants and herbs, shrubs and trees (we will only mention plants from now on, but with regard to all). Somehow, unfortunately, the knowledge how to use native plants got lost along the way. Knowing quite a few people doubting how to use plants from their gardens or found in the woods, I started with the idea of generating information about identification of and recipes for plants. When people harvest plants while foraging in their backyard or the woods, they only need to visit this website to learn on what to do with them.

The primary target groups in this case are:
-	Owners of a food forest (size is not of interest)
-	Foragers going out in the woods
  
Secondary target groups are:
-	The ones who are interested in becoming a food forest owner 
-	Newbies to food foraging, either because they want to become less dependent on supermarkets or have a need to get back to nature

In all cases education on topics (plants) is the common factor.


[Back to top](<#table-of-content>)

# The UX part of creation

## Creating user stories

For the creation of the user stories, we only focus on the primary target group. The user story is complemented with acceptance criteria and tasks to be able designing wireframes that contain all features needed.

<details><summary><b>User Story 1: As a food forest owner / forager I want to see compelling colours, so I can scroll without being blinded</b></summary>

<br>Acceptance criteria: 
    
*	Website has a pleasant colour scheme that soothes the eye and fits a nature site

Task: 

*	Find a great combination of colours
</details><hr>

<details><summary><b>User-Story 2: As a forager / food forest owner I need pictures to identify my plants, so I can scroll to the right plant directly.</b></summary>

<br>Acceptance Criteria: 

*	Images are compressed  
*	Images are high quality and have webp-extension) 
*	Images are showing the right accents to recognize plant

Tasks: 

*	the page layout features the pictures prominent
*	compress all images with tinypng.com
*	search pixel dense images
*	search self-explaining plant images
</details><hr>

<details><summary><b>User Story 3: As a food forest owner, I want to know how to use my harvest in everyday recipes preventing waste, so I need an overview of recipes that fit the produce.</b></summary>

<br>Acceptance criteria:

*	Homepage displays a photo list of plants sorted alphabetically.
*	After each plant is a page containing extended information and several recipes.

Tasks

*	Design homepage in HTML containing 2 blocks in main.
	- an explanation intro, how to use the website
	- a photo list of plants and name using bootstrap cards in alphabetical order
	- a sign up form in the footer containing name and email address where user can show interest in forum or leave a message what plants should be included in the list
*	Use (minimized) photos so plant can easily be identified
*	Incorporate a navbar at the top
*	Style homepage with Bootstrap and CSS
*	Use colour scheme and fitting graphics
*	Design a plant page in Html containing
	- more than one photo,
	- an information section how to identify a plant and
	- at least two recipes
*	Style plant page with Bootstrap and CSS
</details><hr>

<details><summary><b>User-story 4: As a food forest owner I'm not tech savvy, so I need to see what I can find immediately in the navigation section.</b></summary>

<br>Acceptance criteria:

*	The navigation bar is not overcrowded
*	Every navigation point makes sense
*	Responsive and looks clean and clear on every device
*	Navigation is intuitive

Tasks:

*	Design a navigation bar with 3 or 5 subjects
*	Decide on the subjects
*	Apply responsive design with Bootstrap
*	Incorporate an intuitive layout
</details><hr>

<details><summary><b>User-Story 5: As a forager or food forest owner I want to see at a glance what I can expect of the website. Does the website offer me the information I need.</b></summary>

<br>Acceptance Criteria:

*	A catchy headline on homepage
*	Inviting background image
*	One-liner with concise information what visitor can find on site
*	Simple and clear layout

Tasks:

*	Create catchy headline
*	Find a compelling hero image
*	Think of a great one-liner
*	Provide a clean layout
</details><hr>

<details><summary><b>User Story 6: as a forager I want to see more than one photo and read extended information about a plant, so I can identify a plant in the wild.</b></summary>

<br>Acceptance criteria
    
*	more than one image of the plant
*	extensive information about the plant
*	
Tasks

*	search numerous images of the plant
*	find information how to identify the plant
</details><hr>

<details><summary><b>User story 7: as a food forest owner I want to find a recipe that contains the plant with all other ingredients listed and clear preparation instructions, so I can cook everyday meals without a lot of fuzz.</b></summary>
    
<br>Acceptance criteria: 

*	the recipe(s) have a clear name
*	the recipe contains a complete list of ingredients
*	The preparation is shown as a step by step instruction
*	preferably with image
*	the recipes look nicely on all devices
*	
Tasks

*	create layout that is visual appealing for recipes
*	find recipes that contain the plant
*	make unordered list of ingredients with correct amounts
*	make ordered list with preparation instructions
*	make the layout responsive
</details><hr>

<details><summary><b>User story 8: as a forager, I would like to know if like-minded people live near me, so I can get in touch with them. That's why I like to fill in the register form and join.</b></summary>

<br>Acceptance criteria:

*	Registration Form to register for the forum
*	Form contains a message box for additional questions
*	Form looks nice on every device
*   The fields with name and email are required
*	The checkbox for newsletter is optional
*	
Tasks

*	Create form with required name field and required email field and message box
*	Create a checkbox for joining forum or not
*	Make hover function on send-button
*	Use Bootstrap to create round edges for the boxes
</details><hr>

<details><summary><b>User story 9: as a visitor I would like to subscribe to the newsletter, so I will be informed when a new plant is added to the database.</b></summary>
    
<br>Acceptance criteria: 

*	the website contains a sign up option for a newsletter
*	the sign up option sits in the footer so it will show up on every page, making it easy to subscribe
*	
Tasks

*	create a form with required fields: name and email
*	created a checkbox with a required checkbox to sign in
*	add form to footer
</details>


[Back to top](<#table-of-content>)

## Designing the layout and structure
After having created several user stories, all are used to create a structure that meets all the mentioned requirements i.e. acceptance criteria. Wireframes were made with Balsamic to set the basic guidelines for the process.

<details><summary> Mockups Homepage </summary>

![preview homepage mobile](assets/readme-images/hp-mobile.png) ![preview homepage tablet](assets/readme-images/hp-tablet.png) ![preview homepage desktop](assets/readme-images/hp-desktop.png)
</details>

<details><summary> Mockups Plant page </summary>

![preview homepage mobile](assets/readme-images/pp-mobile.png) ![preview homepage tablet](assets/readme-images/pp-tablet.png) ![preview homepage desktop](assets/readme-images/pp-desktop.png)
</details>

<details><summary> Mockups Contact page </summary>

![preview homepage mobile](assets/readme-images/sf-mobile.png) ![preview homepage tablet](assets/readme-images/sf-tablet.png) ![preview homepage desktop](assets/readme-images/sf-desktop.png)
</details>
 
## Colour Palette

Being a website about nature, the first colours that come to mind are green and brown, as they connect emotionally to anything natural. But it took some time to find the right colour scheme as green and brown aren't a match, when it comes to contrasting colours. With green as the main colour, most of the generated palettes (at numerous sites) offered a palette with too little contrast, thus creating contrast errors. The palette that is being used now has the colours of most seasons. Orange is a colour associated with sunset and autumn. Whereas autumn is generally known as the harvest season. 

![preview homepage mobile](assets/readme-images/colour-scheme.png)

Finally, this green and orange scheme at [coolors.co](https://coolors.co) almost passed the test. The light contrast colour is a 70% shade and was changed to the 62% shade to erase any contrast errors, resulting in HEX-colour #E4B681.
The final colours are now:
#606C38 olive green - jungle civilization
#283618 dark green - darkest forest
#FEFAE0 light yellow - magnolia
#E4B681 light orange – cane sugar
#BC6C25 middle orange brown - brown alpaca

## Typography

The criteria for the fonts were:
-	Heading should have a friendly and personal touch, which leads to handwritten looks.
-	The primary font should be readable at all times and should be a straightforward font without much ado.
Looking in the Google Fonts library I found the appealing font Quintessential for the headings and the sturdy font Roboto for the body text.
Quintessential has a fallback of cursive and Roboto sans-serif.

## Images

The general colour palette of the site is greenish, as the project deals with the subject of nature and plants. Therefore it makes sense to continue this look-and-feel in  the images  used showing lots of green, brown, and all bright and fresh colours you can find in nature.
The logo represents a tree, as is found in forests and the favicon is made from the logo to ensure repetition.<br>
![logo website](assets/images/logo.png)


[Back to top](<#table-of-content>)

# Basic Setup

## Setup of the repository 

The basic setup started with setting up the repository for the project in Github. Within it creating a project board and fill out the board with the user stories with their requirements and the subsequent tasks, labeling every task in the to-do section with must-have, should-have and could-have.
Along with it the basics of the website were created with the folder structure:
	- index.html with boilerplate and connection to the style.css stylesheet;
    - assets - css - style.css;
    - assets - favicon and fill this with the generated favicon;
    - assets - images and put all images so far in it.

External sources used in this project are:
    - Bootstrap Version 5;
    - Google Fonts.
These were added as well at the correct places.

The setup was checked and deployed and ready to be filled with all features.


[Back to top](<#table-of-content>)

# Features

## Generic features

### Responsive design

One of the most important generic features of any website is the responsive design to ensure a great user experience on any device. This was achieved by using bootstrap columns, flex-boxes and media queries. The common DOM breakpoints were used with only one exception. An extra query with min-width 1080px was used to fix the height of the title at the plant catalog, which changed the appearance in a very negative way. To avoid a broad form at the contact page, the same min-width of 1080px was used to keep the code as short as possible, as it was already available.

### Favicon

The favicon is a beacon in all tabs opened and offers visitors a quick reminder of the site. It is important to have a favicon that represents the website.
By using the logo making it into a favicon at [favicon](https://favicon.io) the site shows consistancy and offers a recognizable favicon.<br>![favicon website](assets/favicon/favicon.ico)

### Navigation

As website users are used to a certain layout nowadays, the best user experience is to offer the navigation displayed in the same way as they are used to. Therefore the logo leading to the homepage is on the left and the menu with the menu items is on the right. On small and medium screens the menu is represented with the well-known hamburger icon offering a dropdown menu when clicked. To avoid contrast errors the current page is not highlighted, but bolder than the other links. There is a light hover effect on the links.<br>
The navigation consists of three options. Studies have unveiled that uneven numbers of a menu are most pleasing to the mind of visitors. For a great user experience the navigation should always be available at the screen and hence sticky on any device. No need to scroll back to the top. 

![Navigation bar - mobile devices](assets/readme-images/navbar-mobile-devices.png) ![Navigation bar - larger devices](assets/readme-images/navbar-larger-devices.png)

### Hero section
The hero banner is a returning focus point at all pages. This is a seperate user story that indicates, that the website needs a clear image and text, which shows the visitor at a glance what can be found at this particular page. A very important aspect, as the fundamental principle of the website is being informative. The heading is a short and appealing description of what can be expected and found at the page, inviting the visitor to scroll down further.<br>
For the mobile version a smaller size of the hero image is used to garantuee an excellent performance at loading. 

![Hero section - mobile devices](assets/readme-images/hero-section-mobile-devices.png) ![Hero section - large devices](assets/readme-images/hero-section-larger-devices.png)

### Footer
The footer shoukld be consistent at all pages of the website. This time it is not.<br>As the footer offers a signup option to subscribe to the newsletter, this won't be a neccesity at the page with the contactform, as the form already contains the option to subscribe to the newsletter. Furthermore, the simple variety of the footer is found at the 404 and thank you page. The footer stands out due to the contrast colour.<br>The form offers the option to subscribe to the newsletter with recipes. Only the names, mailaddress and if wished a message can be sent. The checkbox stating one would like to receive the newsletter is required. The button has a hover function and after being clicked a thank you page appears.

![Footer - mobile devices](assets/readme-images/footer-mobile-devices.png) <details><summary> Screenshots footer larger devices</summary>![Footer - medium devices](assets/readme-images/footer-medium-devices.png) ![Footer - large devices](assets/readme-images/footer-large-devices.png) </details>
<details><summary> Screenshots small footer on mobile and on large devices</summary>v![Footer small - mobile devices](assets/readme-images/footer-small-mobile-devices.png) ![Footer small - large devices](assets/readme-images/footer-small-large-devices.png) </details>

## Homepage

### Main section
The main section comprises two parts.
<br>First to see, is a text in which is explained what can be found at the website and who will enjoy the content most - the target groups. To keep it open and readable the section is divived into more paragraphs, which on mobile screens is a must.
Second, a collection of plants is shown with bootstrap cards as basis. By touching or scrolling over the image, it is covered in an orange border, so you know, you will choose the right plant to get more information from. All images are of high quality providing the right accent of the plants to identify it generally, is clickable and linked to their plant page. Chickweed and dandelion have completed pages, all others should be filled out later (should-have).<br>
The plants are displayed in alphabetical order, which can be maintained easily in the CSS section, where the sequence is admitted (1 for a, 13 for m, 26 for z). If the database continues to grow, the first change to make is adding a 0 to all numbers. You will have 10 options for every letter to maintain the alphabetical order. Furthermore, we should add a paging bar on mobile screens (should-have), if the number of plants rises.

![Homepage part 1 - mobile devices](assets/readme-images/homepage1-mobile-devices.png) ![Homepage part 2 - mobile devices](assets/readme-images/homepage2-mobile-devices.png) ![Homepage part 3 - mobile devices](assets/readme-images/homepage3-mobile-devices.png) <details><summary>Screenshots Large Device</summary>![Homepage part 1 - larger devices](assets/readme-images/homepage1-larger-devices.png) ![Homepage part 2 - larger devices](assets/readme-images/homepage2-larger-devices.png) ![Homepage part 3 - larger devices](assets/readme-images/homepage3-larger-devices.png)</details>


## Plant page
The plant pages are the important reason this website attracts visitors.,br
First thing to be seen is the acctractive hero image with a text. This text describes the plant in the common and latin name. The sub heading tells the visitor what is written about the plant at this page : specific characteristics of and recipes with the plants.<br>
Being able to identify a plant is not only done with text, images are of great support. The identification section should contain at least two images The images at this page are of high quality, still small enough to offer a great user experience and offering accents of the plant to identify it easier. The pictures are captured in the text, describing how to identify a plant. <br>
The recipe section is seperated from the identification part through an clear and contrasting green color to help the visitor expect other information.
The plant page needs to include at least two recipes. These will be displayed underneath each other at a mobile devices and medium screens to keep it readable. At larger screens the recipes are displayed next to each other as this looks more appealing. The recipe names are clear and signify the ingredients in an unordered list. The recipes contain a complete list of ingredients and a short, but helpful step by step instruction in an ordered list. The recipes have an image with the finished result.<br>
<details><summary> Screenshots Plant page mobile devices</summary>

![plant page mobile 1](assets/readme-images/mobile-devices-plant-page1.png) ![plant page mobile 2](assets/readme-images/mobile-devices-plant-page2.png) ![plant page mobile 3](assets/readme-images/mobile-devices-plant-page3.png) ![plant page mobile 4](assets/readme-images/mobile-devices-plant-page4.png)
</details>

<details><summary> Screenshots Plant page larger devices</summary>

![plant page larger devices 1](assets/readme-images/larger-devices-plant-page1.png) ![plant page larger devices 2](assets/readme-images/larger-devices-plant-page2.png) ![plant page larger devices 3](assets/readme-images/larger-devices-plant-page3.png) 
</details>

## Contact page
The contact page is an extended version of the newsletter subscription option at the bottom of other pages. At this page you can register for the forum. The forum is meant to make it easier for like-minded to find each other. Find someone in your erea to forage with for example. First the text invites visitors to subsribe and join the forum in the headings of the hero section. By asking questions what the wishes might be of the visitor, the visitor is tried to be pursuaded to join. <br>
The form contains required fields: first name, last name, email address, next options apply to me and the checkbox "I want to join the forum". The message box en checkbox for the newsletter are optional.<br.>
As the section 'next options apply to me' should be required parlty only, a piece of JavaScript was used provided by my mentor Gareth McGirr , as they cannot be linked to each other with HTML.<br>
The sign-up button has a hover affect and when clicked, a dump form appears to show the collected data from this subscription.

<details><summary> Screenshots contact page mobile devices</summary>![Contact page - mobile devices](assets/readme-images/contact-page-mobile-devices.png)</details> <details><summary>Screenshots Larger Devices</summary>![Contact page - medium devices](assets/readme-images/contact-page-medium-devices.png) ![Contact page - large devices](assets/readme-images/contact-page-larger-devices.png) </details>

## Thank you page
A thank you page appears when the form in the footer is filled out. It is a simple confirmation stating the sign-up was successful and displays a return to homepage button to keep the visitor at the site. The button has a hover effect. Eventually, the visitor can use the navigation bar, as this is displayed as well at this page.
When the contactform at the contact page is sent, the sent data is displayed in a dump form.

<details><summary> Screenshots thank you page mobile devices</summary>![Thank you page - mobile devices](assets/readme-images/thankyou-page-mobile-devices.png) </details>
<details><summary>Screenshot Large Device</summary>![Thank you page - larger devices](assets/readme-images/thankyou-page-large-devices.png) </details>

## 404 page
Sometimes things go wrong. This is where the 404 page comes in. <br>
As it must be clear, that something went wrong, the 404 shows a text tohether with an image that the page looking for, does not exist.<br>
To fit to the site an image of a tree is used with 404 on it, accompanied with a text that matches the subject of the site: "nothing to forage here!". With it the option to return to the homepage AND the option to send a message, makes this page a good user experience. 

<details><summary> Screenshots 404 page mobile devices</summary>![404 page - mobile devices](assets/readme-images/404-mobile-devices.png)</details> <details><summary>Screenshot Large Device</summary>![404 - larger devices](assets/readme-images/404-larger-devices.png) </details>

## Sitemap XML page
Most websites want to be found and will only flourish, if they are found by search engines. To make it easier for search engines understanding the infrastructure of the website, a XML Sitemap is added. This XML Sitemap was generated at [XML Sitemap Generator](https://www.xml-sitemaps.com)

<details><summary>Screenshot Sitemap</summary>![Sitemap XML page](assets/readme-images/XML-Sitemap.png) </details>

## Privacy Policy
At every website a privacy policy page is mandatory. As this project will not be displayed to unknown visitors, a template is used, which was generated at [Moneris](https://developer.moneris.com/More/Compliance/Sample%20Privacy%20Policy) 

<details><summary>Screenshot Privacy Policy</summary>![privacy Policy page](assets/readme-images/privacy-policy.png)</details>

[Back to top](<#table-of-content>)


# Technology used

## Languages: 
 - HTML
 - CSS
 - JavaScript (in contactform to assure on of the four options is checked)

 ## Other libraries and programs:
- CSS Library [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Font Library [Google Fonts](https://fonts.google.com) 
- Color Library [Coolors](https://coolors.co)
- Balsamic app for creating wireframes
- Gitpod for writing code
- Project Overview and deployment [Github](https://github.com/)
- AI Image Generator [Deep AI](https://deepai.org)
- AI Text Generator [ChatGPT 4.0](https://chatgpt.com)

[Back to top](<#table-of-content>)



# Deployment
Deployment was done with Github.

To deploy the website next steps should be taken:
1. Login to Github
2. Find the repository of the project. In this case: [CSS Angie - Food-Forest-Foraging](https://github.com/CSS-Angie/Food-Forest-Foraging)
3. Go to Pages in the navigation menu left under Settings.
5. Under branch change None to main and keep /root and click save next to these two dropdowns.
6. The site will be deployed after clicking save.
7. Return to the page "<>Code", and on the right side you'll find deployments. Clicking on it will open a new page, where you'll find the link to open the deployed site.

[Back to top](<#table-of-content>)


# Testing

Several tools were used to test the website comprehensively. Validating all written HTML was done online at the website [Markup Validation Service](https://validator.w3.org/)
<br><br>

All CSS was checked at the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
No issues where found.
![Validation CSS](assets/readme-images/validation-css.png) 

## Homepage
### HTML 
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation homepage](assets/readme-images/validation-homepage.png) </details>

### Performance
In Google Chrome Developer Tools the Lighthouse report is generated for the pages. The first test had a performance result of 72% on mobile devices. No screenshot was made at the time. The most important issue was the LCP - Largest Contentful Paint. The hero image took too long to load the page. After submitting two hero images, taking a smaller one for the mobile devices, the results improved and showed a 93% performance.
<details><summary>Screenshot Validations</summary>![Validation Lighthouse mobile devices](assets/readme-images/lighthouse-mobile.png) 
![Validation Lighthouse desktop devices](assets/readme-images/lighthouse-desktop.png)</details>

#### Performance Issues remaining
As the results are in the green, we will not continue to minimize the hero image, which is causing a drop on every page it is presented
<details><summary>Screenshot Issue</summary>![Lighthouse mobile issue 1](assets/readme-images/lighthouse-mobile-issue.png)</details><br>
This one is somewhat confusing. For mobile devices, it shows the issue of a low-quality logo. This is not said when tested for desktops. As the logo is much larger on the desktop and apparently okay, this issue will not be taken up.
<details><summary>Screenshot Issue</summary>![Lighthouse mobile issue 2](assets/readme-images/lighthouse-mobile-issue2.png) </details>

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts.
<details><summary>Screenshot Validations</summary>![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-homepage.png)</details>

##  Plants page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation plant page](assets/readme-images/validation-plants.png) </details>

### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-plantpage.png)

# Contact page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. With it, a larger issue appeared on the contact page. All errors were connected to the checkbox section. 
![Validation contact page errors mentioned](assets/readme-images/Schermafbeelding%202025-01-16%20090146.png) 
After taking them out the page was free of errors and warnings.
![Validation contact page](assets/readme-images/validation-contact-page.png) 
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-contactpage.png)

### Validating form
To make sure data is being transferred to the backend, the formdump of Code Institute was used.
![Form validation](assets/readme-images/..) 

## chickweed page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation chickweed page](assets/readme-images/validation-chickweed.png) </details>

### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-chickweed.png)

# dandelion page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation dandelions page](assets/readme-images/validation-dandelions.png) </details>
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/..)

# fern heads page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation fern heads page](assets/readme-images/validation-fern-heads.png) </details>

### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/..)

# purslane page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) </details>
![Validation purslane page](assets/readme-images/validation-purslane.png)  
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/..)

# stingly nettle page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation stingy nettle page](assets/readme-images/validation-stingy-nettle.png) </details> 
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/..)

# wild garlic page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) 
![Validation wild garlic page](assets/readme-images/validation-wild-garlic.png)  </details>
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/..)

# thank you page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) </details>
![Validation thank you page](assets/readme-images/validation-thankyou.png) 
### Performance

### Accessibilty
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-thankyou.png)

# 404 page
### HTML
On every page trailing slashes were found on void elements. I have no explanation for how these slashes came there.
I have used emmet abbreviations, but trying the abbreviations again gave a clean result. After taking them out the page was free of errors and warnings.
<details><summary>Screenshot Validations</summary>![Validation info trailing slash screenshot](assets/readme-images/validation-info-trailing-slash.png) </details>
![Validation 404 page](assets/readme-images/validation-404.png) 
### Performance

### Accessibility
The page is being tested on accessibility with the [Wave Evaluation Tool](https://wave.webaim.org/) 
No  errors are found in the contrasts
![Contrast validation with Wave](assets/readme-images/validation-contrast-errors-404.png)
 


## Responsiveness of different devices
Testing the website on a real iPhone 12 gave a different result than in DevTools. 
In one of the README's I came across the website [Responsinator](https://www.responsinator.com) and tested the website there as well. As the same results were shown, the H2 heading needed to be adapted on the homepage.

![Issue responsiveness](assets/readme-images/Issue%20responsiveness.png)

After adressing the bug (taking out the height for ththe h2 heading), the result was:

![Issue responsiveness](assets/readme-images/responsiveness-after-correction.png)

## Manual Testing of Features

| Feature | Expected Result | Pass or Fail |
|:----------|:------------|:------------:|
|Website logo in navigation menu links to homepage | User clicks on the logo to be taken to the homepage |Pass|
|Links in navigation menu | Users click home, plants, or contact to be taken to the relevant page |Pass|
|Burger navigation in screens below 768px wide | Menu appears and dropdown navigation items appear |Pass|
|Hero section on all pages contains an explanatory title | User understands what he can find on the page |Pass|
|Plants are displayed in alphabetical order | User can make a quick search because of the logic |Pass|
|Plants are visibly changing when hovered to make clear which plant is clicked | User hovers and sees which plant the cursor is at |Pass|
|The images and text of the plants are linked to the correct information page| The user clicks and the relevant page is opened |Pass|
|Contact form within the footer allows messages to be submitted when correct information entered | The user understands what needs to be filled out |Pass|
|The name section of the contact form is a required field| If the field is not filled out an error message appears and the form is not submitted |Pass|
|The email section of the contact form is a required field and must be entered in the required format| If the field is not filled out an error message appears, or if the input is not in an email address format the form is not submitted |Pass|
|The checkbox is required | If the checkbox is not checked an error message appears and the form is not submitted|Pass|
|The message section of the contact form is not a required field| If the field is not filled out the form can be submitted any way |Pass|

|- | - |Pass|
|- | - |Pass|
|- | - |Pass|


[Back to top](<#table-of-content>)




# Future features
The website is just a start of a website, that can be expanded excessively. There are several features to build in, that would definitely be an upgrade to the website.

## Forum
The forum can be subscribed to, but is not actually live. This could be the backbone of the site, as you may find here volunteers to write pages of new plants with identification and recipes, get tips for better identification to improve the description at the website and so on.

## Recipe site with filter
Sometimes you want to scroll recipes for inspiration what to pick in your garden or forest. A page with recipes (with filter) will meet this need.

## Plant gallery with search option
As soon as more plant pages emerge, a better way to find the plant is needed. Writing a specific characteristic down in a search option should spit out all options.

# Credits

## Sources used to write website
- Code Institute Course Content was very helpful for creating this website.
- The [Dee Mc videos](https://www.youtube.com/@IonaFrisbee) were a great help to comprehend flex-box.

## Images 
-	Hero image is originally from [Tuinsmakelijk](https://www.tuinsmakelijk.nl) (This will not be used, should this website go live for the public);
-	Logo, 404, recipe images, plant images are AI generated with [DeepAI](https://deepai.org);
-	Fern heads image originates from [The Spruce](https://thespruce.com) (This will not be used, should this website go live for the public);
-	Some images (chickweed, dandelion, stingy nettle, wild garlic and purslane) are private photos.
<br><br>
All images are compressed with [TinyJPG](https://tinypng.com)<br>
All images are converted to .webp extension with [Convertio](https://convertio.co)

## Texts
Some texts are generated by [ChatGPT 4o mini](https://chatgpt.com) and partly rewritten.<br>
The recipes are found at other sites:
- [Homestead Acres](https://www.homestead-acres.com/) - Dandelion jelly;
- [Eating Well](https://www.eatingwell.com/) - Aragula, cantaloupe and goat cheese salad – adapted;;
- [Learning Herbs](https://www.learningherbs.com/) chickweed pesto;
- [River Cottage](https://rivercottage.net/) herby chickweed and crow garlic pakoras – adapted.


## Fonts
All fonts at the site were found in the [Google Fonts Library](https://fonts.google.com).

## Favicon
For this great favicon [favicon.io](https://www.favicon.io) was used.

## Colours
The fabulous colour scheme was found at [Coolors](https://coolors.co) 
The website [Colorkit](https://www.colorkit.co) reveiled the names of the colours.
https://www.w3schools.com  where I highlighted the navbar background colour from 62% to 70% to eliminate contrast errors. 

## Privacy Policy sample text
At [Moneris](https://developer.moneris.com/More/Compliance/Sample%20Privacy%20Policy) a sample of a privacy policy could be copied.

## XML-Sitemap
XML-Sitemap was created with the free [Online Sitemap Generator](https://www.xml-sitemaps.com)

## README
To get an insight how to create a great README's I red the README's of [Socks in a Box](https://github.com/catapam/socks-in-a-box/blob/main/README.md), [Sophie McGee Copywriting](https://github.com/SophieMcGee/sophie-mcgee-copywriting/blob/main/README.md) and [Batala Bangor](https://github.com/emmahewson/mp1_batala_bangor/blob/main/README.md)

[Back to top](<#table-of-content>)


# Acknowledgements
Gareth McGirr, my mentor, for all his help and advice throughout the project.<br>
Kristyna Wach for taking care I did not bite of more than I could chew and keeping me motivated.

[Back to top](<#table-of-content>)



