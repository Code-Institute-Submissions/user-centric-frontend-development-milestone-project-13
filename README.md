# Milestone Project 1 - User Centric Frontend Development

## Project Description
The purpose of this project was to create a static website using the skills and techniques 
we've learned in HTML and CSS. I decided to design and create a website for a Hypnotherapy business,
as it's a discipline I'm currently practising in, and so I felt I had enough knowledge to structure a user's 
journey appropriately. 

The area of hypnotherapy I chose to focus on was providing hypnotherapy solutions and support primarily for
learners and creators (writers, muscians, etc). The unusual area would also challenge me to create, not just a visually
user-freindly design, but also in terms of quality content.

## UX 
### User Background
My approach to the UX design was to first establish the feelings I wanted to invoke in the user. 
To do this, I had to consider who the user likely was. In this case, it could be someone of any background, 
but who is looking for support and guidance to achieve a personal goal (eg to learn a new language or create something).
This person is likely stressed, frustrated and possibly anxious. So the feelings I wanted to envoke were those of
comfort and trust.

I also considered the user's expectations before they entered the website. For some, Hypnotherapy might be associated
with spiritual approaches rather than phsychological, which may turn potential clients off. To avoid triggering a
reflex skeptical response from a user, I decided to choose "grounded" and earthly colours, instead of sky-associated 
palettes of blues and pinks (commonly used in spiritual-related media) as well as floral images.

With these elements in mind, I concluded the most advantagous theme for this business would be a mixture of warmth, tradition,
logic and a feeling of prestiege. By combining these, the user would be more likely to engage with the website and 
increase conversion rate.

### Market Research
I conducted some market research by searching for websites of the brands most associated with trust and prestiege and knowledge.
I visited the websites and took note of the structures, colors and content, to better understand what a user expects 
in those contexts. World reknowned universities, government websites, luxury hotels, cars, jewelry and prestiegous
media companies, all designed to encourage trust in their brands were included in the samples.

I noticed the frequent use of dark blue and white (or off-white) and with older brands, the importance of a strong, 
elegant and clean logo. 

### Logo
I had a logo design that conceptually would be suitable. So with the help of a graphic designer (Eoin Brennan), I 
had a digital version made, with the instruction for it to be made square, more elegant, with a better negative space ratio.
The logo is of two N's, the second one overlapping the first. As this website is about learning and becoming a more 
improved version of yourself, the image of the second letter overlapping the previous, seemed fitting. 
The N is from my surname, as this website was for my own potential hypnotherapy business. This logo will feature on the 
top left hand corner of each of the webpages as part of the navbar.

### Colour Palette
As mentioned previously, a deep blue was very frequently used in the samples I researched. I chose a dark green as
the most distinguished colour as it would have a similar sense of depth, but with the added benefits of being more
unique. The colour reminded me of forest vegitation, which allows me to incorporate the calming influence of 
nature, without veering into the more spiritual assocations. This green is also reminiscent of leather chairs and
leather topped desks which used to sit in studies and offices - again reminding the user of knowledge.

Accompanying the green would be cream and yellow and light browns, to resemble parchment, leather, wood and brass.

### Font 
A cursive font called "Tangerine" was selected to be the main title fonts (for all except the jumbotron). The font
style was legible while resembling the writing of a fountain pen.

Roboto was chosen for the text of the main body for its clear and easy-to-read appearance.


### Images
To give a sense of authenticity to the website, all the images used were photographs taken and edited by me. Books,
pens, paper and brass items were the subjects in the images.

### User journey
I identified the following as user goals/needs:
1. To learn whether the services are applicable to their situation.
2. To find more information on hypnotherapy.
3. To find tips for their issue.
4. To find contact information to avail of the service.

To build a quick sense of familiarity, the navbar and footer are the same colours (dark green background, yellow for
unactivated font and cream-white for activated text items). Apart from a different text item being activated, the
structure, content and location of the navbar and the footer will be the same for each webpage.

The navbar has each page listed, with the two main sections mentioned as a dropdown menu for the FAQ page.
The footer features three sections, a vertical navigation, quick links to different services available and links to
social media (not yet linked to accounts, only respective home pages). 

On the first page (the home page), the user sees a jumbotron with a button directing them to the Contact page. Underneath, 
there is a brief description to inform the reader of the types of problems the business aims to solve. 

The parallax effects used were inspired by the an example project, featured on Code Institute's website.
This effect is used at the top of each page (underneath the navbar) and sometimes further down the page.
This feature was added to make the website feel more interactive. 

Bootstrap was used in addition to custom code to produce a dynamic responsive design for mobile, tablet and desktop 
use of this site. This included the repositioning of text over images to ensure legibility.

To address the user's needs, as identified above, an About page and a FAQ pages were used to provide more information. 
The collapse feature in bootstrap was used for the questions and answers section (to be expanded in future versions).

Finally the Contact page completes the user's journey, with contact information, a form to send an inquery and lastly an
options to sign up for a newsletter.

## Features
### Current Features
- About page - Explains the background of the business, including Aims and Philosophies
- FAQ page - Hypnotherapy section addresses concerns regarding hypnotherapy
- FAQ page - Services - Gives the user more information on the structure of the services provided
- Contact page - Allows the user to get in contact for business services
- Newsletter sign-up - Allows the user to sign-up for monthly emails

### Future Features
About the Hypnotherapist - A section is to be added at the bottom of the About page.
FAQ - More questions and answers to be added to the FAQ page.
News page - A page for blog posts is to be added after the contact page.

## Bugs
The most pressing issue that occurred with this project was the use of parallax effects.
While it is easily implemented, it caused issues regarding the z-indexes of dropdown features.
One instance was the dropdown in the navbar, which pushed down the opaque layer over the parallax.
This issue was eventually resolved. The second instance, however, persisted. On the FAQ page, the collapse 
feature from Bootstrap greatly affects the content below. A solution has not been found, as the issue frequently 
seems to eventually rectify itself once the page has been loaded for a time. When asking my mentor in one instance
of this, after adjusting the screen a few times, the issue would spontaneously disappear and could not be replicated
until later if the page was reloaded after a while.

## Testing
The css stylesheet was inputted directly into the W3C CSS validator and approved. All pages - index.html, about.html,
faq.html and contact.html - were inputted directly into the W3C Markup validator. Errors and warnings for each page 
were addressed and then the page was rechecked through the validator. The process was repeated until no warning remained.
All four html files and the css stylesheet have been validated.

Manual testing was carried out on all the links on every page - all links in the footers and the navbars.
The read more and sign-up buttons were all checked as well. 

The collapse feature on the FAQ page resulted in a bug being identified, however, it was not possible to rectify it yet.

The website was inspected using Google Chrome Dev Tools to view it on mobile and tablet versions. Each page was viewed
and tested in these views.

## Deployment of Website
This webiste was developed using gitpod and stored in repositories on Github. Gitpod was installed as an extension
tool on google Chrome, which was accessed then via the project's repository page on Github. This allowed for 
regular version control updates:
1. git add . was entered into the command line interface to add files to the staging area.
2. git commit -m "" committed the files to the repository.
3. git push -u origin master pushed the master branch.
 

The website was deployed using Github Pages. To do this, while in the github webpages of the project repository, 
I accessed the Settings Tab. Under the GitHub Pages section further down the page, is the option to choose Source.
I switched the default option of none to master branch. Then I retrieved the provided link to my deployed website.

Link to Deployed Website:
https://erikan-ir.github.io/user-centric-frontend-development-milestone-project/.

To run the project locally:
1. Follow the link below to the project's Github repository page.
2. Click on Clone or Download.
3. Copy the link provided.
4. Enter git clone into the command line interface.
5. Paste in the copied link and press enter.

## Technology
1. GitHub was where the files were stored.
2. Gitpod was the editing environment used to create and edit files.
3. [Bootstrap 4](https://getbootstrap.com/) was used for navbar, forms and for its grid system to improve responsive design.
4. [Font awesome](https://fontawesome.com/) was used to provide icons.
5. The parallax effect used js code from the following [source](http://pixelcog.github.io/parallax.js/).
6. The photos were taken using a Oneplus 6T phone and edited using the phone's build-in photo software.
7. [Google Fonts](https://fonts.google.com/) was used to provide the fonts.
8. [Coolors](https://coolors.co/) was used to generate a color palette.
9. [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) was used to validate the style.css file.
10. [W3C Markup Validator](https://validator.w3.org/) was used to validate the following files: index.html, about.html, faq.html and contact.html.
11. [HTML Fromatter](https://www.freeformatter.com/html-formatter.html) was used to format the following files: index.html, about.html, faq.html and contact.html.


## Credit
- Thanks to Reuben Ferrante for advising as mentor on this project and to Eoin Brennan for providing the logo file.
- Inspiration for the use of paralax effect came from the [sample project](https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/) on the Code Institute website.
- The implementation and link to the source of the js code for the parallax was guided by the [youtube tutorial](https://www.youtube.com/watch?v=d34GsFz-HkY&t=609s) by [iEatWebsites](https://www.youtube.com/channel/UC0o60y3FtVy3M93JcDFVreA).
- The code used in the construction of the navbar was obtained from the Code Institute "Whiskey Drop" tutorials.
- The code used to style the social links in the footer of all the webpages, came from Code Institute's mini-bootstrap (resume project) tutorial.
- The inspiration for and part of the code used for the timeline/navigation feature in the footer came from Code Institute's mini-bootstrap (resume project) tutorial.
- The css code structure for the jumbotron and contact form buttons were modelled on the [Facebook](https://www.facebook.com/) Sign up button (for the 3D effect).

