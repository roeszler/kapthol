# Kaptain Holiday
### HTML and CSS Essentials Portfolio Project 1
Site link : https://roeszler.github.io/kapthol/index.html

## 1. Purpose of the Project

Kaptain Holiday is a site that represents a theoretical business that facilitates holidays for small to medium businesses. The site is targeted at three main users:

- __Business owner / managers__ looking for someone to take over the daily operations of their business for a short time (_The 'Clients'_).

- __Business professionals__ with appropriate training, responsibility and availability to care-take operations of a small to medium business for short period of time (_The 'Providers'_).

- __Business Students__ looking to gain small business management experience in an assistant manager role for a short period of time, across a variety of industries and global locations (_The 'Assistants'_).

Based out of Stockholm, Sweden, __Kaptain Holiday__ will be useful for those looking for work flexibility, experiences, travel and/or comfortably manage the day to day business operations while they take a break.

![aim-responsive](docs/images/aim-responsive-kapthol.png)

### Main Products / Services

| 3 x Primary Services | | 3 x Working Formats |
| - |:-:| -:|
| 1. Holiday Cover | | Assistant to Manager (testing) .A|
| 2. Management Experience | | Proxy Manager (holidays) .B|
| 3. Service Trial | | Management Exchange (business swaps) .C|

## Note : User Centred Design 

Considering the importance of user experience (UX) and user centred design (UCD) in all web / app developments, and to better develop my understanding, I have spent a portion of my time to include a mock-up of the research and information that may be gleaned from such a process. 

I gave attention to this process in the knowledge that this will be an invaluable tool as I progress in my studies and career. 

Below are links to markdown documents I have used as a framework to develop, design and document the processes typically seen in a live project. 

The mockup documents will be referred to as required within the text. You can be accessed them here:

1. [Strategy Plane](docs/ucd/1-strategy.md) (working example)
2. [Scope Plane](docs/ucd/2-scope.md) (framework only)
3. [Structure Plane](docs/ucd/3-structure.md) (framework only)
4. [Skeleton Plane](docs/ucd/4-skeleton.md) (framework only)
5. [Surface Plane](docs/ucd/5-surface.md) (framework only)

## 2. User Stories

A working document of sample user stories can be found [here](docs/ucd/stories.md). The following stories have been arranged as they are appear in this project.

__Entire Site__
- As a site user I can see that all pages are responsive to different devices being used so I can have a responsive experience across devices used to view it.
- As a viewer of the code I can see that each .html page uses a remotely accessed CSS format so I can confirm this section follows appropriate ease of styling and semantic code structuring practices.
- As a site user I can see that every non-text element has alt text so that the website can meet accessibility guidelines.

- Header
  - As a viewer of code: 
    - I can see the index.html page has a ```<header>``` element with corresponding ```id="header"```.
    - I can see an image within the ```<header>``` there is a ```<nav>``` element with corresponding ```id="nav-bar"```.
      - So that code viewers can confirm this section follows appropriate semantic code structuring practices.
  
  - As a site user I can see the layout of the ```<header>``` element is always at the top of the viewport so that navigation is easy and intuitive.

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
  - As an initial site user I can see the top of the subsequent page bleeding up at the bottom of the page so that I am enticed to investigate the site further.

__Gallery (Our Clients)__
- As a user of the site I can view the experiences of past clients of the business so I can better understand the experience of using these services.
- As a potential customer of the business I can further investigate the experience of other customers so I can decide if it will work with my situation and needs.
- As a business stakeholder I can present more detailed information to potential clients so I can convert them into long term paying customers.

__Contact Us__
- Contact Us Form
  - As a viewer of the code I can see that the index.html page has a ```<form>``` element with a corresponding ```id="form"``` so I can confirm this section follows appropriate semantic code structuring practices.
  - As a viewer of the code I can see that within the form, there is an ```<input>``` field with ```id="email"``` so I can enter an email address.
  - As a viewer of the code I can see that the ```#email``` input field should have a label or placeholder text so that the user knows what the field is for.
  - As a viewer of the code I can see that ```#email``` input field uses HTML5 validation so that we can confirm that the entered text is an email address.
  - As a viewer of the code I can see that within the form, there is a submit ```<input>``` with corresponding ```id="submit"``` to allow ease of CSS styling in the future.
  - As a site user I can click the ```#submit``` button so that the email is submitted to a static thank-you for submission page (success.html) that confirms the email address was entered (and that it posted successfully).

- Map 
  - As a site user I can see an embedded google map of our head office at the immediate end of the contact us section to convey a sense of permanency in the business operations.

- Footer
  - As a site user I can see a footer section containing links to our pages' popular social media sites so I can interact with friends and follow updates from the business page. 

## 3. Features 

### 3.1 Existing Features

- __Head & Meta Terms__
  - Nomenclature
    - Discussed further in the [strategy.md](docs/ucd/1-strategy.md) documentation, Kaptain Holiday name was selected for its memorable nature, sense of playfulness and meaningful connection to the core value proposition of the business.
    - Key Terms : kaptain, holiday, holidays, captain holiday, management, proxy, stand-in, locum, business holiday, Sweden, Stockholm, facilitator, small business management.

  - Content
    - Each .html page uses a remotely accessed CSS format so that code editors can more easily change the format of content from the one location

  - Layout 
    - All pages have at least one media query to make the viewport responsive to different popular devices. This is so users can have a responsive experience across devices used to view the entire site.

<br>

__Navigation Bar__

![header-nav-bar](docs/images/nav-bar-kaptain.png)

  - ```<nav>``` bar featured identically on all pages in the top right hand corner with a minimal design to create a clean simple style and allow easy intuitive navigation. 
  - As a responsive navigation bar, it includes links to the home page, our services, customer stories, contact us and login / registration pages to allow easy intuitive navigation.
  - The site is designed to be browsed easily as a single page site with additional deeper pages used to delve into more detail as required by the B2B user.
  - The navigation bar allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the browsers 'back' button.


__The Landing Page & Image__

![hero-page](docs/images/home-hero-kaptain.png)

  - The landing section includes a format and images with text overlay to allow the user to understand what type of user this site would be applicable to.
  - The landing section announces the core business proposition with a subtle growth and rotation animation to grab the users attention toward the site mascot image ([Sailor Penguin](assets/images/kapthol-hero-image.webp)).

__The Header__

![header-nav-bar](docs/images/header-opacity-kaptain.png)

  - The header shows the name of the business, using the corporate colors selected from the corporate color scheme discussed further in the [strategy.md](docs/ucd/1-strategy.md) documents attached.
  - It has been styled to stick to the top of the viewing window as the user scrolls down each page with a 85% opacity to enhance the modern professional feel of the site.


__About Us Section__

![about-us](docs/images/about-kaptain.png)
![about-us-2](docs/images/about-kaptain-2.png)

  - Allows the user to see the typical process of the Kaptain Holiday product delivery in a visual format to better understand the services of the business.
  - Allows the user to see the value of kaptain holiday to allow them to take a break. 
  - Allows the user their first chance to select / investigate which product option that may suit their particular circumstances.
  - Allows users to initiate a contact us call to action so they may start using kaptain holiday services. 

__Gallery (our clients) section__

![clients section](docs/images/clients-kaptain.png)

  - This section allows the user to further explore the product range and experiences of model customers. It is aimed to encourage users to consider Kaptain holiday as part of their next planned break away from their business. 
  

__The Contact Us Section__

![contact-section](docs/images/contact-kapthol.png)

  - This section will allow the user to contact Kaptain Holiday with queries
  - The user will be able to specify if they would like to take part in hiring a manager, manager exchange exchange programs, or applying to become a manager with Kaptain Holiday. 
  - The user will be asked to submit their full name, email address (required) and a small enquiry message.

__The Footer__ 

  - The footer section includes links to the relevant social media sites for Kaptain Holiday. The links will open to a new tab to allow easy navigation for the user. 
  - The footer section includes information for the user on the legal format and registered office address of the Kaptain Holiday business. 
  - The footer is valuable to the user as it encourages them to keep connected via social media and share with people / businesses they may know that may use the kaptain holiday service(s).
  - In the contact section (found on the index.html page only), there is a map immediately preceding the form to promote a sense of business location and permanency should users wish to investigate further.

![map-and-footer](docs/images/map-footer-aptain.png)

### Subsequent HTML Pages

__Gallery / User Case Studies Pages__

![gallery.html](docs/images/gallery-kaptain.png)
![experiences](docs/images/user-kaptain.png)

  - The experience and client pages are designed to be the base format of three main product options (business holidays, working flexibility and testing services with assistant managers). The pages are designed to allow the user to investigate further which option is valuable to their situation. 
  - This page provides the user with supporting images and information to see what types of business management experiences are available to work in while the business owners are away. 
  - These pages are valuable to the user as they will be able to relate to the requirements and types of businesses and professionals that Kaptain Holiday typically helps.

__The Register / Login Page__

![Register / Login Pic](docs/images/login-page.png)

  - This page will allow the user to either login or sign up to Kaptain Holiday to start planning their next holiday within the community. 
  - The user will be able to specify if they would like to take part in hiring a manager, manager exchange program, or applying to become a manager with Kaptain Holiday. 
  - The user will be asked to submit their full name and email address. 

__Successful Submission Page__

![Success Pic](docs/images/success-kaptain.png)

  - This page is displayed to the user following a successful enquiry submission and indicates a call to action to refer friends via social media and/or return to the site homepage.
  - The success image is a slight deviation away from the site's penguin logo, however the light, fun feel of the action of the site is maintained.

### 3.2 Future Features
___
  - Underline animation occurs in the nav header section on active status whilst still on the single index.html page. An example of this is the 'contact us' (```/index.html#contact```) selection. It should make the contact lettering in the menu become underlined in the nav bar when the 'contact us section' is being viewed. 
    - As a majority of the navigation elements are designed to link to id's on the same page (ie function as a "single page site"), a future feature is to use some form of JavaScript / JQuery to make the relative navbar section appear active on page id selection. This will likely involve the use of an element like : ```window.location.href```.

  - Include an extra .html page of the exchange process to provide more details of this service as it becomes available
  - Hamburger icon for menu navigation on mobile devices
  - Apply ```class=""``` coding in preference to ```id=""``` whenever possible to maintain consistency
  - Use ```.em``` size ranges consistently throughout code in preference to ```.px``` or ```%``` to maintain consistency
  - Functional database, interaction and account page for logged-in users
  - Popup Q&A animations 
  - Automated matching of current registered [clients](ucd/1-strategy.md) and [providers](ucd/1-strategy.md)
  - Possible membership on a subscription model basis
  - API links into CRM and project management software (like [jira](https://www.atlassian.com/software/jira), [trello](https://trello.com/), [hubspot](https://www.hubspot.com/) and/or [slack](https://slack.com/))
  - Further entry animation and smoothing
  - Synergy with ongoing content from small-business education providers
  - Intergrate gallery and new initiatives as they become available via a social media management strategy to keep users engaged with the business

<br>

## 4. Branding

The branding associated with Kaptain Holiday is aimed at associating a :
  - Light, happy, sunny, cloud free, blue skies, impact, fun, non-corporate nature of target business owner / managers.
  - Services and solutions aim to be subtly associated with a "day at the beach" or "a sunny holiday with a pool". 
  - The demographic is aimed at the mid twenties (providers / assistants) to late forties (clients) age groups. 

### Typography and color scheme

__Typography__

Typography was evaluated in line with the themes and brand aiming for a the non-corporate nature of business owner / managers.
  - Bold main 
  - Smooth easy to read content 
  - Excellent contrast 
  - Adequately portray the light, summer holiday feel for the site
  
Typography selection process :
  - Review of similar and complementary fonts from variety of internet based sources
  - Selection of those that seem appropriate to the business profile (summarised in the [strategy.md](docs/ucd/1-strategy.md) process)
    - Shortlisted fonts :
      - Anton / Roboto
      - Alfa Slab / Open Sans
      - Alegreya Sans / Roboto
      - Lobster / Open Sans
      - Quicksand / Ubentu
      - Nunito / Roboto
      - Oswald / Nunito 
  
  Evaluation based on contrast, easy of reading, and shapes that compliment the summer time feel, the combination of [Alegreya Sans](https://fonts.google.com/specimen/Alegreya+Sans) / [Nunito](https://fonts.google.com/specimen/Nunito) was chosen as the font combination most suitable. 
    

__Color Scheme__ 

  | Primary Color Palette | Hexadecimal Value | RGBA Value  |
  | - |:-:| -:|
  | Sky Blue | #3AADFB | rgba(58,173,251, 1) |
  | Sailor Blue | #232361 | rgba(35,35,97, 1) |
  | Light Tan | #F2DDB2 | rgba(242,221,178,1) |
  | Red | #FF0000 | rgba(253,0,0,1) |
  | White | #FFFFFF | rgba(255,255,255,1) |
  | Black | #000000 | rgba(0,0,0,1) |
  | Gray | #3a3a3a | rgba(58,58,58,1) |

  In a effort to maintain build consistency, I have converted all RGB-A values to their equivalent HEX-A values using the below conversion table :


| Opacity % | RGB-A | HEX-A Code | 
| :-: | -: | :-: |
| 100 | 1 | FF
| 99  | 0.99 | FC
| 98 | 0.98 | FA
| 97 | 0.97 | F7
| 96 | 0.96 | F5..
<!-- 95 | 0.95 | F2
94 | 0.94 | F0
93 | 0.93 | ED
92 | 0.92 | EB
91 | 0.91 | E8
90 | 0.9  | E6
89 | 0.89 | E3
88 | 0.88 | E0
87 | 0.87 | DE
86 | 0.86 | DB
85 | 0.85 | D9
84 | 0.84 | D6
83 | 0.83 | D4
82 | 0.82 | D1
81 | 0.81 | CF
80 | 0.8  | CC
79 | 0.79 | C9
78 | 0.78 | C7
77 | 0.77 | C4
76 | 0.76 | C2
75 | 0.75 | BF
74 | 0.74 | BD
73 | 0.73 | BA
72 | 0.72 | B8
71 | 0.71 | B5
70 | 0.7 | B3
69 | 0.69 | B0
68 | 0.68 | AD
67 | 0.67 | AB
66 | 0.66 | A8
65 | 0.65 | A6
64 | 0.64 | A3
63 | 0.63 | A1
62 | 0.62 | 9E
61 | 0.61 | 9C
60 | 0.6 | 99
59 | 0.59 | 96
58 | 0.58 | 94
57 | 0.57 | 91
56 | 0.56 | 8F
55 | 0.55 | 8C
54 | 0.54 | 8A
53 | 0.53 | 87
52 | 0.52 | 85
51 | 0.51 | 82
50 | 0.5  | 80
49 | 0.49 | 7D
48 | 0.48 | 7A
47 | 0.47 | 78
46 | 0.46 | 75
45 | 0.45 | 73
44 | 0.44 | 70
43 | 0.43 | 6E
42 | 0.42 | 6B
41 | 0.41 | 69
40 | 0.4  | 66
39 | 0.39 | 63
38 | 0.38 | 61
37 | 0.37 | 5E
36 | 0.36 | 5C
35 | 0.35 | 59
34 | 0.34 | 57
33 | 0.33 | 54
32 | 0.32 | 52
31 | 0.31 | 4F
30 | 0.3  | 4D
29 | 0.29 | 4A
28 | 0.28 | 47
27 | 0.27 | 45
26 | 0.26 | 42
25 | 0.25 | 40
24 | 0.24 | 3D
23 | 0.23 | 3B
22 | 0.22 | 38
21 | 0.21 | 36
20 | 0.2 | 33
19 | 0.19 | 30
18 | 0.18 | 2E
17 | 0.17 | 2B
16 | 0.16 | 29
15 | 0.15 | 26
14 | 0.14 | 24
13 | 0.13 | 21
12 | 0.12 | 1F
11 | 0.11 | 1C
10 | 0.1 | 1A
9  | 0.09 | 17
8  | 0.08 | 14
7  | 0.07 | 12
6  | 0.06 | 0F
5  | 0.05 | 0D
4  | 0.04 | 0A
3  | 0.03 | 08
2  | 0.02 | 05
1  | 0.01 | 03
0  | 0 | 00 -->
... contunued in order to zero % opacity

The above color combinations (and opacity variations) were chosen as they relate to :
  - The summer feel sought for the site 
  - The hero image 'penguin' discovered at Pixbay user [OpenClipart-Vectors](https://pixabay.com/vectors/tux-anchor-animal-bird-boat-ferry-161379/).

## 5. Supported Screens and Browsers
Testing was performed on a mix of when the display element changed and the resolution of popular screen sizes currently seen in the marketplace.

[GBK soft research](https://gbksoft.com/blog/common-screen-sizes-for-responsive-web-design/) indicates the following proportions of screen useage globally (as at January 2020 to January 2021)* :

- Desktops
  - __1366×768 - 22.6%__
  - __1920×1080 - 20.87%__
  - 1536×864 - 8.52%
  - 1440×900 - 6.97%
  - 1280×720 - 4.81%
  - 1600×900 - 4.1%
  - 1280×800 - 2.95%
  - 1280×1024 - 2.65%
  - 1024×768 - 2.59%
  - 768×1024 - 2.47%

- Mobiles
  - __360×640 – 12.98%__
  - 414×896 – 7.82%
  - 375×667 – 6.65%
  - 360×780 – 6.02%
  - 360×760 – 5.27% 
  - 375×812 – 5.15%

- Tablets
  - __768×1024 - 6.11%__
  - __1280×800 – 7.38%__
  - 800×1280 - 5.9%
  - 601×962 – 5.15%
  - 962×601 – 3.52%
  - 810×1080 – 2.83%

The media sizes intended for the responsive transitions seen on the site, have been based on future popular sizes ([gbksoft](https://gbksoft.com/blog/common-screen-sizes-for-responsive-web-design/)).

Additionally, Gbksoft indicates the typical use of media used to browse web pages is predominantly mobile, seen in the table below : 

| Desktop vs. mobile vs tablet worldwide | | Predominant Screen Resolution (US) |
| - | -:| :-: |
| Mobile | 55.73% | 414×896 |
| Desktop | 41.46% | 1920×1080 |
| Tablet | 2.81% | 768×1024 |

Acknowledging the scope of the project and beginner nature of my skills as a coder in html / css, I originally considered starting the design with a mobile interface and scaling it up with media queries to a desktop version.

With my focus to learn the process of html / css design and the innate simplicity of mobile sites, I found it easier to focus on a desktop version, then simplifying it into a mobile interface using media queries.
### Wireframes 
Contained in the Wireframes section of the [skeleton.md](docs/ucd/4-skeleton.md) documentation is a visualisation of the layout and colouring intended for the site. 

The wireframes are intended to convey :
- An indication of the various elements and positions of these in relation to each other 
- The actions / content that gets priority via it's location on the screen, actions, animations and embedded interactivity
- What is encountered at different stages of the site 
- Illustrate the more technical requirements in the site to achieve an easy and intuitive navigation to the primary goals of the stakeholders in the site
- Convey a sense of the user experience planned for the site as users navigate through

The feel and function of the wireframes was the initial framework inteded to show stakeholders and potential clients early concepts before any coding started. 
### Browsers 
The kaptain holiday site has been created using [GitPod](https://www.gitpod.io/) on a google chrome browser in conjunction with the chrome development environment. 

The site has been tested on each of the following popular browsers to check for maintained function and interactivity :
- [Google Chrome](https://www.google.com/chrome/)
- [Microsoft Edge](https://www.microsoft.com/en-us/edge) 
- [Apple Safari](https://www.apple.com/safari/)
- [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
## 6. Technology

The skillsets used in the creation and review of this project are based around a working knowledge of HTML5 and CSS plus their associated semantic structures. 

The tools and the benefit of using each in the site development are : 
- [GitHub](https://github.com/)
  - Allows a variety of benefits to create, document, store, showcase and share a project in development.
- [GitPod](https://www.gitpod.io/)
  - Provides a relatively secure workspace to code and develop software projects in a remotely accessible cloud based platform.   
- [Google Fonts](https://fonts.google.com/)
  - Is a free to use, reliable, remotely accessible database of web ready fonts endorsed by google that are familiar to most users.
- [FavIcon Generator](https://favicon.io/)
  - A simple, free to use image conversion tool to generate icon files ready for use in a variety of applications.
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
  - The current agreed standard, HTML5 is a free to use, well established markup language recommended by the World [Wide Web Consortium](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium) (W3C) for programming. It is easily read by humans and consistently understood by computers and associated devices.
- [CSS](https://en.wikipedia.org/wiki/CSS)
  - A style sheet language that allows the separation of presentation variables (like layout, colors and fonts) from the content variables that has been defined in the markup languages (like HTML &/or JavaScript). The separation allows either local or site wide changes to occur in the one place.
- [Google Maps](https://console.cloud.google.com/getting-started) 
  - Via the google cloud platform a secure access to a customisable map that can be embedded into projects backed with ongoing device, software and security developments used by google.   
- [Various Image Optimisers](https://fixthephoto.com/best-image-optimizer.html)
  - Able to reduce the file size and format of images ready for rapid access, improving device performance, accessibility and user experience
- [Font Awesome](https://fontawesome.com/)
  - Is a partly free to use, remotely accessible database of fonts and icons helpful for projecting implied meaning through vector graphics.
- [Balsamiq Wireframes](https://balsamiq.com/)
  - A low-fidelity wire-framing tool to visualise and clarify features, interactions in the [skeleton plane](docs/ucd/4-skeleton.md) phase of UCD.
- [Gimp GNU Image Manipulator](https://www.gimp.org/)
  - Free to use desktop publisher that allows you to create &/or manipulate images for use in projects.
## 7. Testing
### Test Cases

- As a site user I can see that all pages are responsive to different devices being used so I can have an unhindered experience across devices used to view it
    - Expand / contract width and height dimensions at each section to see which elements interact and record the dimensions at which these occur
    - Employ google chrome developer tools using varieties of device emulations to indicate responsiveness and content alignment
    - Correct display of all website images on the devices with different screen sizes.
    - Appropriate alignment and positioning of text blocks and headers.
    - The size of images, text and other website blocks should be proportionally changed in accordance with the screen sizes.
    - The color of all site elements should be preserved, despite the extension and characteristics of the screen.
    - When a user enters text, it should be displayed correctly with the size of pins, font, and tabs.
    - Preservation of the correctness of the color reproduction when interacting with the interface - when the tab is on buttons and links, the hover, etc.
    - The page should be scrolled without any problems and failures.
    - The click-ability of the appropriate zones on the pages of the site

- As a viewer of the code I can see that each .html page uses a remotely accessed CSS format so I can confirm this section follows appropriate ease of styling and semantic code structuring practices.
  - Appropriate ```<link rel="stylesheet" href="...style.css">``` command is contained in the ```<head>``` section of each .html file.
  - Each ```<link rel="stylesheet" href="...style.css">``` command is functioning on each .html page with alteration of .css elements.
  
- As a site user I can see that every non-text element has alt text or aria-label so that the website can meet accessibility guidelines.
  - In the upper right, open the customise and control Google Chrome menu by clicking the three horizontal bars. Select Settings.
  - Click the Show advanced settings... link, and then, under "Privacy", click Content settings....
  - Under the "Images" heading, select Do not show any images.
  - Click OK, and then close the Settings tab. If necessary, reopen Chrome to continue browsing.
  - Test and record all elements that do not have appropriate ```alt=""``` text or ```aria-label=""``` content.

- So that code viewers can confirm this section follows appropriate semantic code structuring practices, as a viewer of code: 
  - I can see the index.html page has a ```<header>``` element with corresponding ```id="header"```
  - I can see an image within the ```<header>``` element with a corresponding ```id="header-img"```
  - I can see that within the ```<header>``` element there is a ```<nav>``` element with corresponding ```id="nav-bar"```.

- As a site user I can see the layout of the ```<header>``` element is always at the top of the viewport so that navigation is easy and intuitive.
  - Scroll down each .html page with the header and all its elements stick to the top section of the browser window and float without interaction of any underlying elements.

- As a site user I can easily identify with the style and location of the home button in the nav bar or the left header text so as to intuitively navigate the sections and pages of the site.
  - Home icon / text is located in the top left hand corner of the browser window
  - Icon functions to return user to top of home page ```index.html```.
  - Appropriate spacing to the left of the element to allow ease of access and page balance
  - Element is not effected by the interaction with the format or style of any other element  

- As a site user I can click any given ```<nav>``` link button in the nav bar so that I am taken to the corresponding section of the ```index.html``` and/or ```login.html``` pages.
  - Each subsequent navigation element is appropriately positioned in the top right corner of the viewing window
  - Each subsequent navigation element is appropriately evenly spaced so as not to interact with each other
  - Each subsequent navigation element links to it's appropriate navigation section and/or .html page.
  - With interaction, each subsequent navigation element functions in the same responsive style 

- As a site user I can see that the hero text on the ```#home``` section is clearly presented, appropriately colored and contrasted so that the site is introduced intuitively in an easy to read manner.
  - Lighthouse testing within chrome development tools produces a accessibility contrast score of at least 90 or above for all elements
  - Hero font selected is strong, clear and easy to read

- As a site user I can identify with the hero image to relate to the core services of the business so that business value proposition can be reinforced during my time navigating the site.
  - Hero image is in the same color and style that directly correlates to the rest of the site as detailed in the [strategy.md](docs/ucd/1-strategy.md) documentation.
  - Hero image conveys the core business value proposition detailed in [strategy.md](docs/ucd/1-strategy.md).
  - Hero image is light, friendly and associated with any of the travel, ocean, holiday themes associated to the business brand discussed in [strategy.md](docs/ucd/1-strategy.md). 

- As an initial site user I can see the top of the subsequent page bleeding up at the bottom of the page so that I am enticed to investigate the site further.
  - Height of subsequent about us section that immediately follows the hero section, occupies 25% of the base of the screen.

- A user of the site I can view the experiences of past clients of the business so I can better understand the experience of using these services.
  - Site links contained in the about us section to [success.html](success.html) and [experience.html](experience.html) link to appropriate relative pages

- As a potential customer of the business I can further investigate the experience of other customers so I can decide if it will work with my situation and needs.
  - Links to [contact us](https://roeszler.github.io/kapthol/index.html#contact) section take the user to the appropriate position on the contact us

- As a business stakeholder I can present more detailed information to potential clients so I can convert them into long term paying customers.
  - Submission of contact us messages or login pages directs user to [success.html](https://roeszler.github.io/kapthol/success.html) indicating function to be included in further project updates.

- As a viewer of the code I can see that the index.html page has a ```<form>``` element with a corresponding ```id="form"``` so I can confirm this section follows appropriate semantic code structuring practices.
  - ```index.html``` has appropriate semantic structure seen in ```<form>```, ```<label>```, ```<input>```
  - Appropriate id="form" label at ```<form>``` sections
  - ```<form>``` connected to database appropriately (future feature)
  
- As a viewer of the code I can see that within the form, there is an ```<input>``` field with ```id="email"``` so I can enter an email address.
  - Check is the email field allows valid e-mail ids. For example; an ```id: tester@example.com``` should be accepted.
  - Check is the warning or error message is displaying on entering the invalid e-mail ids. For example; inputs “tester@example”, “tester.example@com” should not be accepted.

- As a viewer of the code I can see that the ```#email``` input field should have a label or placeholder text so that the user knows what the field is for.
  - ```<label>``` Filed appropriately applied to email input field

- As a viewer of the code I can see that ```#email``` input field uses HTML5 validation so that we can confirm that the entered text is an email address.
  - ```<filedset>```, ```<div>```, ```<label>``` and ```<input>``` are in the correct semantic order
  - ```<filedset>```, ```<div>```, ```<label>``` and ```<input>``` correctly refer to each element they relate toward.

- As a viewer of the code I can see that within the form, there is a submit ```<input>``` with corresponding ```id="submit"``` to allow ease of CSS styling in the future.
  - Submit button activates fields appropriately filled in to ```success.html``` conformation page.
  - Check is the spelling and position of the button are correct.
  - Check is the button is clickable.
  - Check on submitting a valid form, the value gets saved and the administrator receives the same (future feature)
  - Check is the administrator receives the contact form at the email address which has been configured (future feature)

- As a site user I can click the ```#submit``` button so that the email is submitted to a static thank-you for submission page (```success.html```) that confirms the email address was entered (and that it posted successfully).
  - Submit button activates fields appropriately filled in to ```success.html``` conformation page.

- As a site user I can see an embedded google map of our head office at the immediate end of the contact us section to convey a sense of permanency in the business operations.
  - Map navigation works within site 
  - Map section takes up a height of 25% at the base of the contact us section 
  - Map controls visible and working
  - View larger map links to appropriate google maps location
  - View larger map link opens in a new page

- As a site user I can see a footer section containing links to our pages' popular social media sites so I can interact with friends and follow updates from the business page. 
  - Facebook icon displayed in first position on left of social media navigation row
  - Twitter icon displayed in second position from left of social media navigation row 
  - Instagram icon displayed in third from left position from left of social media navigation row 
  - LinkedIn icon displayed on the right position of social media navigation row 
  - All social icons display using font awesome bold logo
  - All social icons display with opacity 30% white (```#FFFFFF4D```) on normal status
  - All social icons display with opacity 100% light blue (```#3AADFB```) on hover
  - All social icon links open in a new tab
  - All social icon links target the correct relative business social media page

### Execution of Test Cases 
Test cases used in this project intuitively reflect four types of test execution recognised in modern software design processes. It answers questions like :

- Has the __Business Analyst__ interpreted the requirements correctly?
- Has the __Development Team__ translated the business requirements to functional requirements and eventually to code correctly?
- Have the __Data Architect__ and __Database Administrators__ (DBAs) designed the appropriate back-end systems?

A Summary of Test Case Types

| Smoke Test | Sanity Test | Exploratory Test | Functional Test |
| --- | --- | --- | --- |
| Smoke Testing is not exhaustive testing but it is a group of tests that are executed to verify if the basic functionalities | Sanity Testing as a test execution which is done to touch each implementation and its impact but not thoroughly or in-depth | Exploring the system and encouraging real-time and practical thinking of a tester to challenge| Determines if a piece of software is acting in accordance with pre-determined functional requirements|
| Example: Does the [contact link](https://roeszler.github.io/kapthol/index.html#contact) open up without any issues after code deployment? | Example: Is the "Submit" button on the login.html page functional? | Example: Visited the demo page from Google search results. For no reason it showed me the login page in Swedish language instead of English. When I refreshed the same page it showed me the login page in English.| Example : Error message on unsuccessful input of email format to contact us ```<form> <input>``` element |

## Reported bugs from above Testing

Most problems solved during the build surrounded the formatting and alignment of ```<div>``` sections : 
1. In relation to each other and 
2. Centralising content within them. 

Elements like ``` width:; padding:; margin:;``` have been used to align content, however some interaction between these (like when looking to adjust the screen ratios) conflicted at times. 

Solving this required slight rethinking &/or alteratons to type and combination of code to produce the desired outcome.  

1. About sections not lining up as desired with a single section. Included second section to correct issues.
2. Centralisation of [kapthol-hero-image-400.webp](assets/images/kapthol-hero-image-400.webp) to the central Kaptain Holiday text in the "what we do" section while changing screen sizes.
3. Image hover on the mobile section was influenced by the ```<div>``` containing the ```class="center-align-experience"``` class. It seemed to override the height of the entire content. Fixed with toggling the ```position:;``` element between the two in mobile width screen formats
4. Padding on the right side of ```class="input-forms"``` did not seem to be evenly spaced. Included ```padding-right: 45px;``` in the ```.input-forms``` css to adapt.
5. Fix gray styling to ```<hr>``` on ```experience.html``` and ```holiday.html```
6. Remove unwanted border around hero image in about us section
7. Remove inline-block command conflict in the ```.footer p``` style class
8. Alignment of ```<footer>``` section interrupted by ```height``` not equalling ```auto```
9. Add appropriate ```index.html#id's``` to sections on each of the html pages
10. Correct about us alignment by including a separate section and change ```id=""``` references to ```class=""```.
11. Select element error in validation testing ```login.html``` needing a ```value=""``` to have content when using ```required``` feature. __I would like to remove this in the future__.
12. Semantic order of headings ```h1```, ```h2``` present an error in validation with a non-sequential order. Suggested to change the format of ```<section>``` to ```<div>```. It works, however I wish to keep the semantic structure of the site, so I have re-styled each of the ```h1```, ```h2```, ```h3``` headings to display the exact formats I wish to see at the times I wish to see them.

### Unsolved Bugs

Due to the single person size of the team and scope of the project, testing has been in parallel with coding each element, and once again as a final testing phase. It is not intended to be exhaustive, however __no bugs are reported at time of project submission__.
## 8. Validator Testing 

- HTML
  - index.html = No errors were returned when passing through the official W3C validator on each of the following pages :
    - [index.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Findex.html)
    - [success.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Fsuccess.html)
    - [login.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Flogin.html)
    - [holiday.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Fholiday.html)
    - [gallery.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Fgallery.html)
    - [experience.html](https://validator.w3.org/nu/?doc=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Fexperience.html)

- CSS
  - No errors were found when passing through the official [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Froeszler.github.io%2Fkapthol%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Accessibility
  - I confirmed that the colors, contrast and fonts chosen are easy to read and accessible by running it through [lighthouse](https://developers.google.com/web/tools/lighthouse/) in dev tools.
  
![Accessibility Pic](docs/images/accessibillity-score-kapthol.webp)


## 9. Deployment

### Display Environment (GitHub / GitLab / BitBucket)
The site has been deployed to GitHub pages. The steps to deploy are as follows: 
  - Create / open an existing repository for the project with the name of your choice on your GitHub, GitLab or Bitbucket account page.
  - Navigate within the GitHub repository you chose, and then navigate to the "settings" tab, which displays the general title.
  - On the left hand navigation menu, I selected the "pages" option midway down the menu.
  - At the top of the pages tab, the source section drop-down menu changed to select the branch: "main" with the folder selected as "/(root)"
  - Committed to the save and waited a few moments for the settings to coordinate with the server. 
  - On refresh of the browser, the dedicated ribbon changed to the selected web address, indicating a successful deployment.

> The live link can be found at - https://roeszler.github.io/kapthol/index.html
### Development Environment (GitPod)

The site has been deployed to GitPod pages. The steps to deploy are as follows:
- In the GitHub, GitLab or Bitbucket account page where you created a repository for the project, navigate to the tab titled '<> Code'
- From here, navigate to the button on the top right of the repository navigation pane titled 'Gitpod'.
- If you press this it will create a new GitPod development environment each time.

__Alternatively, if you have already created the GitPod environment for your project__ : 

- In the browser’s address bar, prefix the entire URL with [gitpod.io/#](https://gitpod.io/#) or [gitpod.io/workspaces](https://gitpod.io/workspaces) and press Enter. This will take you to a list of workspaces that have been active within the past 14 days.
- Search for the workspace you wish to work on and access the link to it that lies within the pathway https://gitpod.io/.

PLEASE NOTE: the difference between GitPod and the GitHub hyperlinks : 

> the GitPod workspace for this site is https://gitpod.io/start/#roeszler-kapthol-y3gyoqrxrk4 that is restricted by account access to one of the providers like GitHub, GitLab, or BitBucket.
    
> The freely accessible GitHub repository for this site is https://github.com/roeszler/kapthol

- Sign in to the workspace each time with [gitpod.io/#](https://gitpod.io/#) using one of the listed providers (GitHub / GitLab / BitBucket) and let the workspace start up.
- On navigating to the workspace for the first time, it may take a little while longer than normal to intially install all it needs. Be patient.
- It is recommend that you install the GitPod browser extension to make this a one-click operation into the future.

## Credits 
### Content 

- Primary and additional CSS and html coding was studied and reworked from modules provided through the Code Institute's [Diploma in Full Stack Software Development](https://codeinstitute.net/se/full-stack-software-development-diploma/), [W3 Schools](https://www.w3schools.com/), [Stack overflow](https://stackoverflow.com/), [mozilla.org](https://developer.mozilla.org/en-US/docs/Web/CSS/background) and [GeeksforGeeks](https://www.geeksforgeeks.org/). These included research and implementation of: 
  - position: sticky;
  - z-index: ;
  - opacity: ;
  - text-shadow: ;
  - background-image: linear-gradient();
  - embed a map in iframes using [google cloud console](https://developers.google.com/maps/documentation/embed/cloud-setup)

- The screen size for mockups and responsiveness testing was sampled from [GBK Soft](https://gbksoft.com/blog/common-screen-sizes-for-responsive-web-design/) and based current resolutions typically found globally
- Country codes for dropdown list in contact us section - [html-code-generator.com](https://www.html-code-generator.com/html/drop-down/country-names)

- The text for the Home page was sourced from [Alegreya Sans](https://fonts.google.com/specimen/Alegreya+Sans) by Juan Pablo del Peral, Huerta Tipográfica and [Nunito](https://fonts.google.com/specimen/Nunito) by Vernon Adams, Cyreal, Jacques Le Bailly imported via google fonts. 
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- Test Case scenarios researched from [softwaretestingo.com](https://www.softwaretestingo.com/), [Software Testing Help](https://www.softwaretestinghelp.com/test-execution-software-testing-qa-training-on-a-live-project-day-5/) and [QA Test Lab](https://qatestlab.com/). 

### Media
- The photos, videos and vector graphics used on the home and sign up page are from [pixbay.com](https://pixabay.com/users/openclipart-vectors-30363/), upsplash and [freepik.com](https://www.freepik.com/home)
  - all penguin images - sourced from Pixbay user [OpenClipart-Vectors](https://pixabay.com/vectors/tux-anchor-animal-bird-boat-ferry-161379/).
  - palmtree.webp - sourced from [Palm tree icon vector created by brgfx - www.freepik.com](https://www.freepik.com/vectors/palm-tree-icon)
  - contact-us.webp - sourced from [unsplash.com](https://unsplash.com/photos/4SNUcHPiC8c)
  - success.webp - sourced from [pixabay.com](https://pixabay.com/photos/children-win-success-video-game-593313/)
  - sally-provider.webp - sourced from [unsplash.com](https://unsplash.com/s/photos/owner)
  - all bus images were sourced from pexels user [@nubikini](https://www.pexels.com/@nubikini)
  - Video by [Jess Loiterton](https://www.pexels.com/video/sea-waves-kissing-the-beach-shore-4782135/) from pexels

- The images used for the gallery page were taken from a pexels.com collection curated [here](https://www.pexels.com/collections/kapthol-wqxkprh/) and [here](https://www.pexels.com/search/cafe/).

---

 *__Please Note__ : Kaptain Holiday is a fictitious site used entirely for educational purposes at the time of coding. Notwithstanding its theoretical nature, it has been written as a proof of concept and invitation to treat for possible interested parties into the future. All copyright for ideas, concepts and materials lies with Stuart Roeszler © 2022.*