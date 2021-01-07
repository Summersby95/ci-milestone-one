# Star Wars Knights of the Old Republic Petition Page

The goal of this project is to provide a __Call to Arms__ for a Star Wars game series, _Knights of the Old Republic_, a series developed in the early 2000's that was then cancelled.

Today, remasters of games are very common and there is a devote group of Star Wars game fans who are dying for the two _Knights of the Old Republic_ games to get a remaster. The goal of this project is to rally this _cult's_ support and provide a form where they can petition EA, the company who own the right's to the Star Wars game franchise, to develop a remaster.

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

### Wireframes

[Click here to view wireframes.](/wireframes/kotor_site_wireframes.pdf)

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

* Git
  * Used for version control and maintaining repository of project
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
  One of the effects used frequently throughout the site was the blue-to-yellow hover effect described above and inspired by the dialogue from the game. Initially, I created background colour classes which set the background colour, font colour and border colour for the elements it was assigned to. I then created hover classes for all these background colour classes which changed the colours to yellow. However, after testing and demoing to potential users, I found that when the yellow hover colourings took over they misled the users into thinking that the all elements were clickable and linked to something or performed an action. Users also reported that they found they effect distracting due to it's prevalence on the site. As such, I removed the hover classes from the background colour classes and created a seperate *yellow_hover* class to that would add the effect on elements that served a function, carousel controls, links etc.
* Lightsaber Dividers
  The Lightsaber dividers on the *Characters* and *Planets* pages required a lot of testing. For large and extra large screens I wanted the *light* (green) side and *dark* (red) side to appear side by side with the lightsaber divider down the middle, but on smaller sized screens I wanted the dark side to wrap beneath and the red half of the light saber to appear on the left side of the feature divs. I spent a lot of time initially trying to find two distinct lightsaber images that could fit my purpose. However, I needed the images to be vertically aligned, high resolution, green and red and, most importantly, have a transparent background that wouldn't look out of place or obscure the night sky background I was trying to achieve. Having tried several images as a potential prospect but to no avail, I was forced to ask a friend, skilled in photoshop to assist me in crafting the end result. Having found the right images it took a lot of testing of CSS rules to ensure the lightsabers behaved as intended on all screen sizes.
* Parallax Effect
  Very much like the Lightsaber dividers, I spent a while trying to source appropriate images to use as the background and foreground images to achieve the parallax effect. I was eventually able to find images that suited my needs however I struggled to achieve the desired effect. After searching I found a very useful [W3 Schools Article](https://www.w3schools.com/howto/howto_css_parallax.asp) which described how to achieve the effect I desired. After further adjustments to my DOM and testing I achieved the desired effect.
* Timeline
  One of the features that I thought would be quite useful to potential newcomers to the game was a timeline to help contextualize the game's time in reference to other Star Wars properties. Much like in the [Rosie Resume](https://summersby95.github.io/ucd-resume-ci/resume.html) mini project which proceeded this milestone project in the Full Stack Web Development course, I wanted to create the timeline using CSS after and before pseudo classes, as opposed to an image or other feature imposed on the screen. This [W3 Schools Article](https://www.w3schools.com/HOWTO/howto_css_timeline.asp) was also incredibly helpful. A lot of testing and adjusting was required on this element to prevent text spilling out of the timeline area and ensuring the timeline as a whole did not take up too much real estate on the home page.
