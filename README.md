# ZERO WASTE LIFE


Zero Waste Life is a site which aims at supporting people who are looking to reduce the amount of waste they produce on a daily basis. The site is targeted toward anyone who wish to be a bit more sustainable and is ready to make some changes in their everyday life, startuing in the kitchen. Zero Waste Life will provide useful tips and tricks to have a more sustainable approach to how we buy, consume and store food.
The site will showcase a very simple and easy recipe to demonstrate how to use up carrots, an ingredient which is more often than not forgotten in the cupboad and therefore tends to be thrown away.
In a separate page of the site users will be able to watch a YouTube video with simple instructions on how to start composting, in the hope to encourage users to experiment with compostinmg in their house.
Users will also have the chance to sign up to a monthly newsletter and receive useful suggestions on how to reduce waste as well as a new seasonal recipe.

Zero Waste Life website is live and can be accessed by clicking [HERE](https://www.google.com)



# Table of contents

# UX

## Site Purpose
Provide useful and practical and easy to implement tips to encourage users to reduce food waste, including simple recipes and an educational tutorial video.

## Audience
Anyone who wish to leave the world as a better place and is willing to make an effort to reduce the amount of waste they produce in their daily activities. Our target audience spans from young professionals to stay-at-home parents, typically in the 20 to 45 age range. What they all have in common is they are passionate about sustainability, they carefully choose what to consume and they tend to prefer a vegetarian or vegan diet.  

## Communication
In line with the site ethos, the content is displayed in little "nuggets" of information, meant to be easily read without overwhelming the users. The text bubbles in every page are intended as "calls to action" to engage the users.

# Design


## Color Scheme
The starting point to develop a color scheme was inspired to match the colors in the picture chosen to be the background image for the site. The overall intent was to convey a sense of relaxation, with muted tones and delicate hues. The Chrome extension ColorZilla was used to pick specific colors from the background image, one of which was then converted to RGBA format to match the same hue for the background of the sections with text. ColorZilla was also used to pick a specific shade of white from the background image to be used for the form fields as well as the submit button.
ColorSpace was also used to generate matching gradient palette. 
To create a contrasting effect, the logo, the main headings and the text content have a darker tone. In keeping with the intent of creating a pleasant and relaxing effect, the black color was avoided in favour of less extreme shades.

![Screenshot of the gradient palette generated using ColorSpace.](/assets/images/images-readme/gradient-palette.png)



## Typography
Cormorant Garamond was selected as the font family for the headings, primarily in bold, to achieve a stylized and sleek final effect. On the other hand, Source Code Pro was chosen for the body content: its unpretentious line vaguely remind of the text produced by a typing machine, which make the font esthetically pleasing yet keeping it easy to read. The font family was created using [Google Fonts]( https://fonts.google.com/).

## Imagery
The images and background video used for this website were sourced from the free stock photo platform Pexel.
The video withe the vase of flowers used as a background is by Artem Podrez and can be found [here](https://www.pexels.com/video/decorative-flower-in-glass-vase-against-white-background-4884243/).
The placeholder picture is a screenshot of the video then converted to webp format, using [birme.net](https://www.birme.net/?target_width=300&target_height=300&image_format=webp&quality_jpeg=100&quality_webp=100).

The picture of the fritters used in the recipe page is by Morena Vw and can be found [here](https://www.pexels.com/photo/zucchini-fritters-with-tomatoes-and-green-vegetables-on-white-ceramic-plate-6911885/). As a side note, finding a free stock photo of precisely carrot fritters proved harder than anticipated, therefore eventually this zucchini fritters was chosen as a representative enough image to match the recipe.

The fritters image was resized and compressed using [Adobe Express](https://www.adobe.com/express/feature/image/resize).

The favicon was created using the online generator available on [favicon.io](https://favicon.io/).


# Current Features

## Existing Features

### Logo
The logo can be seen on the upper left corner of every page of the website. Lacking the skills to design a proper logo from scratch, the logo is made up by two headings in bold: the website name "Zero Waste Life" and the mission statement/ethos "Live more sustainably", separated by a horizontal rule and wrapped in a rectangular box with solid border.

![Screenshot of the website logo](/assets/images/images-readme/logo.png)

### Navigation Bar
The navigation bar is displayed across all pages and provides an intuitive reference to navigate between the different sections of the website. The names of the four elements in the menu clearly state the content of each page.


![Screenshot of the navigation bar](/assets/images/images-readme/navigation-bar.png)

To fix the issue of the inverted order of the menu items, after researching online, a viable solution was found on [codepen.io](https://codepen.io/ConStambo/pen/WxRQVq) by adding a float:left property to the li element coupled with a float:right property applied to the ul element.

Similar to how it was done in the Love Running walkthrough project, the menu links were set to underline to provide visual clues for the user as to what link they're about to click on when they hover over it with the cursor.

### Landing Page
The landing page welcomes the users with a relaxing effect of water moving in a vase of flower, created by embedding a short clip as the hero background video. The video is set on loop, to maintain the same soothing effect while users navigate the website but without being too obvious.

To learn how to embed a hero background video I reserached the topic and followed the instructions found on [ToolTester](https://www.tooltester.com/en/blog/how-to-embed-a-hero-background-video/).
The video was encoded using HandBrake, after researching the subject [here](https://www.htmlandcssbook.com/extras/encoding-videos-for-the-web).
This allowed me to optimize the size and quality of the hero video to fit devices.

Listed in the central part of the homepage we can find useful tips and tricks the users are encouraged to implement in their life. The main content was on purpose displayed on the landing page, to be easily and readily accessible.


![Screenshot of the landing page](/assets/images/images-readme/home-tricks.png)


On the right, below the menu, a nugget of information is displayed in a bubble to provide an interesting fact about how much fruit and vegetables are wasted every year. 


![Screenshot of the home bubble](/assets/images/images-readme/home-bubble.png)

The last item in the Tips & Tricks list provides a clickable link directing users to the Compost page within the website. The link changes color to a vibrant shade of green when users hover over it with their cursor:

![Screenshot of the compost link](/assets/images/images-readme/link-to-compost.png)


### Recipe Page
The Recipe page is dedicated to one single recipe, specifically chosen to promote the fight against food waste. The list of ingredients and method content was adapted from an original recipe by [Max La Manna](https://www.maxlamanna.com/recipes/carrot-fritters).
The body of the recipe page is horizontally divided into three parts: the ingredients and method columns are separated by an image in between. As a side note, finding a free stock photo of carrot fritters proved harder than anticipated, therefore a picture of zucchini fritters was chosen instead as it appropriately matches the recipe. The image is styled with a circular container, as learnt in the Love Running walkthough project.

![Screenshot of the recipe page](/assets/images/images-readme/recipe-page.png)

Once again on the right, below the menu we can find a bubble with an engaging call to action, inviting users to try the recipe.

![Screenshot of the recipe bubble](/assets/images/images-readme/recipe-bubble.png)

In a future iteration, this section could be expanded to host more recipes.

### Compost Page
The Compost page is where Users can watch a video about composting and learn more about it. The video was sourced from [YouTube](https://www.youtube.com/watch?v=egyNJ7xPyoQ) and embedded into the page. The video does not autoplay and the YouTube controls were kept.
The video is relatively short (around 3 minutes) but with clear and simple instructions on how to get started with composting at home. In keeping with the essential ethos of the website, the video was not intended to provide a fully comprehensive guide to composting, rather to captivate the users in a fun and engaging way, based on the assumption that the vast majority of our users have never tried composting at all.

### Sign Up Page
In the Sign Up page users find a form they are invited to fill in with their details as well as the food they tend to waste the most. The first name field is set to autofocus, to improve user's experience. The form was created for educational purposes only and once the Submit button is clicked, users are simply directed to the confirmation page, where a thank you message is displayed. This was achieved by adding the path Confirmation.html to the form action.

![Screenshot of the sign up form](/assets/images/images-readme/signup-form.png)

For consistency, also on this page a bubble message is displayed, once again inviting the users to take actions: in this case to subscribe to the Zero Waste Life newsletter.

![Screenshot of the sign up bubble](/assets/images/images-readme/signup-bubble.png)
### Confirmation Page
Users land on this page after submitting their details in the Sign Up page. The thank you message sets the expectations regarding the content and frequency of the newsletter: users can expect to receive on a monthly basis a new recipe and more tips and tricks to implement in their life.
The last line informs the users that they will be soon redirected to the Homepage. 
To learn how to implement this feature, I researched the topic online and followed the instructions found on [HubSpot](https://blog.hubspot.com/website/html-redirect).

![Screenshot of the confirmation message](/assets/images/images-readme/confirmation-message.png)

Once again, for consistency, another bubble message is displayed, this time congratulating the users on signing up to the newsletter.

![Screenshot of the confirmation bubble](/assets/images/images-readme/confirmation-bubble.png)

### Footer
Links to the main social media platforms can be found at the bottom of each page. All the links are set to open in a separate tab.
Below the social media row, a line was added with the student's name. By clicking on it, the hyperlink opens the student's GitHub account in a separate tab.

![Screenshot of the footer](/assets/images/images-readme/footer.png)

## Features to implement
Expand the Recipe section to include more recipes and a photo gallery.
Create dedicated pages with tips and tricks to implement in other areas of life, that are not related to food, such as clothing, packaging and household maintenance.

# Testing

## Validator Testing
## Fixed Bugs
## Unfixed Bugs

# Technologies Used
## Main Languages
HTML5
CSS3
## Frameworks, Libraries & Programs
Google Fonts: for the font families: Source Code Pro, Cormorant Garamond. San-serif was used as a default font.
Font Awesome: to add icons to the Tips & Tricks list as well as the social media links in the footer element.
GitPod: to create the html files and styling sheet before pushing the project to Github.
GitHub: to store the repository for submission.
Balsamiq: used to create mockups of the project prior to starting.
Am I Responsive? - to ensure the project looked good across all devices.
Favicon: to generate the image for the icon in the tab bar.

# Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found [HERE](https://www.google.com)

# Credits

## Content
## Media