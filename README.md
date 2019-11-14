# John Miller - Resume site

This site is a 4 page site with the purpose of show-casing myself to potential clients.  I should come across as prefessional, reliable and skilled at the services I can offer to local businesses.  There are pages covering my employment history and some sample images from completed projects. The site is published through Gitpages;
https://johnmiller1963.github.io/resume/
but could be deployed to my business domain www.ritmanager.co.uk

Using html5 and semantics it would be findable through natural searches but historically my clients come from word-of-mouth via existing customers.  The site contains a single method of contact, a modal contact form that (when connected) would email me details of the enquiry, together with enquiror name and email and optionally the abilty to upload a related data file.
 
## UX

The site is primarily a landing page for local businesses that might be looking for software development services.  Either they have come to this site as a recommendation or a natural search, they would want to have a quick look around to check that the services I can offer are what they need to resolve one or more problems in their company.

The experience should be quick, they don't want to read my life history, only know that I have built bespoke software for organisations large and small also that I have known skills in the platform they perhaps want to use.

They would land on the home page (index.html) and see that I don't have 2 heads, flick around the pages, then click on the 'contact' option which is visible at all times in the navbar and pulled out as separate item (button) on the landing page.

At present the site doesn't display direct phone numbers as I work part-time so may not be able to answer, so an initial contact via email means nothing will be lost.

A typical User Story could be a manager\MD\owner of a local SME that has an internally developed software system, normally in Microsoft Excel or Access.  These systems are prone to problems if not developed correctly, so at some point they ask colleagues or contacts if they know someone who can help improve their internal systems.  Common problem areas are; Work-in-Progress tracking, Stock Management, Job Pricing (man-hours & materials), Quality Management and accessibilty of electronic files and data (Collaberation).  Having found or been directed to my site they will want to know that I am worth contacting and allowing me to listen to their issues.  I can then propose one or more solutions under the company name of 'Our IT Manager Ltd'

The site is a personal resume for myself, but links in several sutble ways to 'Our IT Manager', some clients perfer the perceived security of working with a business rather than an individual.  The site is the bridge between myself as an indivual and my business.

As the site should be more attractive than a simple black and white PDF resume, it should appeal to recruiters looking for contractors for specific roles.  I would like to take on flexible or fixed term contracts through recruitment agencies and similar to the story above these people want to know that I have enough experience to complete the task involved.

Wireframes were created using Balsamiq desktop before any coding, these are available in the Github repository for the site;
https://github.com/johnmiller1963/resume/blob/master/assets/wireframes/JM-MS1.bmpr

## Features

The site is designed mobile first using Boostrap4.  It has a white background and a limited colour pallette.  The colours where checked to have an acceptable contrast ratio as recommended by W3C using the resources at;
https://contrastchecker.com/
Fonts were selected by visual appeal from the Google site;
https://fonts.googleapis.com/css?family=Niramit
with a fall-back of Roboto and sans-serif.

The purpose of the site is to allow a user to get to know me, my profile picture appears on the landing page on all devices and is a NavBrand on other pages.  The contact me button is the only interaction on the landing page, in other pages the same functionality is available from the Navbar.  If a user decides they want to contact me then in one click directly on the landing page they can complete a simple form and submit this to my email.

Some users, depending on the information they have before they find the site may want a bit more information to decide if I am the right person to contact to assist with their issues.  In this case a page exists for my work history, including links to all past empoyers, there is a lot more text on this page for those that want more specific details on my employment history.

A dedicated page also exists to showcase some completed project work, these are presented in an image based slideshow with thumbnails below to allow the user to select any specific image and perhaps look at this in more detail.  The captions for each slide are shown above the images, these are very simple one line descriptions for each slide, for example one slide mentions a full user help system hosted in video format on Youtube, if someone had a need of this for any project this would answer the question 'can this person do this...?'  There are 3 projects highlighted, all display at almost full width on all devices, allowing a user to see some of the detail displayed on the slide.
These are all current live projects so in certain slides personal information has been obfuscated.

### Existing Features

1) Allows a user to see an picture of me, promoting a bond when we meet later on, this makes the website more personal
2) Allows a user to very quickly contact me from the landing page (or any other page)
3) A user can upload a file as they contact me, this also allows me to collect their name, email address and some details of the problem
4) A user can explore a collapsable time-line of my work history, this can be as simple as icons on the page, or these can be expanded to reveal main posts held in each employment
5) The skills page shows a series of progress bars covering my main skillset of Technologies
6) The projects page contains 14 slides across 3 projects, each with a single line synopsis of that slide

The site uses consistent themes throughout, a grey, blue and orange colour collection with 2 fonts families.  Box shadowing is used to lift buttons off the page and mouse hover will show this component is reactive to the users.  Titles are also shadowed but don't react to mouse activity.

A fixed footer exists on all pages, it contains social icons and a link to download a copy of my CV in PDF format, this is held in the assets/downloads folder of the site.

The system uses a Bootstrap Navbar menu system that has a white background to merge into the white background of each page.  On the landing page the menu uses a brand icon for Our IT Manager, on other pages this is replaced with a circular thumbnail of my profile picture that matches the larger responsive image on the landing page.  The projects item in the menu is sub-menued to allow a user to jump directly to any of the 3 projects on that page.  The Navbar will reduce to a familiar hamburger in the top right-hand corner on small screen resolutions.

All html pages incorporate html5 semantic headings where appropriate

### Features Left to Implement

Optional videos for projects might be quite nice, but many users won't have the patience to sit through a 1-2 minute video?  At this stage static screenshots will suffice.

The tumbnails under each of the 3 project slides would look nicer if they had a fixed height container rather than being fully responsive as thye are now.  They look good on smaller devices but on larger screens they take up too much screen space.

I have experimented with background images and colours but at time of writing a white background suits the profession approach that I am striving for.

History page, Orange Our IT Manager Ltd & Emma Bridgewater logos looks poor with the orange background on hover effect, this could perhaps be resolved by removing the png transparency?

## Technologies Used

- html5 <a href="http://www.w3.org/html/logo/">
<img src="https://www.w3.org/html/logo/badge/html5-badge-h-css3-semantics.png" width="165" height="64" alt="HTML5 Powered with CSS3 / Styling, and Semantics" title="HTML5 Powered with CSS3 / Styling, and Semantics">
</a>
Building blocks of this site

- CSS https://www.w3.org/Style/CSS/
A simple mechanism for adding style (e.g., fonts, colors, spacing) to Web documents.

- Javascript https://www.w3.org/wiki/The_web_standards_model_-_HTML_CSS_and_JavaScript#JavaScript_.E2.80.94_adding_behaviour_to_web_pages
Adding behaviour to web pages (only required to make the project slideshows function as desired)

- Bootstrap 4 https://getbootstrap.com/
Bootstrap is an open source, mobile first toolkit for developing with HTML, CSS, and JS.  A CDN link is included on each page

- Font Awesome https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
CDN used for download icon in the footer

- Gitpod https://gitpod.io/
Used as the primary IDE and to push committed changes back to Github

- https://onlinepngtools.com/create-transparent-png
Ref for adding transparent background for pngs used

- https://www.w3schools.com/bootstrap4/bootstrap_carousel.asp
- https://codepen.io/cassidoo/pen/MyaWzp
Both used for inspiration for slider control on projects page

- https://autoprefixer.github.io/
Auto-prefixer to ensure cross-browser compatability

- https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_slideshow_gallery
Slideshow gallery in projects 

- https://www.w3schools.com/bootstrap4/bootstrap_collapse.asp
Accordion used in the history page

- https://www.iconfinder.com/search/?q=social%20media&style=long-shadow
Social icons used on the footer, open license

- https://learn-the-web.algonquindesign.ca/topics/html-semantics-cheat-sheet/
Semantic tags for html5

- https://www.google.com/chrome/
Google Chrome developer tools used to itemise specific spacing issues and debug any problems

## Testing

The project was developed from start to end using Gitpod, using the inbuilt preview window to observe immediate effects.  Prior to important commit operations the terminal command python3 -m http.server and a port opened on my development laptop.  This allowed me to paste the exposed url into locally installed browsers
1) Google Chrome - Version 78.0.3904.97 (Official Build) (64-bit)
2) Mozilla Firefox - 70.0.1 (64-bit)
3) Internet Explorer - Version 11.476.18362.0
4) Microsoft Edge - Microsoft Edge 44.18362.449.0
5) Microsoft Edge (pre-production Beta of the next release) - Version 79.0.309.18 (Official build) beta (64-bit)
6) Safari on iPhone 10X - I don't have direct access to any Apple hardware, so tests carried out by helpful colleagues

There are 9 hyperlinks in the Navbar menu, for each browser above these are all clicked to ensure correct operation and target.  The Navbrand (left edge of the menu) should always return the user to the home page.
The footer is tested to confirm the mouse hover effect on the CV download link, the PDF should open in a new window.
The footer also contains 6 icons, 5 of these link to the home directory of the organisation eg www.facebook.com as yet they do not link to my account on each.  The 6th icon is an email link that when tested should use the users default email client to generate a blank email with my email address included.
The modal 'contact me' is tested from both the landing page (index.html) and the Navbar (contact) link. The form is tested to ensure those elements shown as 'required' must be entered before the 'submit' button can be clicked.  The email field should validate for email format (includes @ and a dot).
The history page uses an accordion to reveal details on an item and simultaneously hide any other open items, functionality is tested.  Each item (where appropriate) contains a link to the employer in question.
The projects page contains 3 javascript driven slideshows, these are controlled either by in-image arrows or by clicking the thumbnails below each main slide.  The thumbnails should be of a low alpha blend unless selected when they change to alpha=100%.
At the bottom of the projects page is a carousel of testimonials, this should be fully visible above the footer and circulate every 6 seconds (enough time to read the content).  If a mouse hover is detected the circulation should stop allowing the user more time.

The site resonded well on all devices and the only issue found was on a massive 4k display where the profile image wasn't horizontally centered in it's container, all other resolution displays hide this issue as the image naver gets to 100% height.  This issue was resolved.

I validated html at https://validator.w3.org
Results:
index.html - Document checking completed. No errors or warnings to show.
history.html - Document checking completed. No errors or warnings to show.
skills.html - Document checking completed. No errors or warnings to show.
projects.html - Document checking completed. No errors or warnings to show.

CSS validated at https://jigsaw.w3.org/css-validator/
Results:
Congratulations! No Error Found.
This document validates as CSS level 3 + SVG !

To show your readers that you've taken the care to create an interoperable Web page, you may display this icon on any page that validates. Here is the XHTML you could use to add this icon to your Web page:

Valid CSS!
<p>
    <a href="http://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="http://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>
            
Valid CSS!
<p>
<a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px"
        src="http://jigsaw.w3.org/css-validator/images/vcss-blue"
        alt="Valid CSS!" />
    </a>
</p>
        


## Deployment

The site resides in Github and the master repository is hosted on Gitpages.  I found multiple methods recommended to allow hosting on Gitpages but using the desktop version of Github didn't work as expected.  The solution was the procedure described here;
https://help.github.com/en/github/working-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

I chose to use the 'master' repository as the source for Gitpages, this means that each new push into the master repository will (within a few minutes) automatically update the published page.    

## Credits

Credit to the Code Institute https://codeinstitute.net/ 
Prior to starting the Full Stack web development course I had never written a single line of html or css

### Content

As the site is my resume, all content is my own.  Some links and icons\logos exist to past employers, these images are owned by the companies in question.

An image (called agreement) on the index.html (visible on mid to large devices) is an image purchased for use on another project, the usage agreement specifies unlimited use on web projects.  All other images are owned by myself. 

The projects page contains live data from current software projects, all visible metadata remains the property of the client who commissioned the project.  The layout and design of the screens displayed are the property of myself.

As detailed earlier in this file, fonts are used from Google fonts, icons from Font Awesome and icons from iconfinder.com, in all cases the only resouces utilised are free and the license wording on the respective owner sites confirms this.

### Acknowledgements

I would like to thank my wife Debbie for never ending patience while completing this project!
