# User Centric Frontend Development Milestone Project

A static website for a band (the Monkees) consisting of 5 different pages, a video of the band with a short description beside it, short descriptions of each member including links to the individual Wikipedia pages for the band members, a page with 4 different songs to listen to and/or download, a page for all upcoming events and a final page where users can get in contact with the band to discuss booking. The user will be able to reach any pages from anywhere as there are 4 links in the header (home, about us, media and upcoming events) and a link in the footer to reach the contact us page.

## UX
The website has an indicator of what page the user is currently on, this indicator is neither so large that it becomes distracting nor too small that it doesn't help the user know where they are. During development, I was also advised to shrink the size of the images and video so that they did not become the main focus of pages where other information was shown.

[Wireframes](https://imgur.com/a/HvqAaRb) - These are the initial wireframes I made before starting development on the website, as you can see the design of the website didn't change too much but I did have to make some small changes.

## Features

The webpage features a video that users can watch, 4 different songs that the user can listen to on the webpage itself or download for later use and a form that the user can fill out in order to contact the band.

If I had the required knowledge I'd have liked to include a calendar that would have shown when upcoming events were scheduled for, instead of having to rely on changing the text.

### Technologies Used
- [Bootstrap](https://getbootstrap.com/) - Bootstrap was used mainly for its ability to help in laying out webpages.
- [Font Awesome](https://fontawesome.com/) - Font Awesome (FA for short) was used for the icons that it includes as this help a lot with styling the webpage.
- [Hover.css](http://ianlunn.github.io/Hover/) - Hover.css was used just to help with styling, it provides a nice visual indicator to the user that they have moused over one of the navigation links.

## Testing
### All Page
- Ensure links to other pages work
- Ensure logo image disappears depending on screen size
### Main Page
- Ensure video works on both desktop and mobile screen
### About Us Page
- Amount of text should lessen depending on screen size
### Media Page
- Mp3 players and images should stack on top of each other instead of being side by side when page size shrinks
### Events Page
- Months should stack vertically instead of being side by side when on a smaller screen
### Contact Us Page
- Form should only allow a valid email address
- Form should require text in all three input boxes
## Deployment
The project is hosted on GitHub Pages using the master branch, as this is a small scale project I felt it wasn't necessary to have a separate branch that would be used for live deployment and a branch for development.

## Credits
The images and video on the main page and about us page, as well as the audio files for the media page were all provided by Code Institute in the GitHub Repo [Project Assets](https://github.com/Code-Institute-Org/project-assets)

The audio files on the media page were pulled from Google.

The text for the section of information on the main page was copied from the Wikipedia page for [The Monkees](https://en.wikipedia.org/wiki/The_Monkees) with the information on each band member being copied from their respective Wikipedia pages: [Peter Tork](https://en.wikipedia.org/wiki/Peter_Tork), [Micky Dolenz](https://en.wikipedia.org/wiki/Micky_Dolenz), [Michael Nesmith](https://en.wikipedia.org/wiki/Michael_Nesmith) and [Davy Jones](https://en.wikipedia.org/wiki/Davy_Jones_(musician)).
