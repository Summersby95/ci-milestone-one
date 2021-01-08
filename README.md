# Star Wars Knights of the Old Republic Petition Page

_Knights of the Old Republic_ was a landmark game released in 2003 that changed the face of modern role playing gaming forever. It's revolutionary combat mechanics, interesting characters, engaging story and ground-breaking player agency are still felt today in the games it has helped inspire.

While the game was revolutionary for it's time, it's graphics and core gameplay mechanics have aged poorly which tends to dissuade new players from experiencing and old players from revisiting this masterpiece.

Today, remasters of games are very common and there is a devote group of Star Wars game fans who are dying for _Knights of the Old Republic_ games to get a remaster. The goal of this project is to garner support and interest in the game and provide a method and resource for users to submit their thoughts to EA, the company who own the right's to the Star Wars game franchise.

![KoToR Logo](/images/kotor-logo.png)

## UX

### Goal

The goal of this site is to make users aware of the game series, some of it's interesting aspects, why it deserves to be remastered and to enable the users to fill in a brief form that will petition EA to remake the game.

### User Goals

- Find information about the game series
- Images/art from the game
- Form to send a petition to get the game remade
- Site should give a feel of the game series/Star Wars Universe


### User Stories

- As a user, I want to see images from the games
- As a user, I want information about the games
- As a user, I want to see how the game relates to other Star Wars properties
- As a user, I want to get a feel for the game


### Site Owner Goals

- As the site owner, I want the site to have a theme consistent with the game series and Star Wars franchise as a whole.
- As the site owner, I want to entice visitors into wanting to play this game and help get it remastered by signing the petition.


### Design Choices
---

For this project I wanted the font and colours to replicate the colours and fonts found in the game. Below you can see an image from a dialogue interaction in the game. As you can see the text is coloured blue, with the highlighted option coloured yellow. I used [HTML Color Codes](https://html-color-codes.info/colors-from-image/) to upload a picture of the games dialogue and figure out the exact colours used.

![Dialogue Example](/images/dialogue-example.jpg)

To fit the theme of the game I decided normal text would have blue text and that clickable elements would use the yellow font colour when hovered over.

Another design choice I wished to use was to incorporate the overall Star Wars theme into the site. To achieve this I decided to use a starry night background for the page, reflecting the players ability to travel around the galaxy in the game.

![Starry Background](/images/starry-background.jpg)

In combination with this starry background I wanted to create a parallax effect similar to the one on the [Firewatch](https://www.firewatchgame.com/) video game website. I thought this was a beautiful effect and I decided to attempt creating a similar illusion on my site by using a static background night sky and a transparent foreground with *stars* which follow the scroll behaviour thereby imitating the night sky.

To highlight this effect, I decided to use transparent backgrounds on my body elements, which also gives the illusion of the text floating in the sky like the infamous Star Wars text crawl used to set the opening stage in movies.

![Opening Text Crawl](/images/text-crawl.jpg)

One of the central gameplay mechanics of the game is player choice in both dialogue and combat, in particular the player can choose do to *good* deeds or *bad* deeds in a given scenario, the outcome of which will turn them to either the *Light* side of the Force and become a more powerful Jedi, or the *Dark* side of the Force and become a more powerful Sith.

This mechanic is integral to the role-playing, player choice driven ethos of the game and something I was keen to incorporate into the site's design. As such I decided to add a question to the bottom of every page with four options. Depending on the user's decision the green and red lightsabers would change length to reflect where the player's decisions fit on this fictional morality scale, imitating how player decisions affect the story of the game.

![Morality Question Example](/images/question-example.png)

Two of the key elements of the game I wanted to portray to the users was the characters and planets that exist in the game and distinguish them by their alignment, good or bad. To achieve this, I found a green and red colour palete to represent the good and bad characters/planets respectively and used some photoshop skills to create two images, halves of the same lightsaber that would act as a divider between the two character/planet alignment sections.

![Alignment Divider Example](/images/alignment-example.png)

### Wireframes
---

[Click here to view wireframes.](/wireframes/kotor_site_wireframes.pdf)

When drawing up wireframes for the site, I felt the best way to immediately convey to a new user the purpose of the site was to have the game logo at the top of the page with the text *Remaster* beneath it. I also felt the navigation bar should appear centred in the screen beneath the logo as opposed to one side which would look out of place.


#### Home Page

Beneath the header, logo image and navbar I decided to place a call to action with a picture that would immediately direct to the petition sign up page when clicked. I felt these elements combined with the header logo and navbar would make it immediately clear to a new user about the sites content.

Having finished the top of the page, I felt it was important to explain a bit about the game and why it deserves to be remastered. I felt this information was important to keep on the home page and not hidden on a different page.

I also decided to place a timeline on the home page that will help users familiar with the Star Wars Universe but unfamiliar with the game understand the point in time that the game takes place in reference to other Star Wars events.

![Home Page Wireframe](/images/wireframe-home.png)

#### Characters/Planets Pages

One of the user stories was *'As a user, I want information about the game'* and I felt that describing the various interesting characters the player has an opportunity to interact with and the locations they have can visit in the game was a good way to fulfil this requirement and also garner interest in the user to sign the petition to get it remastered.

On these pages I wanted to use the lightsaber divider idea which I explained above. I felt it was a good way to convey to users the difference between the characters and their respective alignments.

![Characters Page Wireframe](/images/wireframe-characters.png)

#### Petition Form Page

I wanted the petition page to be clean and simply contain the petition form itself and possibly a few images with the same light versus dark theme.

I also wanted the form to contain as few fields as possible to not discourage users from signing it.

![Petition Page Wireframe](/images/wireframe-petition.png)

## Features
---

Current Features

* Navigation bar that allows users to navigate site easily
* Carousel highlighting different elements of the game with clickable captions to take users to more information about it
* Parallax background that gives illusion of night sky when scrolling, immersing player in the Star Wars theme
* Timeline highlighting when *Knights of the Old Republic* takes place in the Star Wars canon
* Dynamic lightsaber divider on characters and planets pages
* Morality questions at bottom of every page to further engage users in game experience
* Form to submit petition to get the game remastered available to users
* *Call to Action* at top of pages to immediately direct users to petition form

Future Potential Features

* Dynamic lightsaber divider movement based on answers submitted by users on site. Specifically, the divider will grow brighter/adjust position depending on the proportion of people who chose light versus dark side answers
* More character and planet features
* Videos depicting gameplay from the games
* Enhanced Parallax Effect, additional layers moving at different speeds


## Technologies Used

### Languages

* HTML5
  * Used for core structure and layout of pages
* CSS3
  * Used for styling of page elements as well as colouring, adding hover effects, adjusting dimensions of elements
* JavaScript
  * Short script used to change morality meter lengths depending on chosen answers. Also used by Bootstrap library
* JQuery
  * Used by Bootstrap CSS Library

### Tools and Libraries

* Atom
  * Text-editor used for development
* Git
  * Used for version control and maintaining repository of project
* Atom Packages/Extensions
  * Live Server: Package used to create localhost server to preview pages during development
  * Emmet: Syntax shortcuts that make creating elements easier
* Bootstrap
  * CSS/JS library used for core structural layout of elements
* Google Fonts
  * Used to import fonts for use in site
* Font Awesome
  * Used to import icons to site
* Chrome Developer Tools
  * Used in debugging and validating changes made as well as checking site responsiveness on various screen sizes


## Testing

HTML validation was done on all pages using the [W3C Markup Validator](https://validator.w3.org/) and CSS validation was accomplished using the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Both completed without any errors. However, when validating my stylesheet I received several warnings about unknown vendor extensions referring to my root variable colour using the -- prefix. I was unable to fix this issue at the time of writing.

There were a number of features and elements to test in this project.

* Yellow Hover Effect
  * One of the effects used frequently throughout the site was the blue-to-yellow hover effect described above and inspired by the dialogue from the game. Initially, I created background colour classes which set the background colour, font colour and border colour for the elements it was assigned to. I then created hover classes for all these background colour classes which changed the colours to yellow. However, after testing and demoing to potential users, I found that when the yellow hover colourings took over they misled the users into thinking that the all elements were clickable and linked to something or performed an action. Users also reported that they found they effect distracting due to it's prevalence on the site. As such, I removed the hover classes from the background colour classes and created a seperate *yellow_hover* class to that would add the effect on elements that served a function, carousel controls, links etc.
* Lightsaber Dividers
  * The Lightsaber dividers on the *Characters* and *Planets* pages required a lot of testing. For large and extra large screens I wanted the *light* (green) side and *dark* (red) side to appear side by side with the lightsaber divider down the middle, but on smaller sized screens I wanted the dark side to wrap beneath and the red half of the light saber to appear on the left side of the feature divs. I spent a lot of time initially trying to find two distinct lightsaber images that could fit my purpose. However, I needed the images to be vertically aligned, high resolution, green and red and, most importantly, have a transparent background that wouldn't look out of place or obscure the night sky background I was trying to achieve. Having tried several images as a potential prospect but to no avail, I was forced to ask a friend, skilled in photoshop to assist me in crafting the end result. Having found the right images it took a lot of testing of CSS rules to ensure the lightsabers behaved as intended on all screen sizes.
* Parallax Effect
  * Very much like the Lightsaber dividers, I spent a while trying to source appropriate images to use as the background and foreground images to achieve the parallax effect. I was eventually able to find images that suited my needs however I struggled to achieve the desired effect. After searching I found a very useful [W3 Schools Article](https://www.w3schools.com/howto/howto_css_parallax.asp) which described how to achieve the effect I desired. After further adjustments to my DOM and testing I achieved the desired effect.
* Timeline
  * One of the features that I thought would be quite useful to potential newcomers to the game was a timeline to help contextualize the game's time in reference to other Star Wars properties. Much like in the [Rosie Resume](https://summersby95.github.io/ucd-resume-ci/resume.html) mini project which proceeded this milestone project in the Full Stack Web Development course, I wanted to create the timeline using CSS after and before pseudo classes, as opposed to an image or other feature imposed on the screen. This [W3 Schools Article](https://www.w3schools.com/HOWTO/howto_css_timeline.asp) was also incredibly helpful. A lot of testing and adjusting was required on this element to prevent text spilling out of the timeline area and ensuring the timeline as a whole did not take up too much real estate on the home page.
* Alignment Questions
  * The alignment question feature at the bottom of every page was a feature not in the original design or wireframes of the site, however, when the thought occurred to me to add it, it seemed like a no-brainer given the importance of player choice in the game as well as the site. I also felt it would improve user engagement and encourage further interactivity with the site. While the basic layout for the site was not difficult to implement through the use of standard *Bootstrap* elements, figuring out how to get the answers to trigger a response in the progress bars was quite difficult. I initially envisioned using a CSS hover or active pseudo class to trigger a width change on the progress bar. However, after many unfruitful attempts I was resigned to the fact that I would have to use JavaScript to achieve the desired effect. This proved troublesome also however. I have had modest experience using JavaScript on other projects previously and, in combination with [Bootstrap Documentation](https://getbootstrap.com/docs/4.0/components/progress/) I was eventually able to achieve the desired effect.

## Bugs

I encountered several bugs and issues when developing this site, below is a list of a few and how they were solved.

#### During Development

* Blank space beneath footer despite nothing there
  * Mentor suggested adding html { height: 100% } to reset, worked
* Lightsaber dividers not wrapping to left/right of features on small screen sizes
  * Adjusted classes on elements, discovered col-sm-x doesn't exist in Bootstrap 4, replaced with col-x to achieve desired effect
* Answer text overflowing answer area on small devices, not becoming single list insetead of side-by-side
  * Mentor pointed out I had put a height constraint over the parent element preventing the areas from wrapping
* Carousel captions obscuring images, not centred under image
  * Adjust carousel-caption class, increase carousel container height and move caption elements beneath images, add margin-left, margin-right, left and right attributes to carousel-caption class to center.
* Width of page not matching width of viewport, exceeding viewport width
  * Adjust text in timeline and padding on some elements

#### From User Demos

* Center features taking up too much page real estate on page
  * Add width constraint on section element and margins to center
* Text difficult to read with colour pallete
  * Adjust background and text colours to make text more legible
* Yellow Hover Effect Distracting
  * Remove hover classes from background colour classes and create seperate yellow-hover class and apply to clickable elements only
* Alignment Question answers not working
  * Check JS function, and fix id typo that was preventing the function from working
* Features not aligned vertically, horizontally on page
  * Adjust margins and paddings on various elements
* Header Image and text taking up too much real estate on screen
  * Adjust div height

#### From Validatiors

* H5 element in alert not closed
  * Add closing tag
* No semi-colon after attribute value in stylesheet
  * add semi-colon

## Finished Site/Reflections


I would like to place my reflections and final thoughts as I wrap this project up. Overall, I am pretty happy with the finished project and believe it fills the requirements I set out for it.

### Home Page

![Home Page Preview](/images/home-page-preview.png)

I am happy that I was able to achieve the parallax starry sky effect that I sought to create though I would have like to possibly add a few more layers and make it more dramatic. I feel it fits the theme of the site very well and makes it clear on first glance what the site is about.

The *Call to Action* alert element immediately directs the users to the petition form. The carousel element beneath it shows interesting aspects from the game and to entice the user and links to where they can find more information about them.

![Home Page Lower Preview](/images/home-page-lower-preview.png)

The features beneath the carousel clearly explain the what the game is to an unfamiliar new user and why the game needs to be remastered. The timeline to the side helps the users place the game in reference to the Star Wars movies. I would have liked to adjust the timeline and make it look a bit nicer and add more event markers but I ultimately ran out of time to make this happen.

![Alignment Question/Footer Preview](/images/footer-preview.png)

The alignment question and it's functionality work as intended and fit the theme of the game and site very well and promote user engagement. If I had more time, I would have like to link the site to a database where I could store user responses and show graphics showing what other users voted.

The footer is clean and minimal. I would have liked to add more content here or be a bit more creative with this section.

### Characters/Planets Page

![Character Page Preview](/images/characters-page-preview.png)

The lightsaber divider and theme for the characters and planets pages work well and I am happy I was able to create the effect I wanted. It also wraps on mobile very well and looks very well in my opinion.

![Mobile Character Page Preview](/images/characters-page-preview-mobile.png)

If I had more time I would have like to add more features of different characters and planets.

### Petition Page

![Petition Page Preview](/images/petition-page-preview.png)

The petition form is clean, functional, funny and most importantly short which fulfils all the requirements I had for it. Given more time I would have liked to add a few images either side of the form  to decorate the page a bit more. Overall though I am happy with it.



## Deployment

This site was developed using the Atom text editor in conjunction with a package called *live-server* which creates a locally hosted server to preview pages during development. *Git* was used for version control and *GitHub* was used as a repository for the project.

The project was deployed was deployed on [GitHub Pages](https://pages.github.com/) using the following steps:

1. Log in to GitHub using your own credentials
2. Navigate to your repositories
3. Navigate to the repository containing your project
4. In the repository click on the *Settings* tab
5. Scroll down the *Settings* page until you find the *GitHub Pages* section
6. Under the *Source* tab, select which branch of your project you would like to deploy to *GitHub Pages*
7. Click *Save* to confirm and your site will be deployed at the link specified

## Running this Project Locally

To clone this repository to run locally or edit yourself using *Atom*

1. Open this repository
2. Click on the *Code* tab at the top of the repository
3. In the pop-up window click the *HTTPS* tab and copy the url presented in the window
4. Open *Atom* and hold down the *Ctrl, Shift + P* buttons at once
5. Type in *clone*
6. Click on the *GitHub: Clone* option
7. In the *Copy From:* field in the window that opens, paste the url you copied from *GitHub*
8. Choose the directory you wish the clone to be stored on your machine
9. Edit, change, create to your hearts content!

Alternatively if using a different IDE or text-editor, use the following *Git* command to clone the repository

```git clone https://github.com/Summersby95/ci-milestone-one.git```


## Credits

##### Images used on this site

* Transparent Character Models - [Star Wars Galaxy of Heroes Wiki](https://wiki.swgoh.help/wiki/Main_Page)
* More Transparent Planet/Character Models - [Star Wars Fandom Site](https://starwars.fandom.com/wiki/Main_Page)
* Game Screenshots - [GameFront](https://www.gamefront.com/)
* Lightsaber Divider Images - Ciaran Wheeler Dempsey *(Friend :))*


##### Content

* [W3 Schools](https://www.w3schools.com/default.asp) helped a lot with understanding a lot of CSS tricks and techniques I hadn't used before. Their articles on [CSS Animations](https://www.w3schools.com/css/css3_animations.asp), [How To - Parallax Scrolling](https://www.w3schools.com/howto/howto_css_parallax.asp) and [How To - Timeline](https://www.w3schools.com/HOWTO/howto_css_timeline.asp) were immensely helpful. Also their [ARIA in HTML](https://www.w3.org/TR/html-aria/) article was very helpful in ensuring my site met accessibility requirements.

##### Acknowledgements

* My mentor [Caleb Mbakwe](https://github.com/caleboau2012) whose constant help and guidance was key to getting this project over the finish line
* My friends Ciaran, Nestor and Pawel for throwing ideas at me... a few of them stuck ;)
* My work manager, Stephen Boylan, for throwing design suggestions and feedback at me, even when I didn't want to hear it, and most importantly, for allowing me to work on this on while at work ;)
* [Byllsa](https://github.com/byIlsa) for her awesome README which helped guide this document.

**Site For Educational Purposes Only**
