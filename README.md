# dragons-dice-gaming-club

## A tabletop Gaming Club running regular gaming sessions and events

A Website for a local Tabletop Gaming Club based in the town of Portishead. The Website features images of the games run by the event, an explanation of the clubs goals and standards, a timetable of the Clubs regular activities and a page with upcoming major events being run by the club. The Primary two goals of the website is to advertise the club to convince new members to sign up, as well as provide information on upcoming events for existing club members.

The scale of the club is a few dozen members, enough to represent the local area, and is not intended to run as a "business". Consequently, while the Club does have Business Goals, they are conserneerd with maintaining and growing Club Activity rather than providing a service, and so the club's website is stuctured accordingly.

The Buisness Goals of the Website are:
- Build Awareness of the Dragon's Dice Gaming Club and what it does
- Convince new members to join up for club activities
- Display a list of upcoming events for new and old members, with a link to sign up for the event

The Customer Goals are:
- Learn more about the Gaming Club, including ehen and where it meets
- Learn about what activities and events the Gaming Club runs
- Easy procerss to sign up to the club or request more information

## UX

### Ideal user
There are two types of ideal user for this website - a New Visitor and an Existing Member. However, of the two, the New Visitor is the priority focus of the site, as existing Members can be expected to already know many of the details about the Clib, and only be visiting the site for updates on the Events page, while a New Visitor represents a potential new member to the club.

**The ideal New User:**
- A Tabletop Games player who engages with one or more gaming systems
- Disposable income (so they can afford the club fees)
- enough free time to be able to attend activities

**A Visitor to this site is looking for:**
- A gaming club they can join to play tabletop games
- information on both the club itself and any events being run

**This project acheives these goals by:**
- Providing information on the Club and what it offers a prospective new member
- Details on the Clubs' regular activities, including a timetable
- A link to a simple contact form to sign up to the club
- A seperate page detailing upcoming events being run by the club, with links to sign up for the event

**Client Stories**
1. As a New Visitor to this site, I want to learn more about what the Club does, so I can see if it meets my needs.
2. As a New Visitor to this site, I want to learn more about the Club's values, so I can see if it meets my preferences.
3. As a New Visitor to this site, I want to learn more about the Clubs regular activites, so I can see if it supports any of the games I play.
4. As a New Visitor to this site, I want to see when the Club is running, so I can see if I can take part.
5. As a New Visitor to this site, I want to be able to easily contact the club, so I can sign up or ask a question.
6. As an Exisiting Member of the club, I want to see what new events are upcoming, so I can see if I can take part.
7. As an Exisiting Member of the club, I want to be able to easily contact the club, so I can sign up for events or request new information.

**Wireframe Mockups**

Desktop View - Main Page
![Wireframe Main Page](https://github.com/user-attachments/assets/6acd07af-8566-4446-b3e4-611376429b6d)

Desktop View - Events page
![Wireframe Events Page](https://github.com/user-attachments/assets/c3890bd4-bbee-4fac-bcdd-0bb0f8b882fd)

Mobile View - Main & Event page
Due to the limited width of the typical mobile sized screen, the Main and Event page use the same structure on Mobile screens
(I also apologise for the slighty fuzzy nature of this image - the camera unfocused last moment, it seems)
![Wireframe mobile view](https://github.com/user-attachments/assets/71adb33d-da07-4b48-bfff-e0965bab8593)

Contact Form
![Wireframe Contact form](https://github.com/user-attachments/assets/0dfc3037-c4de-41a1-a9e0-fce530f0a1e3)

## Features

Each page features a Responsive Navigation bar (Nav Bar) that collapses on smaller screens. The Clubs Logo is positioned on the left side of the bar and contains a link which leads back to the homepage, with the navigation links on the right hand side. The Nav Links collapse into the classic "Burger" icon on smaller screens, and the active page is highlighted on the Nav Bar.

**Home**

The Home page, referred to as the Index page within the code, is the main page of the website, and serves the main purpose of providing all the information about the club for prospective new members.

After an introductory, welcoming paragraph, the Header of the Home page contains a Carousel of Images featuring images of several of the game systems that are available to be played at the club. The intention of the image carousel is to catch viewers interest, and prompt them to keep viewing the webpage if they see anything that interests them.
While Autoplayng Carosels are not generally advised due to accessibility reasons, one is included here because the trade off of being able to show several eye-catching images in a single section of screen space is considered acceptable in the context of the website - namely being that of a fairly small gaming club.

The next section is titled "About Us" and is a explanatory paragraph outlining the general purpose of the club - providing a communal environment for tabletop gamers to play games together - and providing an example of some of the many games systems supported at the club. It also outlines the Charity work done by the Club, as well as offering a call to action to submit any questions using the contact link in the Nav bar
This section includes a Stock Image of people playing a Card Game before a new section detailing the Club's values and commitment to inclusivity.
finaly, the section concludes with a breakdown of the benefits of membership of the club, the costs involved, and ends with a call to action with a button linking to the contact form to sign up to the club

The following section contains information on the clubs regular meeting place, St Mary's hall - a Village hall rented by the club. As well as two images of the exterior and interior of the hall, the section also includes a description of the facilities available at the hall, as well as information relavant to club gaming activities (the availability of terrain to use)

The final section of the main element details the clubs regular activities, explaining what those activities ential and providing a timetable displaying what days and at what times the activties run. There is also a breif disclaimer about entry fees for non-members (intended to promote joining the club as a way to save money on regular attendance)

The Homepage is closed out by a footer, which has the address of St Mary's Hall, a contact phone number for the club and a contact email, as well as links to the clubs Social Media pages on Facebook and Instagram.

**Events**

The Events page contains a brief introduction to the types of events run by Dragon's Dice Gaming Club, including more information on the Charity Events run by the club, and a call to action to sign up to any events using the buttons on the Event Cards.

A List of Cards containing details on upcoming events is then displayed. the list is responsive to screen size, and each card contains the Event's title, the date it is running, an image, a brief description of the event and a link that leads to the contact form page so users can sign up to events.

the Events page is also closed off by the same footer as the Home page

**Contact Form**

The Contact form is a standardised form that allows users to message Dragon's Dice gaming club, to join the club, join an event, sign up for the newsletter or even just ask a question.

The Contact form consists of four fields, all of which are required to successfully submit the form - the Users name, a contact email address for them, the reason for contacting them, and the content of the message itself - all of these are text fields are text entry fields, except for the contact reason, which is a drop down listing the most common reasopns for contact: Sign up to club, sign up for Newsletter, Sign up for an event or Question/other message.
All the entry fields are mandatory, which prevents an incomplete form being submitted.
Filling out and Submiting the form through the Submit button will take the user to the Success page.

The Contact form does not contain the usual footer, as it is not a "main" webpage - rather than contain information to be browsed, it has a direct purpose in enabling contact with the Club's admin team, so is focused solely on that.

**Success**

The Success Page is a simple page acknowledng the successful submission of the Contact Form, and prompting the User to return to the Home page via a link.

Like the Contact page, the Successpage also does not have a footer.

### Active Features

- **Home Logo:** Part of the Nav Bar on every page, allows user to recognise the Club Logo. Links back to homepage as per convention.
- **Header Nav Bar:** Appears on every page, provides a conventionally recognisable and intuitive form of Navigation.
- **Footer Contact info:** Appears on the Home and Events page, allows user to locate the venue and contact the club administrators.
- **Footer Social Links:** Appears on the Home and Events page, allows user to access social platforms the Club is on.
- **Call to Action Buttons:** Present on every page, in some form. Acts as a prompt to allow users to interact with the club
- **Home Page Carousel:** adds visual appeal by displaying club actvities, engaging the interest of potential users.
- **Club Information:** gives information on the Club to prospective users
- **Location Information:** gives information on the location of the club to prospective users
- **Timetable:** sets out when the regular activities at the club occur, allowing potential users to plan their visits to the club
- **Events Cards:** Clearly set out individual events being run by the club, with a breif outline and a call to action to allow for users to easily join the event
- **Contact Form:** A clear and straightforward form to allow for users to contact the Club, to perform any of the actions they have been previouslty prompted to do.

### Additonal Features to add in future

  - News page: a page offering several articles from the Club's Monthly Newsletter, with a link to sign up to the Newsletter via the Content page. this waould also entail expandingf the Nav Bar to accomodate a new main page. This was not implemented due to timing constraints.

## Technology used

This Project with made using HTML, CSS and Javascript*
- The IDE used was Visual Studio Code (VSCode)
- Website is hosted on GitHub (https://github.com)
- Bootstrap CDN v5.3.8 was used in the construction of this Webpage (https://getbootstrap.com/)
- FontAwesome was used to generate the Social Media Icons used on this webpage (https://fontawesome.com/)
- The Favicon logo was generated by Favicon.io
- HTML and CSS Validated with W3C Markup Validation service (https://validator.w3.org/) and W3C CSS Validator Service (https://jigsaw.w3.org/css-validator/)
- Autoprefixer CSS Online used to validate the CSS code for all browsers (https://autoprefixer.github.io/)
- Code was Formatted using Prettier - Code Formatter extension availble on VSCode Extensions Marketplace
(* Javascript included in Bootstrap) 

## Testing

### Functionality

The Webpages were tested on the following criteria to assess their functionality:

| Test Label | Test Action | Expected Result | Test Result |
|----------|----------|----------|----------|
| Event Navigation | Access Events Page via link in Nav Bar | Event Page opens |  PASS  |
| Home Navigation | Access Home Page (from events page) via link in Nav Bar | Home Page opens |   PASS  |
| Contact Info Navigation | Access Contact info in footer via link in Nav Bar | Scrolls to bottom of home page |  PASS  |
| Contact Form Navigation | Access Contact Form via button in Nav Bar | Contact Form opens | PASS |
| Carosel Auto-Play | Wait to see if Carosel on Home Page autoplays | the Carousel images cycles on its own | PASS |
| Contact Form Navigation 2 | Access Contact Form via button on Home Page | Contact Form opens |  PASS  |
| Contact Form Navigation 3 | Access Contact Form via buttons on Event Page cards | Contact Form opens |  PASS  |
| Contact Form Required Fields | Submit form with different input fields unfilled | Contact form does not submiy while input fields are empty |  PASS  |
| Contact Form Submission | Submit completed form | Success Page opens |  PASS  |
| Success Page Navigation | Access Home Page via "return to homepage" button | Home Page opens |  PASS  |
| Navbar links - Contact Form | Access Home/Events Page via Nav Bar links | relevant page opens |  PASS  |
| Navbar links - Success Page | Access Home/Events Page via Nav Bar links | relevant page opens |  PASS  |
| Logo Navigation | Access Home Page via clicking on Nav Bar Logo on all pages | Home page opens |  PASS  |
| Responsive screen | Layout of all pages change at pre-determins breakoints | Layout changes at certain breakpoints |  PASS  |

All Code was also validates using the online W3C HTML Validator and CSS Validator - no errors were discovered during this Validation.

When subjectesd to Lighthouse testing, a lag in performance of about 66 on mobile and 75 on Desktop (all other metrics tested well) - upon looking into ways to improve this, it was detrermines (with help from Brian Macharia) that large image sizes may be contributing to the issue - all JPEG images were re-formatted into smaller WEBP images with less pixels. This improved the score of the mobile load to 73 on mobile (no discernable effect on desktop), but was still slower than was ideal. On further review, it was determined that the images could be perhaps made smaller still, but constraints with time prevented this being implemented. For now the performance score must remain as it is, but if carried on in future, this project would look to decrease the image sizes further to promote faster loading.
(A contributing factor to the images large size may be that many of them were photographs, and thus not optimised for digital display)

### Browser Compatibility

The Webpage was tested on the following Browsers:
- Google Chrome
- Mirosoft Edge
- Firefox
- Safari

On all tests browsers the manual tests were repeated, and on all browsers they passed the tests

### Responsiveness

The webpage was tested for responsiveness on the following screen sizes:
- Mobile (360 x 740 approx)
- Tablet (1024 x 1366 approx)
- Laptop/Desktop screen (1920 x 1080 approx)

On all sizes tests, the layout changed to match that determined by the code breakpoints. One area was identifies where the layout was less than opitimal on Screen Sizes between 992px and 768px, where the Timetable on the Home page was loading in two columns - this was changed to load into two columns at the large Breakpoint (992px) instead of the medium (768px), providing a better viusal experience at these sizes.

There is still some issues at extreme screen sizes (2000+ px), with the content being centered in the middle of the screen, but this seems to be due to the Containers the content is stored in being capped in size at 1980px. However, as the average screen size seems to be 1980x1080, this is not a priority issue, as it is unlikely to come up in the websites theoretical regualr use.

### User Stories

1. As a New Visitor to this site, I want to learn more about what the Club does, so I can see if it meets my needs
This is met by the "About Us" Section of the Home Page

2. As a New Visitor to this site, I want to learn more about the Club's values, so I can see if it meets my preferences.
This is met by the "What we stand for" section of the Home Page

3. As a New Visitor to this site, I want to learn more about the Clubs regular activites, so I can see if it supports any of the games I play.
This is met by the "Weekly Activities" section, as well as by information in the "About Us" Section of the Home Page
   
4. As a New Visitor to this site, I want to see when the Club is running, so I can see if I can take part.
This is met by the "Weekly Acivities " Section of the Home Page

5. As a New Visitor to this site, I want to be able to easily contact the club, so I can sign up or ask a question.
This is met by the Contact Form and the "Contact Information" in the Footer on the Home/Event Page. It is enabled by the Buttons on the NavBar and Home Page to the Contact Form

6. As an Exisiting Member of the club, I want to see what new events are upcoming, so I can see if I can take part.
This is met by the Events Page
    
7. As an Exisiting Member of the club, I want to be able to easily contact the club, so I can sign up for events or request new information.
This is met by the Contact Form, via the links on the Event Page for each Event

## Deployment

This project was developed using the VSCode IDE, committed to git and pushed to GitHub Pages.

To deploy this page to GitHub Pages from its GitHub repository (https://github.com/TiredSkitarii/dragons-dice-gaming-club), the following steps were taken:

- Logging into GitHub.
- From the list of repositories on the screen, selected TiredSkitarii/dragons-dice-gaming-club.
- From the menu items near the top of the page, selected Settings.
- Scrolled down to the GitHub Pages section.
- Under Source clicked the drop-down menu labelled None and selected Main Branch
- On selecting Main Branch the page was automatically refreshed, the website was then deployed.
- Scrolled back down to the GitHub Pages section to retrieve the link to the deployed website: https://tiredskitarii.github.io/dragons-dice-gaming-club/

At the moment of submitting this Milestone project the Development Branch and Main Branch are the same.

### How to run project

To clone this project, you will need the following:
- a Github account (create at: https://github.com)
- access to an IDE (such as VSCode)

1. Go to this projects Github repository: https://github.com/TiredSkitarii/dragons-dice-gaming-club
2. select the downwards arrow on the green "<> Code" button
3. Select the Local tab in the dropdown
4. copy the HTTPS URL displayed
5. Go to your chosen IDE and open a New Terminal
6. Change your Working Directory to where you would want the cloned repository to be saved
7. type "git clone" then add the copied URL
8. Press enter to clone the Repository

## Credits

### Content
- All Text for all pages was written by Jakob McLaughlin (TiredSkitarii)
- Proof-reading performed by Jakob McLaughlin
- Fonts were acquired from Google Fonts (https://fonts.google.com/)

### Media
- Stock Photos were downloaded from Stock Photo website Pexels: www.pexels.com
   - The Photo of People playing Cards was originally taken by Pavel Danilyuk
   - The Photo of the Merry Christmas Sign was originally taken by Brett Sayles
-  Photos of Greyfriars hall (used as a stand in for the fictional St Mary's hall) were taken by Vincent McLaughlin
-  All other Photos taken by Jakob McLaughlin
-  All Photos were compressed into WEBP Files using: https://www.freeconvert.com/jpg-to-webp
-  All Models and Minatures depicted come from the personal collecton of Jakob McLaughlin

### Code
- The Nav Bar and Event Cards were created using the generic Code from Bootstrap as a basis, and was customised with reference to previous code written for Code Institute Example projects Love Running and Boardwalk games.

To Clarify what is mean by reference - the Example project code was used to reference what a working example of a feature looked like and was used to inform what the finished code should have roughly looked like.

### Acknowledgements
- Inspiration for the project was received from my own background and hobbies
- Special thanks to my Mentor Brian Macharia for his support and suggestions along the way
- Special Thanks to Vincent and Jozef McLaughlin for assistance with taking pictures and testing
- Special Acknowledgment to Sam Smith for agreeing to be the model holding the Magic: The Gathering Cards for the one picture

#### Disclaimer

This Website is intended for educational purposes only. No such Gaming Club exists in real life, and there is no such St Mary's Hall. All Emails, Phone Numbers and Addresses included in the Website are fictional.

All models displayed belong to the private collection of Jakob McLaughlin, and do not represent any endorsment. support or acknowledgement of the relevant model manufacturers. All relevant Copyrights and Tredemarks belong to their respective companies.



