# Kaptain Holiday
### HTML and CSS Essentials Portfolio Project 1
Site link : https://roeszler.github.io/kapthol/index.html

<!-- 
 ### Table of Contents
1. Purpose of the project
2. User stories
3. Features
4. Future features
  - pop-outs
  - header bar 
  - login / registration page
  - animations
5. Typography and color scheme
6. Wireframes
7. Technology
8. <a href="#testing">Testing</a>
   8.2 Test cases (user story based with screenshots)
   8.3 Solved bugs
   8.4 Unsolved bugs
   8.1 Validator Testing & Accessibility
    8.1.1 WC html
    8.1.2 WC CSS
    8.1.3 Lighthouse
   8.4 Supported screens and browsers
9. Deployment
   9.1 via gitpod
   9.2 via github pages
10. Credits
  10.1 Code Content
  10.2 Media

---
-->

## 1. Purpose of the Project
---
Kaptain Holiday is a site that represents a theroetical business that facilitates holidays for small to medium businesses. The site is targeted at three main users looking to employ/provide services that allow them to take a break from the daily operations of their small business:

- __Business owner / managers__ looking for someone to take over the daily operations of their business for a short time (_The 'Clients'_).

- __Business professionals__ with appropriate training, responsibility and availability to care-take operations within a small to medium business for a contract period of time (_The 'Providers'_).

- __Business Students__ looking to gain small business management experience in an assistant manager role for a short period of time, across a variety of industries and global locations (_The 'Assistants'_).

Based out of Stockholm, Sweden, __Kaptain Holiday__ will be useful for those looking for work flexibility, experiences, travel and/or comfortably coordinate their business operations while they take a break.

![aim-responsive](assets/docs/aim-responsive-kapthol.png)

### Main Products / Services

| 3 x Primary Services | | 3 x Working Formats |
| - |:-:| -:|
| 1. Holiday Cover | | Assistant to Manager (testing) .A|
| 2. Management Experience | | Proxy Manager (holidays) .B|
| 3. Service Trial | | Management Exchange (business swaps) .C|

## Note : User Centred Design 
---
Considering the importance of user experience (UX) and user centred design (UCD) in all web / app developments, and to better devlop my understanding, I have spent a portion of my time to include a mock-up of the reserach and information that may be gleaned from such a process. 

I gave attention to this process in the knowledge that this will be an invaluable tool as I progress in my studies and working life. 

Below is links to the markdown documents I have created to assist my understanding of the development design processes as it would relate to a live project. 

The mockup documents will be referred to as required within the text and/or you can be accessed them all here:

1. [Strategy Plane](ucd/1-strategy.md) (working example)
2. [Sope Plane](ucd/2-scope.md) (framework only)
3. [Structure Plane](ucd/3-structure.md) (framework only)
4. [Skeleton Plane](ucd/4-skeleton.md) (framework only)
5. [Surface Plane](ucd/5-surface.md) (framework only)

## 2. User Stories
---
A woking document of sample user stories can be found [here](ucd/stories.md). The following stories have been arranged in accordance to the sections they are seen in this project.

__Entire Site__
- As a site user I can see that all pages are responsive to different devices being used so I can have a responsive experience across devices used to view it.
- As a viewer of the code I can see that each .html page uses a remotely accessed CSS format so I can confirm this section follows appropriate ease of styling and semantic code structuring practices.
- As a site user I can see that every non-text element has alt text so that the website can meet accessibility guidelines.

- Header
  - As a viewer of code: 
    - I can see the index.html page has a < header > element with corresponding id="header"
    - I can see an image within the header element with a corresponding id="header-img"
    - I can see that within the < header > element there is a < nav > element with corresponding id="nav-bar"
  - So that code viewers can confirm this section follows appropriate semantic code structuring practices.
  - As a site user I can see the layout of the < header > element is always at the top of the viewport so that navigation is easy and intuitive.

- Home Button / Icon
  - As a site user I can easily identify with the style and location of the home button in the nav bar or the left header text so as to intuitively navigate the sections and pages of the site.

- Nav Bar
  - As a site user I can click any given .nav-link button in the nav bar so that I am taken to the corresponding section of the index.html and/or login.html pages.

__Home Page__

- Hero Text
  - As a site user I can see that the hero text on the #home section is clearly presented, appropriately colored and contrasted so that the site is introduced intuitively in an easy to read manner.

- Hero Image
  - As a site user I can identify with the hero image to relate to the core services of the business so that business value proposition can be reinforced during my time navigating the site.

- Layout
  - As an initial site user I can see the top of the subsequent page bleed ing up ath the bottom of the page so that I am enticed to investigate into the site further.

__Gallery (Our Clients)__
- Accessed through further investigation into the holiday service as a business owner, as a user of the site I can view the experiences of past clients of the business so i can better understand the experience of using these services.
- As a potential customer of the business I can further investigate the experience of other customers so I can decide if it will work with my situation and needs.
- As a business stakeholder I can present more detailed information to potential clients so I can convert them into long term paying customers.

__Contact Us__
- Form
  - As a viewer of the code I can see that the index.html page has a < form > element with a corresponding id="form" so I can confirm this section follows appropriate semantic code structuring practices.
  - As a viewer of the code I can see that within the form, there is an < input > field with id="email" so I can enter an email address.
  - As a viewer of the code I can see that the #email input field should have a label or placeholder text so that the user knows what the field is for.
  - As a viewer of the code I can see that #email input field uses HTML5 validation so that we can confirm that the entered text is an email address.
  - As a viewer of the code I can see that within the form, there is a submit < input > with corresponding id="submit" to allow ease of CSS styling in the future.
  - As a site user I can click the #submit button so that the email is submitted to a static thank-you for submission page (success.html) that confirms the email address was entered (and that it posted successfully).

- Map 
  - As a site user I can see an embedded google map of our head office at the immediate end of the contact us section to convey a sense of permanency in the business operations.

- Footer
  - As a site user I can see a footer section containing links to our pages popular social media sites so I can interact with friends and follow updates from the business page. 

## 3. Features 
---
<!-- This section explains what value each of the features provides for the user,
  - Focusing on who this website is for, 
  - what it is that they want to achieve and 
  - how your project is the best way to help them achieve these things. 
 -->

### 3.1 Existing Features

- __Head & Meta Terms__
  - Nomenclature
    - Discussed further in the [strategy.md](ucd/1-strategy.md) documentation, Kaptain Holiday name was selected for its memorable nature, sense of playfulness and meaningful connection to the core value proposition of the business.
    - Key Terms : kaptain, holiday, holidays, captain holiday, management, proxy, stand-in, locum, business holiday, Sweden, Stockholm, facilitator, small business management.

  - Content
    - Each .html page uses a remotely accessed CSS format so that code editors can more easily change the format of content from the one location

  - Layout 
    - All pages should have at least one media query to make the viewport responsive to different popular devices being used so that users can have a responsive experience across devices used to view the entire site.

<br>

__Navigation Bar__

![header-nav-bar](assets/docs/nav-bar-kaptain.png)


  - Is featured identically on all pages in the top right hand corner with a minimal design to create a clean simple style and allow easy intuitive navigation. 
  - The full responsive navigation bar includes links to the home page, our services, customer stories, login / registration and contact us pages to allow easy intuitive navigation.
  - The site is designed to be browsed easily as a single page site with additional 'deeper' pages used to delve into more detail as required by the B2B user.
  - The navigation bar allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.


__The Landing Page & Image__

![hero-page](assets/docs/home-hero-kaptain.png)

  - The landing section includes a format and images with text overlay to allow the user to understand what type of user this site would be applicable too.
  - The landing section announces the core business proposition with a subtle animation to grab the users attention.

__The Header__

![header-nav-bar](assets/docs/header-opacity-kaptain.png)

  - The header shows the name of the business, using the corporate colors selected from the corporate colour scheme discussed further in the [strategy.md](ucd/1-strategy.md) documents attached.
  - It has been styled to stick to the top of the viewing window as the user scrolls down each page with a 85% opacity to enhance the modern professional feel of the site.


__About Us Section__

![about-us](assets/docs/about-kaptain.png)
![about-us-2](assets/docs/about-kaptain-2.png)

  - Allow the user to see the typical process of the Kaptain Holiday product delivery in a visual format to better understand the services of the business.
  - Allow the user to see the value of kaptain holiday to allow them to take a break. 
  - Allow the user their first chance to select / investigate which product option that may suit their particular circumstances.
  - Allow users to initiate a contact us call to action so they may start using kaptain holiday services. 

__Gallery (our clients) section__

![clients section](assets/docs/clients-kaptain.png)

  - This section will allow the user to further explore the product range and experiences of model customers. It should encourage users to consider Kaptain holiday as part of their next break away from the business. 
  - This section will be kept up to date as times and new initiatives become available to keep the user engaged with the business. 

__The Contact Us Section__

![contact-section](assets/docs/contact-kapthol.png)

  - This section will allow the user to contact us with queries
  - The user will be able to specify if they would like to take part in hiring a manager, manager exchange exchange programs, or applying to becoming a manager with us. 
  - The user will be asked to submit their full name, email address (required) and a small enquiry message.

__The Footer__ 

  - The footer section includes links to the relevant social media sites for Kaptain Holiday. The links will open to a new tab to allow easy navigation for the user. 
  - The footer section includes information for the user on the legal format and registered office address of the Kaptain Holiday business. 
  - The footer is valuable to the user as it encourages them to keep connected via social media and share with people / businesses they may know that may use the kaptain holiday service(s).
  - On the conatct section of the index.html page only, there is a map immediately preceeding the form to promote a sense of business location and permanancy should users wish to investigate further.

![map-and-footer](assets/docs/map-footer-aptain.png)

### Subsequent HTML Pages
___
__Gallery / User Case Studies Pages__

![gallery.html](assets/docs/gallery-kaptain.png)
![experinces](assets/docs/user-kaptain.png)

  - The experience and client pages are designed to be the base format of three main product options (business holidays, working flexibility and testing services with assistant managers)> The pages are designed to allow the user to investigate further which option is valuable to their situation. 
  - This page provides the user with supporting images and information to see what types of professionals are available to manage their business while they are away. 
  - These pages are valuable to the user as they will be able to relate to the requirements and types of businesses and professionals that Kaptain Holiday typically helps.

__The Register / Login Page__

![Register / Login Pic](assets/docs/login-page.png)

  - This page will allow the user to either login or sign up to Kaptain Holiday to start planning their next holiday within the community. 
  - The user will be able to specify if they would like to take part in hiring a manager, manager exchange exchange programs, or applying to becoming a manager with us. 
  - The user will be asked to submit their full name, email address and LinkedIn details. 

__Successful Submission Page__

![Success Pic](assets/docs/success-kaptain.png)

  - This page indicates is displayed to the user following a successful enquiry submission and indicates a call to action to refer friends via social media and/or return to the site homepage.
  - it is a slight deviation away from the sites penguin logo, however the light, fun feel of the action is maintained.


<!-- _For some/all of your features, you may choose to reference the specific project files that implement them._

_In addition, you may also use this section to discuss plans for additional features to be implemented in the future:_ -->

### 3.2 Future Features
___
  - Underline in nav header on active status on single page. Possibly JS / JQuery function: ```window.location.href```.
  - Include a description of the exchange process in more visual detail
  - Hamburger Icon for menu navigation on mobile devices
  - Functional database, interaction and account page for logged-in users
  - Popup Q&A animations 
  - Automated connecting of current registered [clients](ucd/1-strategy.md) and [providers](ucd/1-strategy.md)
  - Possible membership on a subscription model basis
  - api links into CRM and project management software (like [jira](https://www.atlassian.com/software/jira), [trello](https://trello.com/), [hubspot](https://www.hubspot.com/) and/or [slack](https://slack.com/))
  - Intuitive tracking and cataloging of content
  - Further entry animation and smoothing
  - Synergy with ongoing content from small-business education providers 

<br>

## 4. Typography and color scheme
---
__Typography__

Typograohy was evaluated in line with the themes and brand aiming for a the non-corporate nature of business owner / managers.
  - Bold main 
  - Smooth easy to read content 
  - Excellent contrast 
  - Adequately portray the light, summer holiday feel for the site
  
Selection process :
  - Review of similar and complementary fonts from variety of internet based sources
  - Selection of those that seem appropriate to the business profile summarised in the [strategy.md](ucd/1-strategy.md) process.
    - Shortlist of fonts:
      - Anton / Roboto
      - Alfa Slab / Open Sans
      - Alegreya Sans / Roboto
      - Lobster / Open Sans
      - Quicksand / Ubentu
      - Nunito / Roboto
      - Oswald / Nunito 
  
  On evaluation of the look, feel, and summer time feel sought for the project, a combination of [Alegreya Sans](https://fonts.google.com/specimen/Alegreya+Sans) / [Nunito](https://fonts.google.com/specimen/Nunito) was chosen. 
    

__Color Scheme__ 

  | Primary Color Palette | Hexadecimal Value | RGBA Value  |
  | - |:-:| -:|
  | Sky Blue | #70BBE7 | rgba(112,187,231,1) |
  | Sailor Blue | #232361 | rgba(35,35,97, 1) |
  | Light Tan | #F2DDB2 | rgba(242,221,178,1) |
  | Red | #FF0000 | rgba(253,0,0,1) |
  | White | #FFFFFF | rgba(255,255,255,1) |
  | Black | #000000 | rgba(0,0,0,1) |
  | Grey | #3a3a3a | rgba(58,58,58,1) |

The above color combinations (and opacity variations) were chosen based partly on :
  - The summer feel sought for the site 
  - Access to the hero image 'penguin' discovered at Pixbay user [OpenClipart-Vectors](https://pixabay.com/vectors/tux-anchor-animal-bird-boat-ferry-161379/).

__Branding__

The themes and branding associated with Kaptain Holiday is aimed at associating a  
  - Light, happy, sunny, cloud free, blue skies, impact, fun - non-corporate nature of business owner / managers.
  - Services and solutions aim to be subtly associated with a "day at the beach" or "a sunny holiday with a pool". 
  - The demographic is aimed at the mid twenties (providers / assistants) to late forties (clients) age groups. 
    
## 5. Wireframes
--- 
A simple visualisation of the layout and colouring intended for the site, it conveys the to the user as they experience the site. The feel and function of the site is intended to be light, summery with an air of simple effective service delivery. 

The media sizes employed in the wireframes, that will eventually be intended for the responsive transitions seen on the site, has been based on future popular sizes seen in the UK. This information has been sourced from [https://gbksoft.com/](https://gbksoft.com/blog/common-screen-sizes-for-responsive-web-design/).

Gbksoft also indicates the typical use of media used to browse webpages is predominantly mobile, seen in the table below : 

| Desktop vs. mobile vs tablet worldwide ||
| - | -:|
| Mobile | 55.73% |
| Desktop | 41.46% |
| Tablet | 2.81% |

Acknowledging the scope of the project and beginner nature of my skills as a coder of html / css, I intend to start the design with reference to a mobile interface, and scale it up with media queries in due course.

__The Landing Sections__ 

Desktop 

![1920 x 1080 Desktop - Home](assets/docs/1920x1080-desktop-home.png)

Tablet

![1024 x 768 Tablet - Home](assets/docs/1024x768-index.html-tablet.png)

Mobile

<img src="assets/docs/414x896-index.html-mobile.png" alt="html-mobile" width="414"/>

__What We Do (About Us)__
___

Desktop
![1920 x 1080 Desktop - About](assets/docs/1920x1080-desktop-about.png)

__Our Clients__
![1920 x 1080 Desktop - Gallery](assets/docs/1920x1080-desktop-gallery.png)

__Contact Us__
![1920 x 1080 Desktop - Contact](assets/docs/1920x1080-desktop-contact.png)

__Successful Submission__
![1920 x 1080 Desktop - Success](assets/docs/1920x1080-success-desktop.png)

__Provider Stories__
![1920 x 1080 Desktop - Experience](assets/docs/1920x1080-exp.html-desktop.png)

__Client Stories__
![1920 x 1080 Desktop - Holiday](assets/docs/1920x1080-hol.html-desktop.png)

<!-- __Exchange Process__
![1920 x 1080 Desktop - Exchange](assets/docs/1920x1080-exch.html-desktop.png) -->

__Login / Register__
![1920 x 1080 Desktop - Login](assets/docs/1920x1080-login-desktop.png)

_Please see attached link to view the entire proposed early layout of the site in a .pdf format document at : [KH-wireframes.pdf](assets/docs/KH_wireframes.pdf). The exchange process deatiled in the KH-wireframes.pdf was reserved for future releases due to the scope of this as an initial project._

## 6. Technology
--- 
8. <a href="#testing">Testing</a>
   8.2 Test cases (user story based with screenshots)
   8.3 Solved bugs
   8.4 Unsolved bugs
   8.1 Validator Testing & Accessibility
    8.1.1 WC html
    8.1.2 WC CSS
    8.1.3 Lighthouse
   8.4 Supported screens and browsers
## 7. Testing
---
Overall I am very satisfied that the included features all work as intended using HTML / CSS coding only. The project provides an easy and straightforward way for the users to achieve their goals (Holiday cover / Management Assistance / Sales of Services).

- I have tested that this page works in different browsers: Chrome, Firefox, Safari, Edge.
- I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the devtools device toolbar that accompanies the google chrome browser.
- I confirmed that the navigation, header, about us, sign up and contact text are all readable and easy to understand.
- I have confirmed that the form works: requires entries in every relevant field, will only accept email in the email field, and the submit button works.
- I have set aech form ([contact](https://roeszler.github.io/kapthol/index.html#contact) and [login / register](https://roeszler.github.io/kapthol/login.html)) to method="get" to allow the interaction of each to return a positive response to the [success.html](https://roeszler.github.io/kapthol/success.html) page as indication of a successful submission. This is for testing purposes, and the final site would interact with a database / CRM messaging system a live scenario.
- I have confirmed the nav bar sticks to the top of the page with a transparency that elicits content to be seen, however still allows the header text to be seen clearly.
- Animation of the header penguin to slightly enlarge and roatate to portray a sense of activity, with the palm tree to enlarge at a slightly slower rate. All for visual effect.
- White opaque overlya on mouse hover on images (and social links) with hyperlinks. This has been included to create a subtle interactivity to the desktop user and promote links to further information / opportunity to connect with potential clients.
- Hover of form fields changing to slight blue border
- Centralised form sections on screen widths less than 1200 pixels
- Map section created that inherits and intergrates appropriately with google maps

__Size / Responsivitiy Considerations__

The site functions with the primary light blue, white and black/grey interactions on all sites. 

The mobile site has been designed to reduce the amount of information available and better direct the user to a message / contact us outcome. It has been designed to reflect that mobile users are literally mobile. They are in a form that predomidantly looks to satisfying an immediate need, such as researching directions in a new city or looking up a phone number or an address. 

In contrast, people using a destop (such as business users ready to commit) may be more likely to use the desktop format when they want to read several pages or conduct in-depth research.



_You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet._

_If this section grows too long, you may want to split it off into a separate file and link to it from here._

## 8. Bugs
### Solved Bugs
___
Most problems seem to revolve around formatting and alignment of ```<div>``` sections with each other and centralising content within them. Elements like ``` width:; padding:; margin:;``` have been used to align content, however some interaction between these (like when looking to adjust the screen ratio's) has caused a few problems

1. Content alignment and the use of elements as detailed above.
2. About secion not lining up as desired with single section. Included second section to correct issues.
3. Centralisation of [kapthol-hero-image-400.png](assets/images/kapthol-hero-image-400.png) to the cetral Kpatain Holiday text in the "what we do" section while changing screen sizes.
4. Image hover on the mobile section was influenced by the ```<div>``` containing the ```class="center-align-experience"``` class. It seemed to overide the height of the entire content. Fixed with toggling the ```positon:;``` element between the two in mobile width screen formats
5. Padding on right side of ```class="input-forms"``` does not seem to be evenly spaced. Included ```padding-right: 45px;``` in the ```.input-forms``` css to adapt.
6. Fix grey styling to ```<hr>``` on experience.html and holiday.html
7. Remove unwanted border around hero image in about us section
8. Remove inline-block command conflict in the footer p styling
9. Alignment of footer section interupted by height not equalling auto
10. Add appropriate ```index.html#id's``` to sections on each of the html pages
11. Correct about us alignment by including separate secion and chane ```id=""``` refrences to ```class=""```.

### Unsolved Bugs
___
- The 'contact us' (```/index.html#contact```) selection, should make contact underline in nav bar when selected, even though it is on the same index.html page.
  - Once I have progressed in the learning modules, I plan to use some form of JavaScript / JQuery to make relative nav bar section appear active on page id selection. This will likely involve the use of a element like : ```window.location.href```.

## 9. Validator Testing 
___
- HTML
  - index.html = No errors were returned when passing through the official W3C validator on each of the following pages :
    - [index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Findex.html)
    - [success.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Fsuccess.html)
    - login.html
    - holiday.html
    - gallery.html
    - experience.html
- CSS
  - No errors were found when passing through the official [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froeszler.github.io%2Flove-running%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
  - I confirmed that the colors and fonts chosen are easy to read and accessible by running it through [lighthouse](https://developers.google.com/web/tools/lighthouse/) in dev tools.
  
![Accessibility Pic](assets/images/readme/love_running_signup.png)


## Deployment
---
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

> The live link can be found here - https://roeszler.github.io/kapthol/index.html


## Credits 
---
In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The screen size for mockups and responsiveness testing was sampled from [GBK Soft](https://gbksoft.com/blog/common-screen-sizes-for-responsive-web-design/) and based current resolutions typically found in the UK marketplace
- Country codes for dropdown list in contact us section - [html-code-generator.com](https://www.html-code-generator.com/html/drop-down/country-names)

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos and vector graphics used on the home and sign up page are from [pixbay.com](https://pixabay.com/users/openclipart-vectors-30363/), upsplash and [freepik.com](https://www.freepik.com/home)
  - all penguin images - sorced from Pixbay user [OpenClipart-Vectors](https://pixabay.com/vectors/tux-anchor-animal-bird-boat-ferry-161379/).
  - palmtree.png - sourced from [Palm tree icon vector created by brgfx - www.freepik.com](https://www.freepik.com/vectors/palm-tree-icon)
  - contact-us.jpeg - sourced from [unsplash.com](https://unsplash.com/photos/4SNUcHPiC8c)
  - success.jpeg - sourced from [pixabay.com](https://pixabay.com/photos/children-win-success-video-game-593313/)
  - sally-provider.jpeg - sourced from [unsplash.com](https://unsplash.com/s/photos/owner)
  - all bus images were sourced from pexels user [@nubikini](https://www.pexels.com/@nubikini)
- The images used for the gallery page were taken from a pexels.com collection curated [here](https://www.pexels.com/collections/kapthol-wqxkprh/) and [here](https://www.pexels.com/search/cafe/).

---


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice
---
Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 

 *__Please Note__ : Kaptain Holiday is a fictitious site at the time of coding. Notwithstanding its theoretical nature, it has been written as a proof of concept and invitation to treat for possible interested investors into the future. All copyright for ideas, concepts and materials lies with Stuart Roeszler © 2022.*


