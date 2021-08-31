# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
I followed a desktop first approach since the design for mobile and desktop are pretty similar. To center the card I used flexbox at first but then switched to using grid and the place-items property; that's because with flexbox it centered the card horizontally but not vertically, I hoped using grid would solve that problem but it didn't. The circles on the background were set using the transform: translate() property. Again, I had a problem keeping the circles in their location in all screens. Before using the transform property I used the position property. I read about both of them in a website I linked above, while I understood how they're used I'm still having trouble making the website look the same on all screen sizes, and the location of the card and the circles keep changing when I close and reopen the browser. To test the website I used Firefox, Edge, and Chrome. I found that Chrome was the least accurate, sometimes I would change the something in the code like the margin, and it wouldn't show until I closed the browser and reopened it. In the end I stuck with Edge. I used vh and vw units in hope of getting a more accurate positioning but it still didn't work. I had trouble displaying the svg as a background in the card but after using position: absolute; and setting the width to 100%, it worked. Before that I went to read more on svg on the mdn docs, while they didn't help with this challenge it was still an interesting read that gave me a good understanding on inline svgs and the tags and other details that are usually overwhelming.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### Continued development
I need to improve on positioning items and I need to read more on viewport units.


### Useful resources

- (https://www.sitepoint.com/atoz-css-translate-vs-position/) - Explains the difference between using the position property and the translate() property for positioning elements
- (https://developer.mozilla.org/en-US/docs/Web/SVG/Tutorial) - The mdn docs give a detailed explanation of svgs and how they work

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)