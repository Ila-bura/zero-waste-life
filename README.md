# ZERO WASTE LIFE


<p>Zero Waste Life is a website which aims at supporting people who are looking to reduce the amount of waste they produce on a daily basis. The site is targeted to anyone who aspires to live a bit more sustainably and is ready to make some changes in their everyday life, starting in the kitchen.</p>

<p>Zero Waste Life provides useful tips and tricks to have a more sustainable approach to how we buy, consume and store food.</p>


<p>The website showcases a very simple and easy recipe to demonstrate how to use up carrots, an ingredient which more often than not tends to be forgotten in the cupboard and therefore ends up being thrown away.</p>


<p>In a dedicated page of the website, users will also be able to watch an embedded YouTube video with simple instructions on how to start composting. By following this intuitive beginner's guide, users are encouraged to start experimenting with composting in their house.</p>

<p>Additionally, users will have the chance to sign up to a monthly newsletter and receive a new seasonal recipe as well as more useful suggestions on how to reduce waste.</p>


![Screenshot of homepage displayed on different devices](/assets/images/images-readme/amiresponsive.png)

The Zero Waste Life website is live and can be accessed [HERE](https://ila-bura.github.io/zero-waste-life/index.html)


# Table of contents

- [UX](#ux)
  * [Site Purpose](#site-purpose)
  * [Audience](#audience)
  * [Communication](#communication)
- [Design](#design)
  * [Color Scheme](#typography)
  * [Typography](#typography)
  * [Imagery](#typography)
- [Wireframes](#wireframes)
- [Features](#features)
  * [Existing Features](#existing-features)
    + [Logo](#logo)
    + [Navigation Bar](#navigation-bar)
        + [Landing Page](#landing-page)
    + [Recipe Page](#recipe-page)
    + [Compost Page](#compost-page)
    + [Sign Up Page](#sign-up-page)
    + [Confirmation Page](#confirmation-page)
    + [Footer](#footer)
  * [Features to implement](#features-to-implement)
- [Testing](#testing)
  * [Media Queries](#media-queries)
  * [Validator Testing](#validator-testing)
  * [Lighthouse Testing](#lighthouse-testing)
  * [Fixed Bugs](#fixed-bugs)
  * [Peer Review](#peer-review)
  * [Unfixed Bugs](#unfixed-bugs)
- [Technologies Used](#technologies-used)
  * [Main Languages](#main-languages)
  * [Frameworks, Libraries & Programs](#frameworks--libraries---programs)
- [Deployment](#deployment)
- [Credits](#credits)
  * [Content](#content)
  * [Media](#media)
 
  
# UX

## Site Purpose

Provide useful, practical and easy to implement tips to encourage users to reduce their food waste, including simple recipes and an educational tutorial video.

## Audience

<p>Anyone who wishes to leave the world a better place and is willing to make an effort to reduce the amount of waste they produce in their daily activities.</p>

<p>The website target audience spans from young professionals to stay-at-home parents, typically in the 20 to 45 age range. What they all have in common is they are passionate about sustainability, they are mindful about what they consume and tend to prefer a vegetarian or vegan diet.</p>  

## Communication

<p>In line with the site ethos, the content is displayed in little "nuggets" of information, meant to be easily read without overwhelming the users. The text bubbles in every page are intended as "calls to action" to inform and engage the users.</p>

# Design

## Color Scheme

<p>The starting point to develop the color scheme was oriented by the intention to match the colors of the background hero video. The overall intent was to convey a sense of relaxation, with muted tones and delicate hues.</p>

<p>The Chrome extension ColorZilla was used to pick specific colors from the background image, one of which was then converted to RGBA format to match the same hue used for the background of the sections with text. ColorZilla was also used to pick a specific shade of white from the background image to be used for the form fields as well as the submit button.</p>

<p>ColorSpace was used to generate a matching gradient palette.</p> 

<p>To create a contrasting effect with the background, the logo, the main headings and the text content have a darker tone. In keeping with the intent of creating a pleasant and relaxing effect, the black color was avoided in favour of a more nuanced shade.</p>

![Screenshot of the gradient palette generated using ColorSpace.](/assets/images/images-readme/gradient-palette.png)


## Typography

<p>Cormorant Garamond was chosen as the font family for the headings, primarily in bold, to achieve a stylized and sleek final effect.</p>

<p>Source Code Pro was chosen for the body content: its unpretentious lines vaguely remind of the text produced by a typing machine and make the font aesthetically pleasing without compromising readability. The font family was created using Google Fonts.</p>

## Imagery

<p>All the imagery on the site, including the hero background video were sourced from the free stock photo platform Pexel. More information can be found in the Credits section of this document.</p>

<p>The choice behind the images and video is in keeping with the theme of the site. More specifically, the hero video was chosen to create a relaxing effect of water moving in a vase of flower. This was achieved by embedding a short clip as the hero background video. The video is set on loop, to maintain the same soothing effect while users navigate the website, without being too distracting.</p>

<p>The video was encoded using HandBrake to optimize its size and quality when displayed on mobile devices.</p>

<p>The placeholder picture is a screenshot of the video then converted to webp format.</p>


# Wireframes

The wireframes for the project were created using Balsamiq:
* Mobile Wireframe: [view](/assets/wireframes/mobile-wireframe.png)
* Tablet Wireframe: [view](/assets/wireframes/tablet-wireframe.png)
* Desktop Wireframe: [view](/assets/wireframes/desktop-wireframe.png)

# Features

## Existing Features

### Logo

<p>The logo of the website is displayed on the upper left corner of every page.</p>

<p>Lacking the skills to design a proper logo from scratch, the logo simply consists of two superimposed headings in bold: the website name "Zero Waste Life" and the mission statement or ethos "Live more sustainably", separated by a horizontal rule and wrapped in a rectangular box with a solid border.</p>


![Screenshot of the website logo](/assets/images/images-readme/logo.png)

### Navigation Bar

<p>The navigation bar is displayed across all pages and provides an intuitive reference to navigate between the different sections of the website.</p>

<p>The names of the four elements in the menu clearly state the content of each page. The links are arranged in order of information priority from left to right, beginning with the Home link, followed by Recipe, Compost and Sign Up.</p>


![Screenshot of the navigation bar](/assets/images/images-readme/navigation-bar.png)

To fix the issue of the inverted order of the menu items, after researching online, a viable solution was found on [codepen.io](https://codepen.io/ConStambo/pen/WxRQVq) by adding a float: left property to the li element, coupled with a float: right property applied to the ul element.

<p>Similar to how it was done in the Love Running walk-through project, the menu links were set to underline, to provide visual clues for the users as to what link they are about to click on when they hover over it.</p>

### Landing Page

<p>The landing page welcomes the users with an unobtrusive and relaxing effect of water moving in a vase of flower, created by embedding a short clip as the hero background video. This is a recurring feature that is displayed in every single page of the website.</p>

<p>Listed in the central part of the homepage we can find a selection of useful tips and tricks the users are encouraged to implement in their life. The main content was displayed directly on the landing page on purpose, so that users can easily and readily access it.</p>


![Screenshot of the landing page](/assets/images/images-readme/home-tricks.png)


<p>On the right, below the menu, a nugget of information is displayed in a bubble, which provides an interesting fact about how much fruit and vegetables is wasted every year.
</p> 


![Screenshot of the home bubble](/assets/images/images-readme/home-bubble.png)

<p>The last item in the Tips & Tricks list provides a clickable link directing users to the Compost page within the website. The link changes color to a vibrant shade of green when users hover over it with their cursor:</p>

![Screenshot of the compost link](/assets/images/images-readme/link-to-compost.png)


### Recipe Page

The Recipe page is dedicated to one single recipe, specifically chosen to promote the fight against food waste. The content - the list of ingredients and method - was adapted from an original recipe by the vegan food blogger [Max La Manna](https://www.maxlamanna.com/recipes/carrot-fritters).

<p>The body of the recipe page is horizontally divided into three parts: the ingredients and method columns are separated by the image of the finished dish.</p>

<p>As a side note, finding a free stock photo of precisely a platter of carrot fritters proved harder than anticipated. For this reason, the picture chosen for the recipe page is actually a picture of a platter of zucchini fritters, which was deemed representative enough to match the recipe.</p>

<p>The image is styled with a circular container, as learnt in the Love Running walk-through project.</p>

![Screenshot of the recipe page](/assets/images/images-readme/recipe-page.png)

<p>On the right below the menu, we can find another bubble with an engaging call to action, inviting users to try the recipe.</p>

![Screenshot of the recipe bubble](/assets/images/images-readme/recipe-bubble.png)

<p>In a future iteration, this section will be expanded to host more recipes.</p>

### Compost Page

<p>The Compost page is where users can watch a video about composting and learn more about it.</p>

The video was sourced from [YouTube](https://www.youtube.com/watch?v=egyNJ7xPyoQ) and embedded into the page.

<p>The video does not autoplay and the YouTube controls were kept. The "loop" feature is on, so that the effect of water moving in the vase never ends.</p>

<p>The video is relatively short (around 3 minutes) but with clear and simple instructions on how to get started with composting at home.</p>
In keeping with the essential ethos of the website, the video is not intended to provide an exhaustive guide to composting, rather to captivate the users in a fun and engaging way, based on the assumption that the vast majority of the Zero Waste Life's users are absolute beginners and have never tried composting before.</p>

### Sign Up Page

<p>In the Sign Up page users are presented with a form they are invited to fill in with their details, as well as the food they tend to waste the most. 
The first name field is set to autofocus, to improve user's experience.</p>

<p>The form was created for educational purposes only and once the Submit button is clicked, users are simply directed to a confirmation page, where a thank you message is displayed. This was achieved by adding the path "Confirmation.html" to the form action.</p>

![Screenshot of the sign up form](/assets/images/images-readme/signup-form.png)

<p>For consistency, also on this page another bubble message is displayed, once again inviting the users to take action: in this case, they are encouraged to subscribe to the Zero Waste Life newsletter.</p>

![Screenshot of the sign up bubble](/assets/images/images-readme/signup-bubble.png)

### Confirmation Page

<p>Users land on this page after submitting their details in the Sign Up page. The thank you message sets the expectations regarding the content and frequency of the newsletter: users can expect to receive a new recipe and more tips and tricks on a monthly basis.</p>

The last line informs the users that they will be soon redirected to the Home page. 
To learn how to implement this feature, I researched the topic online and followed the instructions found on [HubSpot](https://blog.hubspot.com/website/html-redirect). The page is set to refresh after a few seconds to give users the chance to read the confirmation message.

![Screenshot of the confirmation message](/assets/images/images-readme/confirmation-message.png)

<p>Once again, for consistency, another bubble message is displayed, this time congratulating the users on signing up to the newsletter.</p>

![Screenshot of the confirmation bubble](/assets/images/images-readme/confirmation-bubble.png)

### Footer

<p>Links to the main social media platforms can be found at the bottom of each page. All the links are set to open in a separate tab.
Below the social media row, a line was added with the project creator's name. By clicking on it, the hyperlink opens the corresponding GitHub account in a separate tab.</p>

![Screenshot of the footer](/assets/images/images-readme/footer.png)

## Features to implement

* Expand the Recipe section to include more recipes and a photo gallery.

* Create dedicated pages with tips and tricks to implement in other areas that are not related to food, such as clothing, packaging and household maintenance.

# Testing

Testing was carried out throughout the entire build. Chrome DevTools was used to pinpoint and troubleshoot any issues along the way.

<p>The following issues were raised during the mid-project meeting with my mentor: 

<li>Absolute vs. relative path: the following error was displayed in Chrome DevTools:


 ![Screenshot of the 404 message](/assets/images/images-readme/placeholder-error.png)

Solved by fixing the file path to "../images/placeholder.webp".</li>
<li>My mentor recommended consistency in the use of either underscore or dash as a naming convention for classes and ids in my code. This was implemented by choosing to use a dash to separate words in names.</li>
</p>

## Media Queries

The most challenging part of the project was creating the media queries to ensure responsiveness on different devices. 

<ul>
<li>The first issue I needed to tackle was the less than optimal readability of some of the content, when viewed on smaller screens, mainly due to the design of the background hero video. I solved this by adding a contrasting background color to the navigation bar as well as the hook bubble. In keeping with the color palette created for the project, I applied the same RGBA color value used for the body, to ensure improved readability against the background.
</li>

![Screenshot of the menu and hook text with colored background](/assets/images/images-readme/hook-menu-small-screens.png)

<li>Next, I had to reposition the image in the Recipe page: as it is normally displayed between two columns hosting the ingredients and the method, it was decided to add the float: left property to have the image displayed below the two columns. 
Furthermore, the size of the original fritters image is 300x300 pixels and proved to be too big for smaller screens, therefore it was resized to approximately 50% of its original size (153x150 pixels). 
As a side note, it is worth noticing that the resized picture only features a single fritter, rather than the whole platter. This was done intentionally in order to preserve the quality of the resized image.
</li>
</ul>

![Carrot fritters original image](/assets/images/carrot-fritters.webp)

![Carrot fritters resized image](/assets/images/single-fritters-resized.webp)


## Validator Testing
The W3C validator was used to validate the HTML code of all the pages of the website. It was also used to validate the CSS code in the style.css file. No errors were found in any of the files.

* Index Page HTML: [view](/assets/images/images-readme/W3C/W3C-index.png)
* Recipe Page HTML: [view](/assets/images/images-readme/W3C/W3C-recipe.png)
* Compost Page HTML: [view](/assets/images/images-readme/W3C/W3C-compost.png)
* Sign Up Page HTML: [view](/assets/images/images-readme/W3C/W3C-signup.png)
* Confirmation Page HTML: [view](/assets/images/images-readme/W3C/W3C-confirmation.png)
* style.css CSS: [view](/assets/images/images-readme/W3C/W3C-CSS.png)


## Lighthouse Testing

I used Lighthouse within the Chrome DevTools to test the performance, accessibility, best practices and SEO of the website.
Lighthouse initially flagged that the hyperlink in the Compost page did not have a descriptive text ("Learn how to compost here"). 
I researched the matter [here](https://developer.chrome.com/docs/lighthouse/seo/link-text/?utm_source=lighthouse&utm_medium=devtools) and solved by changing the hyperlink to a more descriptive text: "Learn how to compost".

Every single page of the website was then retested using Lighthouse with excellent accessibility scores:

* Home Page: [Desktop](/assets/images/images-readme/Lighthouse/lighthouse-homepage-desktop.png) - [Mobile](/assets/images/images-readme/Lighthouse/lighthouse-homepage-mobile.png)
* Recipe Page: [Desktop](/assets/images/images-readme/Lighthouse/lighthouse-recipe-desktop.png) - [Mobile](/assets/images/images-readme/Lighthouse/lighthouse-recipe-mobile.png)
* Compost Page: [Desktop](/assets/images/images-readme/Lighthouse/lighthouse-compost-desktop.png) - [Mobile](/assets/images/images-readme/Lighthouse/lighthouse-compost-mobile.png)
* Sign Up Page: [Desktop](/assets/images/images-readme/Lighthouse/lighthouse-signup-desktop.png) - [Mobile](/assets/images/images-readme/Lighthouse/lighthouse-signup-mobile.png)


## Fixed Bugs

* The menu items were originally displayed in reverse order: the Sign Up link was aligned to the left and the Home link to the right. This occurred because of the float: right property which floated the menu items in order of their appearance in the code. 
In the Love Running walk-through project the same issue was solved by reordering the menu items in the code to suit the float property.
I researched the matter and found a viable solution using CSS: I added float: right to the ul and float: left to the li.
The source for this piece of code can be found on [Stack Overflow](https://stackoverflow.com/questions/20920265/horizontal-menu-how-to-float-right-but-keep-the-menu-items-in-the-correct-order=).


* Soon after adding the footer section, I noticed that the footer did not stick to the bottom of the page and it changed its position depending on how much content was displayed on the page. I researched the issue and tackled it by creating a page container to wrap all of the content: its minimum height was set to 100% of the viewport height and I added a relative property to it. 
Then I added a div to wrap all of the page content except for the footer. Using CSS, I set the footer position to absolute. Finally, I gave the content wrap a bottom padding with the same height of the footer.
The source for this piece of code can be found [here](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/).


* Improved appearance of the hero background video for iPhone4. I researched the topic and found a viable solution to resize the hero background to be responsive when displayed on smaller screens [here](https://discourse.webflow.com/t/background-video-responsive-size/81825).

## Peer Review 

A peer review was requested using the Code Institute peer-code-review Slack channel. Carl Murray suggested the following improvements:
* Increase the opacity of the green background, to ensure better readability. This was implemented by increasing it from 0.6 to 0.7 in all instances where the green background was used, including the media queries. 
* Reduce the refresh time once the confirmation message is displayed. This was implemented by reducing it from 15 to 7 seconds.


## Unfixed Bugs

# Technologies Used

## Main Languages

* HTML5
* CSS3

## Frameworks, Libraries & Programs

* [Balsamiq](https://balsamiq.com/): used to create wireframes.
* GitPod: for version control before pushing the project to Github.
* GitHub: to save and store the files for submission.
* [Google Fonts](https://fonts.google.com/): for the font families Source Code Pro, Cormorant Garamond. San-serif was used as a default font.
* Font Awesome: to add icons to the Tips & Tricks list as well as the social media links in the footer.
* [ColorSpace](https://mycolor.space/): to create the gradient palette.
* ColorZilla: to pick specific colors from web pages.
* Google DevTools: to troubleshoot and test features, solve issues with responsiveness and styling.
* [Adobe Express](https://www.adobe.com/express/feature/image/resize): to resize and compress images. 
* HandBrake: to encode the hero video.
* [birme.net](https://www.birme.net/?target_width=300&target_height=300&image_format=webp&quality_jpeg=100&quality_webp=100): to convert pictures to webp format.
* [favicon.io](https://favicon.io/): to generate the image for the icon in the tab bar.
* [Am I Responsive?](https://ui.dev/amiresponsive): to ensure the project looked good across all devices.
* [Spell Checker for Chrome](https://chrome.google.com/webstore/detail/spell-checker-for-chrome/jfpdnkkdgghlpdgldicfgnnnkhdfhocg): to validate spelling.

# Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

<ol>
<li>Log in (or sign up) to Github.</li>
<li>Find the repository for this project, zero-waste-life.</li>
<li>Click on the Settings link.</li>
<li>Click on the Pages link in the left hand side navigation bar.</li>
<li>In the first section displayed, the live Github Pages site is now deployed at the URL shown.</li>
</ol>

![Screenshot of the deployed site on GitHub](/assets/images/images-readme/deployed-site-github.png)

# Credits


## Content

* The initial set up for this project was inspired by the 'Love Running' walk-through project. In particular, a similar approach was taken for the design of the navigation bar, along with the display of the social links in the footer element.

* To learn how to embed a hero background video I researched the topic and followed the instructions found on [ToolTester](https://www.tooltester.com/en/blog/how-to-embed-a-hero-background-video/) and [here](https://www.htmlandcssbook.com/extras/encoding-videos-for-the-web).

* The issue with the reversed order of floating menu to the right was solved by applying the code found on: [codepen.io](https://codepen.io/ConStambo/pen/WxRQVq) and [stack overflow](https://stackoverflow.com/questions/20920265/horizontal-menu-how-to-float-right-but-keep-the-menu-items-in-the-correct-order). 

* The piece of code used to make the background video responsive can be found [here](https://discourse.webflow.com/t/background-video-responsive-size/81825).

* To learn how to make the footer stick to the bottom, I applied the code suggested [here](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/).

* The piece of code used to set the homepage to load after a certain amount of time was found on [HubSpot](https://blog.hubspot.com/website/html-redirect).

## Media

The video with the vase of flowers used as a hero background was downloaded from Pexels and the author is [Artem Podrez](https://www.pexels.com/video/decorative-flower-in-glass-vase-against-white-background-4884243/).
The placeholder picture is a screenshot of the video then converted to webp format.

The picture of the fritters used in the recipe page was downloaded from Pexels and the author is [Morena Vw](https://www.pexels.com/photo/zucchini-fritters-with-tomatoes-and-green-vegetables-on-white-ceramic-plate-6911885/).  