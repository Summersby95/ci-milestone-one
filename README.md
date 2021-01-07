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


## Technologies Used
---

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
