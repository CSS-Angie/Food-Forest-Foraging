# **_Food Forest Foraging Recipes - Portfolio Project 1_**

This document contains all the issues necessary to create and develop a website in HTML5 and CSS3 for the website: <a href="https://css-angie.github.io/Food-Forest-Foraging/" rel="noopener" target="_blank">Food Forest Foraging Recipes</a>. The website is a part of the course “Full Stack Software Development” at Code Institute and is a showcase of the knowledge I have gained so far.

<Screenshot of all 3 devices>
</Screenshot>

# Table of Contents
The objective of the website	1
The UX part of creation	1
Creating user stories	1
Designing the layout and structure	1
Colour Palette	1
Typography	1
Images	2
Basic Set-up	2
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

The food forest hype keeps continuing to conquer the world. Many people are looking at their garden, wondering what they can do to make the world a better place. The ones doing this are willing to start a food forest with native plants and herbs, shrubs and trees (we will only mention plants from now on, but with regard to all). Somehow unfortunately, the knowledge how to use native plants got lost along the way. Knowing quite a few people doubting how to use plants from their garden or found in the woods, I started with the idea to generate information about identification of and recipes for plants. When people harvesting plants during foraging in their backyard or in the woods, they only need to visit this website to gather the knowledge what to do with it.

The primary target group in this case are:
-	Owners of a food forest (small or large is not of interest)
-	Foragers going out in the woods
  
Secondary target groups are:
-	the ones who are interested in becoming a food forest owner 
-	newbies to food foraging, either because they want to become less dependent on supermarkets or have a need to get back to nature

In all cases the education on topics (plants) is the common factor.


[Back to top](<#contents>)

# The UX part of creation

## Creating user stories

For the creation of the user stories, we only focus on the primary target group. The user story is complemented with acceptance criteria and tasks to be able to design wireframes that contain all features needed.

<details><summary><b>User Story 1: As a food forest owner / forager I want to see compelling colours, so I can scroll without being blinded</b></summary>

<br>Acceptance criteria: 
    
*	Website has a pleasant colour scheme that soothes the eye and fits a nature site

Task: 

*	Find a great combination of colours
</details><hr>

<details><summary><b>User-Story 2: As a forager / food forest owner I need pictures to identify my plant, so I can scroll to the right plant directly.</b></summary>

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

<details><summary><b>User Story 3: As a food forest owner, I want to know how to use my harvest in everyday recipes preventing waste, so I need an overview of recipes that fits the produce.</b></summary>

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

<details><summary><b>User-story 4: As a food forest owner I'm not tech savvy, so I need to see immediately what I can find in the navigation section.</b></summary>

<br>Acceptance criteria:

*	The navigation bar is not overcrowded
*	Every navigation point makes sense
*	Responsive and looks clean and clear at every device
*	Navigation is intuitive

Tasks:

*	Design a navigation bar with 3 or 5 subjects
*	Decide on the subjects
*	Apply responsive design with Bootstrap
*	Incorporate an intuitive layout
</details><hr>

<details><summary><b>User-Story 5: As a forager or food forest owner I want to see at a glance what I can expect of the website. If the website offers me the information I need.</b></summary>

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
*	the recipes look nicely at all devices
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

<details><summary><b>User story 9: as a visitor I would like to subscribe to the newsletter, so I will be informed, when a new plant is added to the database.</b></summary>
    
<br>Acceptance criteria: 

*	the website contains a sign up option for a newsletter
*	the sign up option sits in the footer so it will show up on every page, making it easy to subscribe
*	
Tasks

*	create a form with required fields: name and email
*	created a checkbox with a required checkbox to sign in
*	add form to footer
</details>


[Back to top](<#contents>)

## Designing the layout and structure
After having created several user stories, all are used to create a structure that fit all the mentioned requirements i.e. acceptance criteria. Wireframes were made with Balsamic to set the basic guideline for the process.

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

Being a website about nature, first colours that come in mind are green and brown, as they connect emotionally to anything natural. But it took some time to find the right colour scheme as green and brown aren't a match, when in comes to contrasting colours. With green as the main colour, most of the generated palettes (at numerous sites) offered a palette with too little contrast, thus creating contrast errors. The palette that is being used now has the colours of most seasons. Orange is a colour associated with sunset and autumn. Whereas autumd is generally known as the harvest season. 

![preview homepage mobile](assets/readme-images/colour-scheme.png)

Finally this green and orange scheme at [coolors.co](https://coolors.co) almost passed the test. The light contrast colour is a 70% shade and was changed to the 62% shade to erase any contrast errors, resulting in HEX-colour #E4B681.
The final colours are now:
#606C38 olive green - jungle civilization
#283618 dark green - darkest forest
#FEFAE0 light yellow - magnolia
#E4B681 light orange – cane sugar
#BC6C25 middle orange brown - brown alpaca


[Back to top](<#contents>)
 
## Typography

The criteria for the fonts were:
-	Heading should have a friendly and personal touch, which leads to handwritten looks.
-	The primary font should be readable at all times and should be a straightforward font without much ado.
Looking in the Google Fonts library I found the appealing font Quintessential for the headings and the sturdy font Roboto for the body text.
Quintessential has a fallback of cursive and Roboto the fallback sans-serif.


[Back to top](<#contents>)

## Images

The general colour palette of the site is greenish, as the project deals with the subject nature and plants. Therefore it makes sense to continue this look-and-feel in  the images  used showing lots of green, brown and al bright and fresh colours you can find in nature.
The logo represents a tree, as is found in forests and the favicon is made from the logo to ensure repetition.<br>
![logo website](assets/images/logo.png)


[Back to top](<#contents>)

# Basic Set-up

## Set-up of the repository 

The basic set-up started with setting up the repository for the project in Github. Within it creating a project board and fill out the board with the user stories with their requirements and the subsequent tasks, labeling every task in the to-do section with must-have, should-have and could-have.
Along wi it the basics of the website were created with the folder structure:
	- index.html with boilerplate and connection to the style.css stylesheet
    - assets - css - style.css
    - assets - favicon and fill this with the generated favicon
    - assets - images and put all images so far in it

External sources used in this project are:
    - bootstrap version 5
    - google fonts
These were added as well at the correct places

The set-up was checked and deployed and ready to be filled with all features


[Back to top](<#contents>)

# Features

## Generic features

### Responsive design

One of the most important generic features of any website is the responsive design to ensure a great user experience at any device. This was achieved by using bootstrap columns, flex-boxes and media queries. The common DOM breakpoints were used with only one exception. An extra query with min-width 1080px was used to fix the height of the title at the plant catalog, which changed the appearance in a very negative way. To avoid a very large broad form at the contactpage, the same min-width of 1080px was used to keep the code as short as possible, as it was already available.

### Favicon

The favicon is a beacon in all tabs opened and offers the visitor a quick reminder of the site. It is important to have a favicon that represents the website.
By using the logo making it into a favicon at [favicon](https://favicon.io) the site shows a consistancy and offers a regognizable favicon.<br>![favicon website](assets/favicon/favicon.ico)

### Navigation

As website users are used to a certain layout nowadays, best user experience is to offer the navaigation displayed in the same way as they are used to. Therefore the logo leading to the homepage is on the left and the menu with the menu-items is on the right. On small and medium screens the menu is represented with the well-known hamburger icon offering a dropdown menu when clicked on it. To avoid contrast errors the current page is not highlighted, but bolder than the other links. There is a light hover effect on the links.<br>
The navigation consists of three options. Studies have unveiled that uneven numbers of a menu are most pleasing to the mind of visitors. For a great user experience the navigation should always be available at the screen and hence sticky at any device. No need to scroll back to the top. 


### Hero section
The hero banner is a returning focus point at all pages. This is a seperate user story that indicates, that the website needs a clear image and text, which shows the visitor at a glance what can be found at this particular page. A very important aspect, as the fundamental principle of the website is being informative. The heading is a short and appealing description of what can be expected and found at the page, inviting the visitor to scroll down further.<br>
For the mobile version a smaller size of the hero image is used to garantuee an excellent performance at loading. 

### Footer
The footer shoukld be consistent at all pages of the website. This time it is not.<br>As the footer offers a signup option to subscribe to the newsletter, this won't be a neccesity at the page with the contactform, as the form already contains the option to subscribe to the newsletter. Furthermore, the simple variety of the footer is found at the 404 and thank you page. The footer stands out due to the contrast colour.<br>The form offers the option to subscribe to the newsletter with recipes. Only the names, mailaddress and if wished a message can be sent. The checkbox stating one would like to receive the newsletter is required. The button has a hover function and after being clicked a thank you page appears.


## Homepage

### Hero section
The hero banner is a returning focus point at all pages. This ia a seperate user story that indicates, that the website needs a clear image and text, which shows the visitor at a glance what can be found at this particular page. This is an important aspect as the fundamental principle of the website is being informative. For the mobile version a smaller size of the hero image is used to garantuee an excellent performance. The heading is a short and appealing description of what can be expected and found at the page, inviting the visitor to scroll down further.

### Main section
The main section comprises two parts.
<br>First to see, is a text in which is explained what can be found at the website and who will enjoy the content most - the target groups. To keep it open and readable the section is divived into more paragraphs, which on mobile screens is a must.
Second, a collection of plants is shown with bootstrap cards as basis. By touching or scrolling over the image, it is covered in an orange border, so you know, you will choose the right plant to get more information from. All images are of high quality providing the right accent of the plants to identify it generally, is clickable and linked to their plant page. Chickweed and dandelion have completed pages, all others should be filled out later (should-have).<br>
The plants are displayed in alphabetical order, which can be maintained easily in the CSS section, where the sequence is admitted (1 for a, 13 for m, 26 for z). If the database continues to grow, the first change to make is adding a 0 to all numbers. You will have 10 options for every letter to maintain the alphabetical order. Furthermore, we should add a paging bar on mobile screens (should-have), if the number of plants rises.

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
The sign-up button has a hover affect and when clicked on it, a dump form appears to show the collected data from this subscription.

## Thank you page
A thank you page appears when the form in the footer is filled out. It is a simple confirmation stating the sign-up was successful and displays a return to homepage button to keep the visitor at the site. The button has a hover effect. Eventually, the visitor can use the navigation bar, as this is displayed as well at this page.
When the contactform at the contact page is sent, the sent data is displayed in a dump form.

## 404 page
Sometimes things go wrong. This is where the 404 page comes in. <br>
As it must be clear, that something went wrong, the 404 shows a text tohether with an image that the page looking for, does not exist.<br>
To fit to the site an image of a tree is used with 404 on it, accompanied with a text that matches the subject of the site: "nothing to forage here!". With it the option to return to the homepage AND the option to send a message, makes this page a good user experience. 

## Sitemap XML page
Most websites want to be found and will only flourish, if they are found by search engines. To make it easier for search engines understanding the infrastructure of the website, a XML Sitemap is added. This XML Sitemap was generated at [XML Sitemap Generator](https://www.xml-sitemaps.com)

## Privacy Policy
At every website a privacy policy page is mandatory. As this project will not be displayed to unknown visitors, a template is used, which was generated at [Moneris](https://developer.moneris.com/More/Compliance/Sample%20Privacy%20Policy) 

[Back to top](<#contents>)


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

[Back to top](<#contents>)



# Deployment
Deployment was done with Github.

To deploy the website next steps should be taken:
1. Login to Github
2. Find the repository of the project. In this case: [CSS Angie - Food-Forest-Foraging](https://github.com/CSS-Angie/Food-Forest-Foraging)
3. Go to Pages in the navigation menu left under Settings.
5. Under branch change None to main and keep /root and click save next to these two dropdowns.
6. The site will be deployed after clicking save.
7. Return to the page "<>Code", and on the right side you'll find deployments. Clicking on it will open a new page, where you'll find the link to open the deployed site.

[Back to top](<#contents>)


# Testing
	All pages
	Validation
	Accessibility

[Back to top](<#contents>)


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

[Back to top](<#contents>)


# Acknowledgements
Gareth McGirr, my mentor, for all his help and advice throughout the project.<br>
Kristyna Wach for taking care I did not bite of more than I could chew and keeping me motivated.

[Back to top](<#contents>)



