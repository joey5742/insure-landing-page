# Frontend Mentor - Insure landing page solution

This is a solution to the [Insure landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/insure-landing-page-uTU68JV8). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- (#overview)
  - (#the-challenge)
  - (#screenshot)
  - (#links)
- (#my-process)
  - (#built-with)
  - (#what-i-learned)
  - (#Continued-Development)
  - (#useful-resources)
  - (#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](design/Insure-landing-page_1440px.png)
![](design/Insure-landing-page_375px.png)

### Links

- Solution URL: [https://joey5742.github.io/insure-landing-page/](https://your-solution-url.com)
- Live Site URL: [https://joey5742.github.io/insure-landing-page/](https://your-live-site-url.com)

## My process

The first thing I did was review the design for Insure landing page for the full screen and the mobile version. After this review I made some notes about what type of CSS properties would be needed to create a responsive webpage. This included using just flexbox within the webpage. In addition, pseudo elements were needed to create the different active states for the links. 

HTML coding was completed first based on the design of the completed website. The challenge was to include both the desktop and duplicate mobile images without creating extra HTML coding. Another challenge was to include both navigation menu for desktop and mobile versions. Both these challenges required using appropriate class and id selectors.

-- Mobile Version

I started with a mobile first design workflow.  Most of the coding was for CSS except for the mobile hamburger menu. This required adding JavaScript to create a mobile navigation when clicking on the hamburger icon. The hamburger icon was suppose to change into an "X" icon when clicked; however, I was unable to adjust the JavaScript code to create this effect. Instead, it changes into the X icon upon hovering over the hamburger icon.  In addition, the design required using mobile images that were duplicates of the desktop images but smaller. Therefore, class id's were required to exclude the desktop version of images but include the mobile images. The rest of the styling was pretty straightforward because the design showed that everything was laid out in a single column except for the images before the footer which were set into two columns. 


-- Desktop Version 

After completing the mobile version, I set up a new viewport for desktop screens with a minimum width of 1100px. Starting from the top of the page it was clear that the line designs used throughout the webpage had to be placed using absolute positioning. There was a lot of trial and error in order to get these items in the right place to match the design image. In addition, there was the issue of correctly placing the family picture on the top frame. 

The next group of frames included both images and text. These were layed out using flex. Two of the sections on the page included square button links that was to have a hover effect. The hover effect was to impact the color of the background and of the text. 

Most of the sections were fairly simple to layout, they just required adding some white space between sections and a couple of the sections were designed to be less wide than others. 

The design for the footer appeared to use a different background color then what was listed on the style guide. In addition, the footer was a little more complex to complete because it combined different styles. It included a section with the logo and social icons along with another section that included 4 columns of links. Another issue with the footer was that the "active-states" design image showed that the social icons were to be darkened on hover. In order to change the hover state on the social icons, I used the Filter design element.  This required some trial and error with the 4 different aspects of the filter element. 



-- Tablet Version 

The tablet version combines items from the desktop and mobile versions. It is for screens between 700px and 1100px wide. It uses the mobile version of the family image however, the layout is simillar to the desktop version.   


### Built with

- Semantic HTML5 markup
- CSS custom properties
	- Flexbox
	- CSS pseudo elements (hover)
- JavaScript

### What I learned

	1. This activity helped me to learn more about when to use absolute and relative positioning in designing a webpage. 
	2. I learned effective ways to use selectors to style specific items on a webpage without effecting other parts of the page. 
	3. While researching, I learned how to search effectively including finding out which sites are most helpful and which sites to avoid. 
	4. I learned the importance of responsive design and it should be used throughout your CSS code. 


### Continued development

	1. Learning more about creating efficent HTML and CSS code to not use uneccessary code.
	2. Continue developing skills needed to develop responsive sites that smoothly transition for different screen sizes. 
	3. Increase knowledge of JavaScript to include interactive elements to websites. 
	
### Useful resources

	- StackOverflow.com - This site is used as a forum for solutions to various CSS, HTML or JavaScript questions. It helped me when I had a problem with the mobile navigation that opened automatically when the page is loaded instead of through the hamburger icon.
	- css-tricks.com - I used this site to help create responsive grids. It was also good in learning about how to use the after pseudo element. 
	- w3schools.com - This is a good resource on many basic CSS or HTML topics.

## Author

- Website - Joey S. 
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
got some inspiration from someone else's solution. This is the perfect place to give them some credit.

