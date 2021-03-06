<head>
<meta name="google-site-verification" content="wcV7kpKbH6TmMH3tgjEqdGx65Zr3zuKgTi3F0ZeLzoE" />
</head>

7th Sea CCG plugin for OCTGN
============================

7th Sea finally sails into OCTGN. A card game about swashbuckling pirates, ruthless privateers and even undead horrors from Davy Jones' locker.

This is a repository for the a game definition for the [Online Card and Tabletop Gaming Network (OCTGN)](http://octgn.net).

* Automation Rank: **D** *(This game definition contains no automation.)*


Available Sets
---------

Currently 7th Sea does not utilize OCTGN auto-generated proxies to play. You'll need to download the card image packs to be able to play.

The link below will provide you with a download bundle you can import into OCTGN by the "add o8c" function in the game manager

* [7th Sea CCG Card Images Bundle](https://drive.google.com/file/d/1Pi_EV53rDqVBC5Vi6UaBFVQThBgmWsrQ/view?usp=sharing) *(Last Updated 01/10/2021)*

A lot of images in this bundle are built manually off of templates. In the future I hope I'll be adding proper high quality scans as they are procured and will provide a download link here.

Community
---------

Join our [7th Sea CCG discord server](https://discord.gg/Q9H78sb)

[7th Sea CCG Players Facebook Group](https://www.facebook.com/groups/2233394568/) 

and additional resources at [The 7th Sea CCG Fan Page](http://www.7thsea.info). 

[7th Sea Board Game Geek page](http://boardgamegeek.com/boardgame/3125/7th-sea-collectible-card-game) here.

Hopefully, with the game being playable on OCTGN, we might be able to rejuvenate the community and teach new people to play. So please **do** speak up if you're around ;)


# 7th Sea on OCTGN

7th Sea is a card game about swashbuckling pirates, ruthless privateers and even undead horrors from Davy Jones’ locker. A card game for 2-6 players

*7th Sea is a game of high seas swashbuckling and ship-to-ship combat. In 7th Sea, you are the captain of a ship fighting for control of the seas of Théah. Whether you want to board your opponents and fight with swords, blast them with your cannons, or simply ram them to the bottom of the sea, you will organize your crew and adventure across the seas until the time is right to strike.*

![7th Sea Logo](7thSea_logo2.jpg)

This is a game definition for the [Online Card and Tabletop Gaming Network (OCTGN)](http://octgn.net/).

This site is the repository of all things related to this game definition. Please check the header above for such things such as installation instructions, tutorials, and contributions information.

## Installation

1. Download & Install the OCTGN client from here (Windows only)
2. Open OCTGN and register an account or login with an existing one.
3. Go to the game manager tab and click the “Add” button. In the window that will open type:
 **Name:** OCTGN Directory
**Feed URL/Path:** https://www.myget.org/f/octgngamedirectory and press “Add”. A new feed should appear on the left.
4. Click on the “OCTGN Directory” Feed. On the right a list of games should appear.
5. Click on 7th Sea and click “Install”. After a short wait it should finish.
6. Go here and download all the card packs (.o8c) you find.
7. In OCTGN, go to game manager and click on “Add Image Packs”
8. Select the .o8c files you download them one by one and install them. You will see a install window and once each pack is installed, you’ll see a pop-up window confirming this. This should take a few seconds at most.
9. Done! You can now start a game with the included decks, or make your own in the deck editor

**(Recommended)** In case you’re a new player, [grab the rulebook from here](https://72097bb9-ee25-40ee-b5a8-363a17454f74.filesusr.com/ugd/51c7cb_2ef9693b499e4962a4adfb669ca809a8.pdf) (pdf).


## Contact
If you found a bug in the game definition and want to report it, or if you have a great idea for a new feature and want to see it implemented, please report it in the [github repository for 7th Sea on OCTGN](https://github.com/stevetotheizz0/7thSea-for-OCTGN). This is the best way for the developer to see and track issues reported and you’ll also be informed when they’re closed.

For additional support, join [OCGTN's Discord Server](OCTGN Community Chat & Support: https://discord.gg/Yn3Jrpj).

## For Developers

### How to install and run this game locally:

#### Step 1
Download .nupkg file from this repository

#### Step 2
Navigate to the Local Feed of your OCTGN. Usually this is located at C:\Users\ \Documents\OCTGN\LocalFeed

If you use different locations for OCTGN and its data, the 'LocalFeed' folder might be inside OCTGN\Data\LocalFeed

#### Step 3
Drop the .nupkg file you just downloaded into this folder and start OCTGN. Under the games manager select the developer local feed option from the drop down. (Also note that the local package will need to have a higher version number than the current to update) 

For testing changes, you will need to create another .nupkg file and drop it in the LocalFeed folder to run and test locally. OCTGN has a build process and build GUI included within its files and documented [here](https://github.com/octgn/OCTGN/wiki/O8build). The OCTGN discord channel can also provide additional support for developers. 

