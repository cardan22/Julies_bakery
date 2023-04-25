# Julie's Bakery

Link to live website: [Julie's Bakery](https://cardan22.github.io/Julies_bakery/)

![Mockup of Julie's Bakery website](/assets/images/readme-images/julies-bakery-mockup-light.png)

# About
The Julie's Bakery website is made to feel cozy and friendly, just like the bakery itself. It's easy to use and helps visitors find important information like course sign-ups, location, and how to contact the bakery. The website aims to make customers happy and keep them coming back by providing a fun and easy online experience that matches the warm and welcoming feeling of the bakery. 

# UX

## User Demographic
This website is for:
* People interested in baked goods and desserts, such as cakes, pastries, and bread.
* People who enjoy baking as a hobby and want to learn new techniques and recipes by taking a course.
* People who plan to visit the bakery. 

## User stories
* As a new resident in the area, I want to easily access information about Julie's Bakery, including its location and hours of operation, so that I can plan my visit.
* As a regular customer of Julie's Bakery, I want to be able to view the bakery's latest specials and promotions, so that I can take advantage of any discounts or new menu items.
* As a person interested in learning new baking skills, I want to find a baking course that I can enroll in so that I can improve my baking knowledge and techniques.

## User goals
* To find information about Julie's Bakery, such as it’s location, opening hours in order to plan a visit to the bakery
* Sign up to baking and pastry courses
* Contact the bakery

## Design
My goal was to create a website to feel like the bakery and show how they are related. I also want visitors to easily understand what the website is for and what it's all about.

## Wireframes
* I used Figma to design wireframes, which helped me to create a visual representation of the website's appearance.
* The website was completed with only minor differences from the original plan, although a few parts were exluded from the footer.

(screenshot here)

## Colours
I got inspiration from the specific color palette below but modified it to match Julie's Bakery's branding.

(Screenshot here)

## Typography
Using Playfair Display for headings and Didact Gothic for body text results in a modern and seamless design that connects with the Julie's bakery's logo and brand, while also making the text easy to read and understand.

## Logo
* The bakery's logo, which features a simple text and a lemon symbol, was personally designed by me.

# Features
The Julie's Bakery website is made up of three pages:

* Home
* Courses
* Contact

## Existing Features

### Header and Navigation Section

* The fully responsive navigation bar is included on all three pages of the Julie's Bakery website. It contains links to the home page, courses, and contact page. On screens smaller than 768px, the navigation bar is replaced with a hamburger menu.
* The navigation section of the website enables users to move easy from one page to another, regardless of the device they are using. This means they won't need to use the back button to return to a previous page.

![Header and navigation](/assets/images/readme-images/header-navigation.png)

### Hero section

* The Hero section of the website includes Hero image, header and a paragraph.
* The section introduces the user to Julie’s bakery with a image that evokes the warm and inviting atmosphere of the bakery, along with a header and a paragraph of text that provide users with a clear understanding of what the website is about.

![Hero section](/assets/images/readme-images/hero-section.png)

### Pastry of the month section

* Pastry of the month section highlights a featured pastry chosen for that particular month, along with a short text and price.
* This section will make the user crave to visit the bakery for a treat.
* The section will be updated monthly with a new featured pastry.

![Pastry of the month section](/assets/images/readme-images/pastry-section.png)

### Baking and Pastry Courses

* This section contains a photo, text and a call-to-action botton.
* This section tells you why you should take a course at Julie's Bakery. Visitors can click on the call-to-action button to read more and sign up for a course.

![Baking and Pastry Courses section](/assets/images/readme-images/courses-section.png)

### Instagram feed

* This section displays Julie's Bakery's Instagram feed.
* Keeps visitors up-to-date with the latest news and events from Julie's Bakery, through their Instagram account. It's automatically updated on a weekly basis.

(Screenshot here)

### Footer

* The footer includes the logo, opening hours, contact information and copywright.
* It serves the purpose of providing users with essential information that they may need to reach out to or visit the bakery.

![Footer](/assets/images/readme-images/footer.png)

### Courses page header

* The courses page header includes background image, header and a paragraph.
* The combination of the photo and text captures the user's attention and motivates them to navigate and read more on the webpage.

![Courses page header](/assets/images/readme-images/courses-header.png)

### Baking and Pastry courses section

* This section contains three blocks with text and photos: Sourdough Bread, Pastry Course, and Learning to Decorate. 
* TProvides users with details about the upcoming baking and pastry course, including information on course content, dates and times, and the course fee.

![Baking and Pastry courses section](/assets/images/readme-images/courses-columns.png)

### Signup form 

* Signup form for the courses.
* The signup form enables users to register for one or multiple baking classes by submitting their full name, phone number, email address, and course.

![Signup form for courses](/assets/images/readme-images/form.png)

### Quote section

* This section contains a headline and a paragraph.
* This section includes a quote from a student who has taken a baking class at Julie's Bakery, providing users with feedback on the course and encouraging them to enroll. The quotation will be updated regularly.

![Quote section](/assets/images/readme-images/quote.png)

### Contact us header

* The contact us page header includes background image, header and a paragraph.
* This section includes a photo and brief text explaining why the user might want to contact the bakery.

(screenshot here)

### Contact section

* This section consists of three blocks, containing text and icons.
* This section gives important information to users who may be interested in visiting or contacting the bakery. By displaying the bakery's opening hours, location, and contact information, the website makes it easy for users to plan their visit or get in touch with any questions or concerns they may have.

(screenshot here)

### Google map

* The section includes an embedded Google Map with the bakery's address.
* The Google Map helps users to visually locate the bakery's address and navigate to it more easily.

(screenshot here)

### Submit page

* The submit page include a photograph and a short thank you text, navigation and logo.
* Providing users with a confirmation message after they have submitted their application of the course.

(Screenshot here)

### Back to top botton

* A sticky back to top button
* The button remains visible on the screen as the user scrolls, allowing them to easily navigate back to the top of the page with just one click. 

(Screenshot here)

# Technologies Used

* [HTML](https://sv.wikipedia.org/wiki/HTML) 
* [CSS](https://sv.wikipedia.org/wiki/Cascading_Style_Sheets)
* [JavaScript](https://sv.wikipedia.org/wiki/Javascript)

# Testing

* 
* 

## List of main issues:

The toggle menu fails to remain hidden off-screen, even when it is supposed to be hidden.
* The solution was to add the CSS code "body { overflow-x: hidden; }" to the media query. This will disable horizontal scrolling and ensure that the toggle menu remains hidden off-screen.

The image in the flexbox was leaving a small space at the bottom. 
* The solution was to add the following CSS property: { display: block; }.

The logo was appearing pixelated and unclear.
* The solution was to use SVG file for the logo instead of PNG.


# Development and Deployment

The development environment used for this project was GitPod. Regular commits and pushes to GitHub were performed to manage version control and track the development stage. A Code Institute-provided template was used to set up the GitPod environment.
The live version of the project is deployed at GitHub pages.

To deploy the project, follow the "Creating your site" instructions provided in GitHub Docs, which involved these steps:
1.	Sign in to [GitHub](https://github.com/).
2.	Find the repository that you want to deploy.
3.	Click on "Settings" at the top of the repository.
4.	Scroll down to the "GitHub Pages" section and click "Check it out here!"
5.	In the "Source" section, select "main" as the branch and "root" as the folder, then click "Save".
6.	The website will be deployed, and the page will automatically refresh to display the link to the live project.

You can find the link to the project [here.](https://cardan22.github.io/Julies_bakery/)

# Credits

## Content

* I followed a tutorial by [@EasyTutorialsVideo](https://www.youtube.com/watch?v=oYRda7UtuhA) on YouTube to create the header section with an image and text.
* To implement the toggle menu, I used the same tutorial as above. [@EasyTutorialsVideo](https://www.youtube.com/watch?v=oYRda7UtuhA)
* My mentor recommended using flexbox for the layout, and I practiced using it by playing the game [Flexbox Froggy](https://flexboxfroggy.com/).
* For the Instagram feed widget, I used the service provided by [ElfSight](https://elfsight.com/), which offers customizable social media widgets that can be easily embedded into websites.
* I got the code snippet for the "back to top button" from [w3schools.com](https://www.w3schools.com/howto/howto_js_scroll_to_top.asp).

## Media

* The photos are downloaded from [Unsplash](https://unsplash.com/) and are available for free use, for commercial or non-commercial purposes.
* The logo are designed by myself.



[Back to top](#julies-bakery)