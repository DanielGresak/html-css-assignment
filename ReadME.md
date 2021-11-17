# Skydiving Website.
*Daniel Gresak - v1.0*

---
### Background.

I decided to do my project on my hobby of skydiving. I felt like this would be
the most interesting. I have a passion for it and would motivate me to make a site good enough to show off.
I would also like to include the back-end in the future so the site can be hosted if I wanted.

On top of the HTML and CSS I learnt in class, I also have completed the Full Stack
Web Development Bootcamp by The App Brewery (by Angela Yu). So any code we haven't covered that I included without
references would have been from the knowledge I gained in this course ([The App Brewery](https://www.appbrewery.co/)).

---
### Elements Included.

1. - External Link - The external link is situated on the homepage in the second last paragraph *(text is "skydive")(Line 65 index.html)*.

  - The internal links are provided in the nav bar *(line 22  index.html)*.


2. Navigation bar - The navigation bar is situated on each page *(line 22 index.html)*.

3. Table - The table is located in the in the Disciplines page *(line 32)*.

4. My unordered list is situated on the index.html page *(line 38)*.

5. I have embedded two videos from YouTube. The one I created before is situated on the index.html page (line 51) and another one is located in the tunnel.html page *(line 56)*.

6. - HTML5 Specific Elements.
    - section tag *(eg: line 30 index.html)*.
    - header tag *(e.g line 17 index.html)*.
    - footer tag *(e.g line 90 index.html)*.
    - details/summary tag *(line 36/37 index.html)*.
    - mark tag *(e.g line 77 disciplines.html)*.
  - CSS3.
    - border radius *(e.g line 12 styles.css)*.
    - Flex *(e.g line 235 styles.css)*.
    - transition duration *(e.g line 89 styles.css)*.
    - opacity *(line 229, styles.css)*.
    - transform *(line 218, styles.css)*.


7. I used a few css positional properties. Some examples of this is float *(line 154 and 160 in styles.css)*. Position absolute *(line 31 styles.css)* and relative *(line 22 and 80 styles.css)*.

8. - Block Elements - I used divs/sections/footers as block elements to make sure the previous floating elements didn't interfere with new sections. This was done in the travel.html page *(lines 30, 90)*. I also changed the tunnel video to block so that it would stay on its own at the bottom of the screen *(line 175 styles.css)*
  -Inline Elements -  I used inline elements to position elements on the same line as others. For instance I changed the text in the main header to inline in the css file *(line 33)*.
  - Flex Elements - I used flex elements  to create the gallery page to position the rows *(235 styles.css)*.

---
### Extras.

#### Expanding Images.
*Line 250 - styles.css*

I wanted to create a more reactive gallery page and give users the opportunity to view the images better. I googled this and found an excellent article on W3Schools on how to expand images on hover. I really enjoyed playing around with the transform timeframe and image scale to make the website feel more professional. I also used the z-position tool to make sure the expanded image was viewed above the other images.
~~~
.gallery-image {
  transition: .5s;
}

.gallery-image:hover {
  transform: scale(1.8);
  /* To make sure it displays over the other images on smaller screens */
  z-index: 2;
}
~~~

#### Website Responsiveness.
*Line 295 - styles.css*

I wanted to make sure that my website could look good on smaller as well as larger screens. I did this through using @media css rule to change the size of elements when viewed on a smaller screen. I realized halfway through the project that I was viewing the website on a particularly large screen so I made the first rule fairly big so the images would be resized for laptop screens. I used Chrome developer tools to format the sizes for phones.
~~~
@media only screen and (max-width: 1400px){
  .body-image {
    max-width: 300px;
  }
}
~~~

#### Email and Social Media Links.
*Line 198 - styles.css*

I decided that it would be nice to include contact information in the website. This included a link to bring up their mail client to email myself. I also
included my GitHub and LinkedIn profile as I feel that would fit nicely with the site. I learnt this during the previous online course I did
but also looked up how to add a mailto link to remind myself. I got the LinkedIn logo from [flaticon.com](https://www.flaticon.com/) and the GitHub logo from the official GitHub website. I
also made it into an unordered list and used the flex display to align it neatly with each other.

~~~
<a class="body-text button" href="mailto:daniel.gresak@ucdconnect.ie">Email Me!</a>
~~~


#### Favicon.
*line 12 - index.html*

I thought it would be a nice finishing touch to include a favicon in the title. I found a perfect one online
at [flaticon.com](https://www.flaticon.com/). I included the reference for this on the index.html page(line 14) and included the favicon on all of my 5 pages. I also added an online font that I found on google so if the page is opened without internet access it will load with the default font.
