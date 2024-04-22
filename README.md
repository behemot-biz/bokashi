# Bokashi Simplified - A beginners guide
## Introduction

### Project Description
[Bokashi Simplified](https://behemot-biz.github.io/bokashi/)
is a site about bokashi composting, an efficient, anaerobic process that uses a specific group of microorganisms to ferment kitchen waste. 
### Project Purpose
My aim with this site is to demystify the concept and encourage people to give it a try with a very basic step-by-step guide without overwhelming with technical and scientific text.

I use my own knowledge on the subject, and I remember how daunted I felt before I dared to get going four years ago. 

### Look and feel on different devices
![Responsive image example](readme-images/amiresponsive.png)


## User Stories
Bokashi simplified is designed to educate and engage visitors on the benefits of the bokashi method for economy, environment, and agriculture. The website consists of a homepage, a step-by-step guide, and a contact page.

### Homepage Visitor
**User story:**  As a new visitor, I want a clear and welcoming introduction, so that I can quickly understand what the website is about.

**End user goal:** I can quickly understand what the website is about and decide if it has the information I'm looking for.

### Guide User
**User story:**  As a user who needs help with the process covered by the guide, I want a clear and easy-to-understand step-by-step guide.

**End user goal:** I can easily follow each step and complete the process without confusion

### Contact Page User
**User story:**   As a user who needs additional help or has specific questions, I want to be able to fill out and send a simple contact form.

**End user goal:** I can quickly contact the people responsible for the website and get answers to my questions.

### Website Owner
**User story:**  As the owner of the website, I want the website to effectively communicate the benefits of the method through a well-structured homepage and a detailed step-by-step guide.

**End business goal:**  Visitors not only understand how the method works and the benefits it offers but are also motivated to try the method and possibly share the information with others.

### Conclusion
These user stories are designed to ensure that the website meets the needs of both its users and me as the owner, focusing on clarity, engagement, and actionable outcomes. They guide the development and content strategy to maximize the impact and usability of the website.

## Design decisions
### Fonts
I wanted contrast between headlines and bread text, I used the site fontpair.co for inspiration. 
I decided to use Playfair Display for all headlines and Source Sans 3 for bread text.

A quite funny thing, later when I was looking around for some inspiration, I found the same headline font on a Swedish site, selling all things needed for bokashi composting, bokashi.se, so I guess it was a good choice.

### Colours
I selected brown and shades of green. Brown for the bokashi brans and the good soil it creates. Green for the great food I get when growing in the nutrient soil I get from the compost.

![Color scheme](readme-images/colors.png)

#### Colour use
- Brown #582f0e - Headlines on white background, logo, hamburger icon and footer 
- Green #072B07 - Headlines on pale green background
- Pale green #f6f9f4 - Background color
- White #ffffff - Background color, icons in footer
- White whith opacity #fffffff2 - Background color
- Dark grey #3a3a3a - Bread text and navigation text

### Imagery
I used my own pictures from my garden and family. I also took new pictures of the bokashi workflow to use as illustrations in the guide.

### Wireframes

I chose to use figma for wireframe and prototyping. This is also where I wrote most of the textual content to make sure it all works together with the layout.
As you can see in the image below some design elements has changed, but most is staying true in the deployed version.
<details>
<summary>View the Prototype document (image of)</summary>

![Prototype](readme-images/figma-prototype.png)
</details>

## Features

### Header, Navigation and Footer - Elements avaiable in all pages
The responsive navigation bar in top of a page includes links to the home, guide and contact pages. 
The Bokash! logo is linked to the home (start page). The navigation bar has the same content and functionality on all pages.
I didn't want to use fontawesome for the "hamburger" menu (small devices), instead I chose to use '&#9776' for &#9776;

The footer in the bottom a page contains links to social media sites. All links opens in new tabs.

### Home (start page)
The start page starts off with a hero section with a button-link to the step-by-step guide (guide page, I used an anchor to the guide section of the page) followed by a fairly brief introduction to the benefits of using composting method. Below there is a testimonial section with thoughts from people using the composting method. I decided on the pale green background color here to visually separate the testimonials from the introduction.

![Home/startpage](readme-images/index.webp)

### Guide 
First section gives a short introduction of the compost technique and the initial cost to start (in Sweden).
Second section is the 5-step guide with pictures and textual instructions. The pale green background is used here as well as visual separation from the first section.

![Guide](readme-images/guide.webp)

### Contact
Contact form for anyone who wants to get in touch.
The form consists of first name, family name, email and message fields as well as send message and reset buttons.

![Contact](readme-images/contact.webp)

### 404
File not found page with image and links.

![Contact](readme-images/404.webp)

## Test

### Early and continuous testing 
Throughout the development process of the website, I conducted continuous testing to ensure a robust and responsive design. 

Having worked with HTML and CSS since the mid-1990s, I have a quite good understanding of how to code a basic website. This knowledge meant that I did not encounter any general issues with the core coding aspects during the development process. 

Personally, I find the design aspect of web development challenging since I am a perfectionist. My indecision and general dislike for designing web pages often leads to a cycle of minor adjustments (pixel pushing).

**Specific Issues and Solutions**

**Home/Start Page:**
A notable error occurred when I mistakenly used a capital 'P' in an image file name (`Pe.webp` changed to `pe.webp`). This seemingly minor discrepancy caused the image not to display on GitHub Pages. Resolving this involved numerous commits and pushes to ensure that GitHub correctly interpreted the changes. Eventually, renaming the file to `petra.webp` fixed the issue.

**Guide Page:**
Using a flex layout did not suit the row/column structure I intended for the step-by-step guide. Switching to a grid layout proved more effective, offering the flexibility and control needed to achieve the desired presentation and functionality.


### Testing against the user stories
#### Homepage Visitor
- **User Story:** As a new visitor, I want a clear and welcoming introduction, so that I can quickly understand what the website is about.
- **Analysis:** The homepage features a clear and engaging headline, "Bokashi Simplified," and provides an informative introduction to the Bokashi composting method. The use of images and customer testimonials adds to the page's welcoming nature and establishes credibility, meeting the user story's objective.

#### Guide User
- **User Story:** As a user who needs help with the process covered by the guide, I want a clear and easy-to-understand step-by-step guide.
- **Analysis:** The guide page presents a well-structured and detailed walkthrough of the Bokashi composting process. Steps are clearly numbered and supported by descriptive text and images, facilitating user understanding and execution of the method, in line with the user story.

#### Contact Page User
- **User Story:** As a user who needs additional help or has specific questions, I want to be able to fill out and send a simple contact form.
- **Analysis:** The contact page offers a straightforward form for visitors to leave their name, email, and message. Instructions are clear, and the options to clear or send the message are readily accessible, satisfying the user story's criteria.

#### Conclusions
The website effectively meets the criteria laid out in the user stories. The information is presented clearly, navigation is straightforward, and visitors are encouraged to engage further, whether by learning through the guide or reaching out via the contact page. The site's design and content strategy is aligned with the goals of educating visitors and encouraging the adoption of Bokashi composting.

### Functionality test (manual testing)

I created the cases below to verify the functionality of each page in both desktop and mobile layout.

#### Home/Start page - desktop layout
|Feature|Expected result|Action|Status|
| --- | --- | --- | --- | 
|Logo|Reloads page|Click logo|Pass|
|Navigation|Reloads page|Click home in navigation|Pass|
|Navigation|Loads guide page|Click guide in navigation|Pass|
|Navigation|Loads contact page|Click contact in navigation|Pass|
|Hero CTA|Loads guid page-step guide section|Click CTA button|Pass
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|

#### Guide page - desktop layout
|Feature|Expected result|Action|Status|
| --- | --- | --- | --- | 
|Logo|Loads start page|Click logo|Pass|
|Navigation|Loads start page|Click home in navigation|Pass|
|Navigation|Reloads page|Click guide in navigation|Pass|
|Navigation|Loads contact page|Click contact in navigation|Pass|
|Link to source|Opens link in new tab|Click link in last section of page|Pass|
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|

#### Contact page - desktop layout
|Feature|Expected result|Action|Status|
| --- | --- | --- | --- | 
|Logo|Loads start page|Click logo|Pass|
|Navigation|Loads start page|Click home in navigation|Pass|
|Navigation|Loads guide page|Click guide in navigation|Pass|
|Navigation|Reloads page|Click contact in navigation|Pass|
|Form|Sends data to CI formdump|Fill out all fields, click send message|Pass|
|Form-empty field|Message indicates empty field, message not sent|Leave form field blank, click send message|pass|
|Form-not email address|Message indicates not an email address, message not sent|Input text in email form field, click send message|pass|
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|

#### Home/Start page - mobile layout
|Feature|Expected result|Action|Status|
| --- | --- | --- | --- | 
|Logo|Reloads page|Click logo|Pass|
|Mobile navigation|Expands menu|Click burger icon|Pass|
|Mobile navigation|Collapses menu|Click burger icon|Pass|
|Mobile navigation|Reloads page|Click home in navigation|Pass|
|Mobile navigation|Loads guide page|Click guide in navigation|Pass|
|Mobile navigation|Loads contact page|Click contact in navigation|Pass|
|Hero CTA|Loads guid page-step guide section|Click CTA button|Pass
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|

#### Guide page - mobile layout
|Feature|Expected result|Action|Status|
| --- | --- | --- | --- | 
|Logo|Loads start page|Click logo|Pass|
|Mobile navigation|Expands menu|Click burger icon|Pass|
|Mobile navigation|Collapses menu|Click burger icon|Pass|
|Mobile navigation|Loads start page|Click home in navigation|Pass|
|Mobile navigation|Reloads page|Click guide in navigation|Pass|
|Mobile navigation|Loads contact page|Click contact in navigation|Pass|
|Link to source|Opens link in new tab|Click link in last section of page|Pass|
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|

#### Contact page - mobile layout
|Logo|Loads start page|Click logo|Pass|
| --- | --- | --- | --- | 
|Mobile navigation|Expands menu|Click burger icon|Pass|
|Mobile navigation|Collapses menu|Click burger icon|Pass|
|Mobile navigation|Loads start page|Click home in navigation|Pass|
|Mobile navigation|Loads guide page|Click guide in navigation|Pass|
|Mobile navigation|Reloads page|Click contact in navigation|Pass|
|Form|Sends data to CI formdump|Fill out all fields, click send message|Pass|
|Form-empty field|Message indicates empty field, message not sent|Leave form field blank, click send message|pass|
|Form-not email address|Message indicates not an email address, message not sent|Input text in email form field, click send message|pass|
|Footer|Opens Facebook in new tab|Click Facebook icon|Pass|
|Footer|Opens X in new tab|Click X icon|Pass|
|Footer|Opens Youtube in new tab|Click Youtube icon|Pass|
|Footer|Opens Instagram in new tab|Click Instagram icon|Pass|


The test cases were carried out on following devices/browsers: 

MacBook Pro 15-inch, 2017
- Safari Version 17.4.1 
- Firefox 124.0.2 (64-bit)
- Chrome Version 123.0.6312.124 (Official Build) (x86_64)

Ipad pro (12,9 inch IOS 16.7.7)
- Safari
- Firefox
- Chrome 

Iphone SE
- Safari
- Chrome 

Iphone 8 plus (IOS 16.7.7)
- Safari

The tests where carried out on the finalized site, no errors found.

### Code validation
#### HTML
All four pages Passed without errors

<details>
<summary>View html validation of home/start page (image of)</summary>

![Home/start](readme-images/html-validation-index.png)
</details>

<details>
<summary>View html validation of home/start page (image of)</summary>

![Guide](readme-images/html-validation-guide.png)
</details>

<details>
<summary>View html validation of home/start page (image of)</summary>

![Contact](readme-images/html-validation-contact.png)
</details>

<details>
<summary>View HTML validation of home/start page (image of)</summary>

![404](readme-images/html-validation-404.png)
</details>

#### CSS
Passed without errors

<details>
<summary>View CSS validation (image of)</summary>

![CSS](readme-images/css-validation.png)
</details>

### Performance test - Lighthouse

#### Desktop

<details>
<summary>Result start/home page (image of)</summary>

![Index page - desktop](readme-images/lighthouse-index-desktop.png)
</details>

<details>
<summary>Result guide page (image of)</summary>

![Guide page - desktop](readme-images/lighthouse-guide-desktop.png)
</details>

<details>
<summary>Result contact page (image of)</summary>

![Contact page - desktop](readme-images/lighthouse-contact-desktop.png)
</details>

#### Mobile

<details>
<summary>Result start/home page (image of)</summary>

![Index page - desktop](readme-images/lighthouse-index-mobile.png)
</details>

<details>
<summary>Result guide page (image of) </summary>

![Guide page - desktop](readme-images/lighthouse-guide-mobile.png)
</details>

<details>
<summary>Result contact page (image of)</summary>

![Contact page - desktop](readme-images/lighthouse-contact-mobile.png)
</details>

## Technologies

**Programs used:**
- Vscode (html, css)
- Photoshop (edit images and generating webp files)
- Figma (wireframe/prototyping)

**Browsers:**
- Firefox
- Chrome
- Safari

**Technologies:**
- HTML 5
- CSS 3

**Browser tools:**
- Google Dev Tools (troubleshoot and test features)
- Lighthouse, google plugin - (performance tests, desktop and mobile)

**Web tools:**
- [Github](https://behemot-biz.github.io/bokashi/) (repository)
- [Favoicon](https://favicon.io/favicon-generator/#google_vignette) (generate favicon)
- [Fontpair](https://www.fontpair.co/) (find matching fonts)
- [Google fonts](https://fonts.google.com/) (font api for loading fonts)
- [Am i responsive](https://ui.dev/amiresponsive) (generate image on different devices)
- [Font Awesome](https://fontawesome.com) (social network icons)
- [Markup validation Service](https://validator.w3.org) (html code validation)
- [CSS validation service](https://jigsaw.w3.org/css-validator/) (css code validation)

## Ideas for future implementation
- FAQ on the subject
- Scroll to top for small devices
- Use of responsive images for improved layout and optimized performance (srcset)

## Credits

### Sources

Forskning.se, [Komposten kan bli en klimatbov](https://www.forskning.se/2022/04/28/kompost-eller-bokashi-vad-ar-bast/) A Swedish government funded research site. (Linked to in guide.html)

### Code 
Header and navigation copied from the CI project "Love Running", modified to fit my purposes<br>
Footer copied from the CI project "Love Running", modified to fit my purposes<br>
Css for header and footer as well as for the hero section was copied from the CI project "Love Running", modified to fit my purposes.

### Tutorials used for improving the site

**Kevin Powell youtube**<br>
[Learn CSS Grid the easy way](https://www.youtube.com/watch?v=rg7Fvvl3taU)<br>
[Build a responsive card - HTML and CSS tutorial](https://www.youtube.com/watch?v=51DbAwcmqD8)<br>

**Refreshing my html knowledge**<br>
[W3Schools](https://www.w3schools.com/)

**Readme**<br>
[README.md - How, What and When?](https://www.youtube.com/watch?v=l1DE7L-4eKQ) 

**Special thanks**<br>
Special thanks to my husband Jimi for patience and support with the copywriting and proofreading of all texts both site and readme.<br>
Fellow students in the Swedish channel<br>
Mentor Rohit Sharma

