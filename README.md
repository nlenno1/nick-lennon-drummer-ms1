# Nick Lennon - Drummer

![Preview](assets/readme-assets/website-mockup-min.png)

[Link to the Live Project](https://nlenno1.github.io/milestone-project-1/)

# Table of Contents

1. [Introduction](#introduction)
2. [UX](#ux)
3. [Development Planes](#development-planes)
    - [Strategy](#strategy)
    - [Scope](#scope)
    - [Structure](#structure)
    - [Skeleton](#skeleton)
4. [Design](#design)
5. [Features](#features)
6. [Technologies Used](#technologies-used)
7. [Testing](#testing)
8. [Deployment](#deployment)
9. [Bugs and Issues](#bugs-and-issues)
10. [Credits](#credits)

***

#  Introduction

This website has been designer for the **Drummer Nick Lennon** (from here on will be referred to as the “client”) who is a musician who offers services, including **live music performance, recording sessions and tutoring**, to all clients who have an interest in creating, listening to or learning how to play live music. 

This website is based on my own previous work, with some fictitious information added as example content,  before taking up coding as it is an area I am very familiar with and completely understand the needs of the client and the user.

This is the first of four Milestone Projects that make up the Full Stack Web Development Program at The Code Institute. The main requirements of this project are to create a responsive and static website with a minimum of three pages using primarily **HTML5** and **CSS3**.

[Back to top](#nick-lennon---drummer)

# UX
### Project Goals
- To produce a well-designed and engaging website to advertise all services in the most efficient way possible
- To make it easy for users to navigate and access all the information they need.
- To allow users to learn more about the client and their experience.
- To enable users to contact the clientTo showcase the clients abilities	 
- To maintain a clean and professional image at all times
- To enable users to contact the client

## User Demographic
The target demographics for this web site are:
- Potential Students,
- Fellow Musicians or Potential Collaborators,
- Fans of Nick Lennon,
- Agents,Recruiters or Potential Employers,

## User Stories

- As a **Potential Student** I want to find information on the client’s lessons, the client’s experience, see previous student testimonials and view examples of the lesson content to help me establish if the client is a good teacher, to encourage me to get in touch if I have any questions and to sign up for lessons
- As a **Musician/Potential Collaborator**, I want to see the client’s previous work/performances, experience and training to allow me to decide if I want to work with them in the future and then to find easy ways to contact them.
- As a **Fan** who saw the client perform, I want to find more information about the client including what their latest music or video is, pictures of client and pervious performances, links to clients current projects, when their next show is, links to buy tickets and to connect with their social networks.
- As an **Agent,Recruiter or Potential Employer**, I want to see information about the client’s training and experience as well as be able to view performances to establish the client’s playing ability and be able to download a copy of the information for future reference, before having an easy way to get in touch.

[Back to top](#nick-lennon---drummer)

# Development Planes
## Strategy
The website will focus on the following user attributes:

**Demographics**
- Ages 18 - 50 years old
- All Genders and Ethnicities
- Employed or Self-Employed

**Psychographics**
- Personalities
    - Outgoing
    - Confident
    - Modest in their abilities
- Lifestyles and attitudes
    - Active interest or passion in Music
    - Looking for new challenges
    - Interested in learning
    - Open to taking advice and constructive criticism

The website needs to enable the **USER** to:
   
    Find information on:
    - Future Performances
    - Client's experience and previous work
    - Services that the client offers
    - How to contact the client
    - Signing up to the clients mailing list

The website needs to enable the **CLIENT** to:
   
    - Develop an online presence
    - Increase social media following
    - Showcase their porfolio
    - Attract new students
    - Encourage users to contact the client about future work
    - Promote future performances

I performed a Importance-Viability analysis on the clients needs to ensure that they were both important enough to need to be taken into consideration with this project but also to ensure that they are viable to do with all factors considered. The results look like this:

![Importance Viability Graph](assets/readme-assets/importance-viability-graph-min.png "Importance Viability Graph")

As you can see all goals set out are viable and important enough to be included.

[Back to top](#nick-lennon---drummer)

<hr>

## Scope
A scope was defined to identify what needed to be included in the project to complete the goals defined in the strategy section.

**Content Requirements**

    - Images of the client and previous performances
    - Future live performance information with links to ticket sales
    - Video performance examples
    - Client biography with basic CV download optiion
    - Studio credits with links to preview and buy the recordings
    - Drum lesson promotion video
    - Description of drum lesson services
    - Drum lesson example video with accompanying PDF download
    - Call to action to get in contact in regards to lessons and project enquires
    - Mailing list sign up form
    - Provides contact information

**Functionality Requirements**

    - Easy navigation to the required information
    - Quick loading of the website
    - Links to:
        - external websites for ticket sales and to purchase music
        - social media accounts
        - media sites (youtube for other videos and soundcloud/spotify to listen to music))
    - Mailing list sign up form
    - Links to social media accounts
    

[Back to top](#nick-lennon---drummer)

<hr>

## Structure

This website is organised using a **Tree** structure hireracy to reduce complexiy and make user navigation easier while allowing for a small amount of user exploring to discover information they didn't initially come to the website for.

Here is a diagram of the page structures.

![Link to the page structure image](assets/readme-assets/website-structure-min.png)

## Reasoning for the page structuring
**index.html** *(linked to from Logo)*. Decided on element order of:
1.	Hero image with name – to confirm identity of website and create a nice landing page,
2.	What I do – to allow quick and easy navigation to desired information while informing new visitors about the client's services.
3.	Gallery – To provide images of the client and previous performances to encourage them to see the client live.
4.	Future Performances with Video Performance Example – *(linked to from What I Do)* Advertises future performances, with direct links to ticket sales, and shows an example of a live show to encourage new visitors to buy tickets. These elements have been places at the bottom as fans coming looking for new performances to see will also see the social links in the Footer as the screen size from the top of Future Performances includes the footer. Using a link from YouTube will also direct the user to videos of other performances and shows increasing social media engaguement.
	
**about.html**. Decided on element order of:
1.	Image, Bio and Career Highlights (with CV download link) - this is what users that selected the about me page will be looking for primarily with the download link for the Agent,Recruiter or Potential Employer demographic.
2.	Studio credits - *(linked to from What I Do)* acts as evidence for the bio and when users are interested in recording services, they will also want to know about the background of the client. All album covers have links to the album to listen and purchase.

**lessons.html** *(linked to from What I Do and NavBar)*. Decided on element order of:
1.	Lessons Promotional Video – *(auto playing but muted when page loads)* gives general information in a succinct and informative way.
2.	Description of Services – general bullet point overview. Important to get information over as fast as possible if the user doesn’t watch the video or to reinforce the main points again if they do.
3.	Testimonials – potential students are not experienced in what they are looking into so can be persuaded to use the client’s services by current or previous students/parents of students leaving good reviews.
4.	Example Lesson – A video lesson example to show a user what the service would be like (including handout pdf download for the full experience)

In the footer **(linked to from the "Contact" in the Header element)** of every page there is:

- Links to social media accounts
- Contact information
- Mailing list sign up form
- Site map (desktop only)

[Back to top](#nick-lennon---drummer)

<hr>

## Skeleton

Wireframes were created in Balsamiq and Figma. Balsamiq was used to design the basic structure and Figma for the design elements. This system was used to focus on the two processes seperatly, enabling each area to be tailored to the users requirements. 

Throught out the design phase some elements of the design changed to allow for a better user experience. 

I was unable to represent some UI features on the wireframes due to Figma limitations.

Full Original Balsamiq Wireframe:
![Home Page Wireframe](assets/readme-assets/ms1-wireframe-complete-balsamiq-min.png "Balsamiq Wireframe")
<hr>

Index Page (Figma):
![Index Wireframe](assets/readme-assets/index.html-min.png "Index Wireframe")

<hr>

About Me Page (Figma):
![About Me Wireframe](assets/readme-assets/about-me.html-min.png "About Me Wireframe")

<hr>

Lessons Page (Figma):
![Lessons Wireframe](assets/readme-assets/lessons.html-min.png "Lessons Wireframe")

[Back to top](#nick-lennon---drummer)

# Design

## Colour Scheme
The main colours used throughout the website are a mixture of Blue primarily with Black, Silver, White and Peach highlights.

The chosen colour scheme is to give the website a modern and friendly feel that will appeal to the wide demographic.

## Typography
This project uses the fonts Overpass for body text, PT Sans for H1 headings and Roboto Condensed for sub-headings. All of these fonts use Sans Serif as the fallback font in case of import failure. 

## Imagery
The images used are all appropriate to the website and are vibrant and engaguing. Videos have been used to reduce the amount of text required in some sections.
All imagery has alternative text to accomodate the use of screen readers or if the image doesn't load.

[Back to top](#nick-lennon---drummer)
# Features

### Header 
- Company logo - establishes the website identity and doubles as the home button for only the phone breakpoint
- Navbar links with icons 
- Fix Navbar to the top of the screen to allow quick navigation at all times 

### Footer
- Footer  doubles as contact information (until contact page is implimented on next release)
- Sign Up For Newsletter (not currently linked to a mailing server but it will be implemented on next release)
- Site Map (only on Desktop breakpoint) to allow easier easier acces to specific information and some exploration
### index.html
- Hero Image - A strong image to welcome the user to the website while confirlming where the user has arrived at
- What I Do - quick navigation to the secondary topics of information
- Gallary - Gives the user a brief visual insite into the clients experience
- Upcoming Performances - Future performance details with links to ticket sales websites with a hover feature at the desktop breakpoint to reveal an image of the performance venue behind the card
- Live Performance Video - showcases a previous performance to encourage the user to buy tickets
### about-me.html
- About Me - Profile picture with biography to give in depth information about the clients background in their field
- Career highlights - A timeline element to give the user an overview of the important points from the clients career if they don't want to read the biography
- Studio Credits - Cover art of previous recording work. Each images will link to spotify to allow the user to listen to the music. Images have a hover feature to show the name of the song for the desktop breakpoint. Audio samples are also avaliable underneath the album images using Soundcloud.
- Basic CV Download - A stripped down CV PDF download to allow recruiters to retain a copy of it for future reference
### lessons.html
- Lesson Video Advert - A short advert for the clients tutoring service. The video plays but muted to draw the user in but all the important information is displayed on the screen in text.
- Lessons Overview - A revision of the main points from the video with clear icons to enable faster understanding
- Testimonials - Short statements from current pupils to persuade users to sign up for a lesson
- Example lesson - A short video lesson to act as an example of the clients services with a brief introduction and a download link to supporting documentation

## Features Left to Implement
* Why take Up Drumming - A section to inform the user about the many positive aspects to learning how to play the drums
* Endorses Section - A section to inform the user about what products the client uses therefore encouraging the potential student or fellow musician to use the same product which could lead to opening avenues for company collaborations
* Contact page - A new page with several contact options
* Mailing server - For the mailing list sign up and subscription to newsletter
* Online store - To give the client the ability to sell merchandise and music directly to the user

[Back to top](#nick-lennon---drummer)

# Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- HTML5 - Programming Language
- CSS3 - Programming Language
- [Bootstrap v4.3.1](https://getbootstrap.com/) - Library Import
- [Font Awesome](https://fontawesome.com/) - Icons Import
- [Phosphor Icons](https://phosphoricons.com/) - Icons Import
- [Google Fonts](https://fonts.google.com/) - Typography Import
- [Git Pod](https://gitpod.io/) - IDE (Intergrated Development Enviroment)
- [Git](https://git-scm.com/) - Version Control Tool
- [Github](https://github.com/) - Cloud based hosting service to manager my Git Repositories
- [Google Chrome Development Tools](https://developer.chrome.com/docs/devtools/) - Development Tools
- [Tiny Png](https://tinypng.com/) - Image Condenser
- [Balsamiq](https://balsamiq.com/) - Wireframes
- [Figma](https://www.figma.com/) - Wireframes

[Back to top](#nick-lennon---drummer)

# Testing

For every section that I built in the project, I tested for responsiveness during construction and after completion. To do this I used [Google Chrome Developer Tools](https://developer.chrome.com/docs/devtools/ "link to Google Chrome Developer Tools") to check that at all times the layout was how I expected it to be by dragging the screen width through all possible variaions while paying special attention to the predefined breakpoints. I also used the device models to make sure the page would provide a good UI and UX. 

This is what I tested in each section:
- NavBar
    - Logo link points to index.html
    - NavLinks point to the correct pages or sections
    - Active page icon colour changes page to page
    - NavLink icon hover effects icon colour
- Footer
    - Site map links points to the correct pages or sections
    - Social links open a new tab in the browser and load the correct social media page
    - Mailing List Sign Up email entry bar and submit button validates for correctly formatted email addresses and the input in required before the data is sent.
- index.html
    - What I Do buttons hover effects background colour
    - Gallery corner images change relative to number of columns
    - Upcoming performance links points to online ticket sales website and open in a new tab
    - Upcoming performance cards hover (at desktop breakpoint) changes background to venue image
    - Live performane video links to correct YouTube video and allows all users controls
- about-me.html
    - CV download link points to correct document, opens in a new tab and text colour is effected by hover
    - Career highlights containers and icons are effected by hover
    - Studio credits album images have drop down animation effected by hover
    - Soundcloud Iframes point to correct soundcloud songs and allows full user interaction expected
- lessons.html
    - Lessons video advert plays automatically, muted and does not loop
    - Example lesson video links to correct YouTube video and allows full user interaction expected
    -  CV download link points to correct document, opens in a new tab and text colour is effected by hover
    
I used some validator and responsiveness testing tools to evaluate my website. If any errors or warnings came up on these tests I reviewed and fixed them.

The testing tools I used were:
    
- [HTML Validator](https://validator.w3.org/) - [HTML Validator Results]()
- [CSS Validator](https://jigsaw.w3.org/css-validator/) - [CSS Validator Results]()
- [A11y](https://color.a11y.com/) to test site colours - ![A11y Results](assets/readme-assets/a11y-test-results.png)
- [Google Mobile-Friendly Test](https://search.google.com/test/mobile-friendly) - ![Google Mobile Results](assets/readme-assets/google-mobile-test-results.png)
- https://www.webpagetest.org/result/210323_XiPE_823011699fee64e1ac0319d0b160f385/
- https://www.aliciaramirez.com/closing-tags-checker/


### Results and outcomesd

All final tests produced good to excellent results apart from........

[Back to top](#nick-lennon---drummer)

# Deployment

All code was written on Gitpod, an online IDE.

This project is deployed on GitHub Pages. 
All my code was written using [Gitpod](https://www.gitpod.io/) and then pushed to a repository which was stored on my [Gitpod account](https://github.com/nlenno1/).

This is the process I used to deploy my project:

1. In my Github Repository I selected the settings tab and scrolled down to the GitHub Pages section.
2. In the source section, for the branch dropdown menu, I selected "Master" and then clicked the save button.
3. Once this process had been completed the website URL was displayed above the GitHub Pages section.

This code can be run locally through a clone or downloaded as a zipfile to your local hard drive.
The clone will provide a URL which you can use in any online IDE.
To clone or download the repositary, you need to:
1. Open the [repositary](https://github.com/nlenno1/milestone-project-1/).
2. Click the code dropdown menu and select either "Clone" or "Download".

[Back to top](#nick-lennon---drummer)

# Bugs and Issues

- While creating the footer I had some issues with spacing and objexts being pushed where I didnt want them. After some research through the Bootstrap documentation, I realised this was because the .row class was adding extra padding so to remove this is used the .g-0 class to remove all the gutters.
- Page layout was extending under the scroll bar on the right hand side of the screen but after some research on [Stack Overflow](https://stackoverflow.com/), suggestions from the Slack Community, some tutor guidance and the [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) I found an instance where I had not put an Image in its own seperate div which was causing the horixontal overflow.
- Socials links were creating a 404 page not found error. After reviewing the code, I realised that I had forgotten to include the "https://" part of the URL.
- Biography text was not wrapping round the Profile Picture. This was because they were in seperate Bootstrap .col classes so to fix this I put them in the same column and then floated the image to the right.
- Album Covers were not displying as 2 rows of 3 at desktop. To fix this I reduced the padding around them and reduced their max-width, still allowing them to shrink as the screen width dimishes.
- Soundcloud Iframe were stealing focus when loaded. After some reasearch on the soundcloud website I learnt that the autoplay value was automatically set to true so I changed this value to false to fix the bug.
- At the smallest breakpoint (280px - Galaxy Fold) the What I Do buttons where pressed together so to remedy this I changed their width to 95% and then their max width to 85px (the original width value) to allow them to shrink if the space was to small.
- The text on the Bounce to Bottom class p element over the Album Covers appearing before animation could take effect. To correct this I changed the text color on the p element to rgba(0, 0, 0, 0) so it was invisible and the hvr-bounce-to-bottom class changed the text colour when it was activated and not before.

[Back to top](#nick-lennon---drummer)

# Credits

Code snippets
- NavBar template taken from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/components/navbar/) and customised

Resources
- [Code Institute Course Content](https://courses.codeinstitute.net/) - Code fundamental learning platform
- Code Institude Slack Community and Tutor network
- [W3 Schools](https://www.w3schools.com/) - Learning resource
- [CSS-Tricks](https://css-tricks.com/) - Learning and bug fixing resource
- [Stack Overflow](https://stackoverflow.com/) - Bug fixing research
- [Color Scheme Designer](http://colorschemedesigner.com/csd-3.5/) - Inspiration for colour scheme


## Content

All text content on this site is original to the project.

### Media
All the images that were used during the development of this site are either original images or taken from Pixabay

Drumming related images:
- [Live Performances Background](https://pixabay.com/photos/drums-live-dancing-entertainment-755530/)
- [Lessons Background](https://pixabay.com/photos/drummer-drum-set-drums-music-5229705/)
- [Spare Background](https://pixabay.com/photos/drums-drum-pool-snare-drum-2778190/)

Venue images:
- [Park](https://pixabay.com/photos/concert-park-venue-music-artist-4634009/)
- [Theatre](https://pixabay.com/photos/metz-france-opera-theatre-interior-86226/)
- [Jazz Club](https://pixabay.com/photos/performance-music-musician-concert-3202707/)
- [Rock Venue](https://pixabay.com/photos/guitar-rock-music-concert-sound-2006563/)

Testimonial images:
- [Female](https://pixabay.com/photos/baby-bodysuit-female-girl-holding-22018/)
- [Young Male](https://pixabay.com/photos/man-fashion-brick-wall-pose-model-6018417/)
- [Older Male](https://pixabay.com/photos/man-male-beard-hat-woolly-hat-1146530/)

[Back to top](#nick-lennon---drummer)

## Acknowledgements

Structurally redesigned Gallery layout inspiration from Love Running Mini-Project in CSS Module of Code Institutes Full Stack Developer Course.

Readme template used to produce this documentation is from [Code Institute README Template](https://github.com/Code-Institute-Solutions/readme-template)

Additional guidance taken from 
 - https://github.com/nemixu/Milestone1
 - https://github.com/rebeccatraceyt/KryanLive
 - https://github.com/JimLynx/CI-MS1-Explore-Ireland

[Back to top](#nick-lennon---drummer)
