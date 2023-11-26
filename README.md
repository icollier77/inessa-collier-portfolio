<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<!-- INESSA: change to deployed application!!!! -->
  <a href="https://github.com/icollier77/inessa-collier-portfolio">
    <img src="./starter/images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">My Portfolio</h1>

  <p align="center">
    This is a webpage to host my portfolio of front-end web development projects to showcase my knowledge and skills for prospective employers and the dev community.
    <br />
    <br />
    <!-- CHANGE to the deployed app link -->
    <a href="https://icollier77.github.io/inessa-collier-portfolio/">Deployed application</a>
    ·
    <a href="https://github.com/icollier77/inessa-collier-portfolio">GitHub repo</a>
    <br>
    <br>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#mock-up">Mock-Up</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#wireframe">Wireframe</a></li>
        <li><a href="#colour-palette">Colour Palette</a></li>
          <ul>
            <li><a href="#main-colour-palette">Main colour palette</a></li>
            <li><a href="#accent-colours">Accent colours</a></li>
            <li><a href="#font-colourfont-colour">Font colour</a></li>
            <li><a href="#webpage-palette">Webpage palette</a></li>
          </ul>
        <li><a href="#images">Images</a></li>
          <ul>
            <li><a href="#photos">Photos</a></li>
            <li><a href="#icons">Icons</a></li>
          </ul>
      </ul>
    </li>
    <li><a href="#development">Development</a></li>
      <ul>
        <li><a href="#bootcamp-resources">Bootcamp Resources</a></li>
        <li><a href="#code-contributions">Code Contributions</a></li>
          <ul>
            <li><a href="#line-animation">Line Animation</a></li>
            <li><a href="#object-size-transformation">Object Size Transformation</a></li>
            <li><a href="#box-shadow">Box Shadow</a></li>
            <li><a href="#smooth-scrolling">Smooth Scrolling</a></li>
            <li><a href="#href-on-images">Href on Images</a></li>
          </ul>
      </ul>
    <li><a href="#project-takeaways">Project Takeaways</a></li>
    <li><a href="#deployed-project">Deployed Project</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## `About The Project`
The goal of this project is to build a webpage to show my portfolio of web development projects as I progress through the [Front-End Web Development Bootcamp][bootcamp-url].

<p>The critical requirements for this portfolio page:</p>
<ol>
  <li>When the page is loaded the page presents your name, a recent photo or avatar, and links to sections about you, your work, and how to contact you</li>
  <li>When one of the links in the navigation is clicked then the UI scrolls to the corresponding section</li>
  <li>When viewing the section about your work then the section contains titled images of your applications</li>
  <li>When presented with the your first application then that application's image should be larger in size than the others</li>
  <li>When images of the applications are clicked then the user is taken to that deployed application</li>
  <li>When the page is resized or viewed on various screens and devices then the layout is responsive and adapts to my viewport</li>
</ol>
</p>

### `Mock-up`
We were presented with a mockup of a portfolio page as an example:

![Mock-Up][mock-up-gif]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### `Built With`

I used the following technologies when building this portfolio page: 
* [HTML][html-url]
* [CSS][css-url]
* [JavaScript][js-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## `Getting Started`

<p>The project requires a wireframe to set the visual aspects of the planned portfolio page. This includes object shapes, locations, fonts, and the colour scheme.</p>
<p>The next step is to build an html file and the corresponding css file.</p>
<p>The last step is to adjust the css file for different device screens using media queries.</p>


### `Wireframe`

<p>As explained in the project brief, the portfolio is a one-page application and should contain:
<ul>
    <li>Header with my name</li>
    <li>Navigation links to the page sections</li>
    <li>An image divider for esthetics</li>
    <li>'About me' section that provides short overview of my background and skills.</li>
    <li>'My work' section that displays cards with my projects. The cards contain links to deployed applications.</li>
    <li>'Contact me' with links to the main contact methods (email, LinkedIn, GitHub).</li>
</ul>

I built the following wireframe using [Figma][figma-url]:

[![Portfolio Webpage Wireframe][wireframe-image]][wireframe-url]

### `Colour Palette`

I decided to utilize dark tones in my design to create a <b>professional</b> and <b>contemporary</b> portfolio page.

#### `Main colour palette`

To generate a color palette for the web page, I used the [Coloors][coloors-url] palette creation tool.

The main palette selected:

[![Main color palette][main-color-palette]][main-palette-url]

#### `Accent colours`

I also researched the web design colour trends for 2023 and 2024, and chose to use 2 accent colours mentioned in a blog post on Wix:

[7 website color trends that’ll be everywhere in 2024][wix-blog-url]

#### `Font Colour`

I used a [color contract checker][contrast-checker-url] to find the best font color, and selected white.

#### `Webpage palette`

As a result, I selected the <b>following colours</b> for the website:
<ul>
  <li>Main background colour: #0D0221</li>
  <li>Secondary background colour: #6688B0</li>
  <li>Main font colour: white</li>
  <li>Visited link: light grey</li>
  <li>Hover link: #C419BE</li>
  <li>Active link: #279DC0</li>
  <li>Highlight background colour: #C2E7D9</li>
  <li>Highlight font colour: #2628DD</li>
</ul>

These colours are set as <i>global variables</i> in the css file.

### `Images`

#### `Photos`

I sourced free photos from [Unsplash][unsplash-url], and used the following images in my design:
- [ ] [image for the Divider section][divider-img-url]
- [ ] [cover image for Project 1][project1-url] 
- [ ] [cover image for Project 2][project2-url]
- [ ] [cover image for Project 3][project3-url]
- [ ] [cover image for Project 4][project4-url]
- [ ] [cover image for Project 5][project5-url]

#### `Icons`

The navigation links at the top of the page and the links in the 'Contact me' section at the bottom of the page are set to be in text format when displayed on desktop. 
<br>
<br>
However, when displayed on mobile screens, I wanted those links to switch to icons as they would fit the available space better. 
<br>
<br>
Unfortunately, I was not able to find good free white icons for the navigation links.
<br>
<br>
I used the following free white icons for the 'Contact me' section:
* []() [Email icon][email-icon-url]
* []() [LinkedIn icon][linkedin-icon-url]
* []() [GitHub icon][github-icon-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- The build process -->
## `Development`

During the project development I faced several challenges as I wanted the page to have certain functionality but did not know how to do it.

### `Bootcamp resources`

In trying to find out how to do various aspects of the page (eg, _flex_ vs _grid_, etc), I found it very helpful to refer to the practice problems that we worked on during the Module 2 of the Front End Web Development bootcamp.
<br>
<br>
In particular, I found the <i>'Jakes Eatery'</i> and the <i>'Furniture Store'</i> problems very helpful, both for the design solutions and the code under the hood.
<br>
<br>
Finally, I want to mention the invaluable help I received from tutors in the bootcamp who helped me think about building the page by breaking it into smaller parts and going after them one by one, trying to find similar solutions in previous work or online.
<br>
<br>
Finally, my fellow students in the bootcamp, [Ben Rumbold][ben-rumbold-url] and [John Dick][john-dick-url] shared valuable insights in their approaches to the webpage design and functionality. These were helpful as I thought about my own portfolio page payout, the colour scheme, other design and coding aspects.


### `Code contributions`

However, in some cases, what I wanted to achieve went beyond what we discussed in the class or worked on in the practice problems. In those cases, I turned to the favourite tool of all programmers - Google.

#### `Line animation`

First of all, I wanted to have my motto <i>"Let's build something great!</i> move across the divider image. I did not know how to do this but after doing some research, I found advice and code in this [HubSpot article][hubspot-url]. 

#### `Object size transformation`

I wanted the cards in the 'Portfolio' section slightly increase in size when moused over. Again, some online research helped me remember how to do it. Namely, [this article][transformation-url] was very helpful.

#### `Box shadow`

I also wanted the project cards to have a dark shadow when moused over, adding to the highlight effect. I found a [great example][darkshadow-url] of dark shadow applied to white font and utilized in my my `box-shadow` property.

#### `Smooth scrolling`

In my intended design, the page should scroll _smoothly_ to the related section when one of the 'Navigation' links is clicked. An article from [Stackflow][smooth-scroll-url] was very helpful in solving this problem.

#### `Href on images`

One of the biggest challenges I faced was adding a weblink (`<a href>`) to images of projects. I placed the images in the css file as backgrounds to the corresponding `<div>` sections. Some advice online suggested that I would be able to wrap the `<div>` sections in `<a href>` however in practice, this did not work. 
<br>
<br>
Another solution would be to move all images into the HTML file but firstly, it would change the page design, and secondly, it would require many more hours of re-writing the code.
<br>
<br>
I knew that it should be possible to click on the images even if they are placed as backgrounds in the css file. After some research, I found suggestions that _JavaScript event listeners_ can offer a solution to this problem. These articles in particular offered some insights:
* []() [How can I add an event listener to an image inside JavaScript to make the image clickable?][quora-url]
* []() [How do I add a hyperlink to a background image?][stackoverflow-url]

However, the code suggested in these articles did not work for my project directly. I then used ChatGPT3.5 to ask clarifying questions and find the exact code that gave me the required solution. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- TAKEAWAYS -->
## `Project Takeaways`

It was an interesting project that challenged me to go over the **flex** and **grid** display in css numerous times. I realized the importance of changing the flex display to _column_ when resizing for mobile screens, both for the navigation links, and for the main section of the screen.
<br>
<br>
Overall, it is clear that the mobile design should be very different from the desktop design, and should be wireframed from the start as well.
<br>
<br>
I struggled with organizing my 'Portfolio' section, trying to arrange the cards using **flex** display. In the end, I realized that a much easier and much more functional approach would be to use a **grid**. Re-arranging components of a grid for a smaller screen is very easy and requires minimum code adjustments. 
<br>
<br>
A **grid** was also the best solution to make sure that one of the card is larger than the others. I initially used the `:nth-of-type(1)` selector but the overall **flex** display worked poorly for the design.
<br>
<br>
Finally, the **media queries**, although they may seem quite easy, can take a significant amount of time, mainly due to resizing fonts and margins. I think I still need to understand better when and how to utilize different units of size such as _em_, _rem_, _%_, _vh_, and _vw_ in order to reduce the number of adjustments for different screen sizes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Deployed project -->
## `Deployed project`

The project is now live. You can find the portfolio and the corresponding code here:

- [ ] [Inessa Collier portfolio][deployed-url]
- [ ] [Project repo][repo-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
[html-url]: https://www.w3schools.com/html/
[css-url]: https://www.w3schools.com/css/default.asp
[js-url]: https://www.w3schools.com/js/default.asp
[deployed-url]: https://icollier77.github.io/inessa-collier-portfolio/
[repo-url]: https://github.com/icollier77/inessa-collier-portfolio
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/inessacollier/
[mock-up-gif]: images/01-css-challenge-demo.gif
[wireframe-image]: starter/images/portfolio-wireframe.png
[wireframe-url]: https://www.figma.com/file/
[bootcamp-url]: https://www.edx.org/boot-camps/coding/skills-bootcamp-in-front-end-web-development
[figma-url]: https://figma.com
[coloors-url]: https://coolors.co/
[main-color-palette]: starter/images/main-palette.png
[main-palette-url]: https://coolors.co/0d0221-0f084b-26408b-a6cfd5-c2e7d9
[wix-blog-url]: https://www.wix.com/blog/website-color-trends?utm_source=google&utm_medium=cpc&utm_campaign=13774768257%5E126077909722&experiment_id=%5E%5E531699814064%5E%5E_DSA&gclid=Cj0KCQiA6vaqBhCbARIsACF9M6n3Fa1SVaeIERjT2uQGhIsFCQ9G3ysPLUtkUikSlxyY5i2wiIkVVOQaAttBEALw_wcB
[contrast-checker-url]: https://webaim.org/resources/contrastchecker/
[unsplash-url]: https://unsplash.com/ 
[divider-img-url]: https://unsplash.com/photos/purple-and-white-round-light-9bBLdOaRIB0
[project1-url]: https://unsplash.com/photos/black-flat-screen-computer-monitor-8qEB0fTe9Vw
[project2-url]: https://unsplash.com/photos/turned-on-monitor-displaying-function-digital_best_reviews-gnyA8vd3Otc
[project3-url]: https://unsplash.com/photos/turned-on-gray-laptop-computer-XJXWbfSo2f0
[project4-url]: https://unsplash.com/photos/macbook-pro-beside-white-ceramic-mug-on-brown-wooden-table-k-rKfqSm4L4
[project5-url]: https://unsplash.com/photos/apple-macbook-beside-computer-mouse-on-table-9l_326FISzk 
[email-icon-url]: https://www.iconsdb.com/white-icons/email-14-icon.html 
[linkedin-icon-url]:  https://www.iconsdb.com/white-icons/linkedin-4-icon.html
[github-icon-url]: https://www.iconsdb.com/white-icons/github-10-icon.html 
[hubspot-url]: https://blog.hubspot.com/website/scrolling-text-css 
[transformation-url]:  https://www.tutorialrepublic.com/faq/how-to-transform-image-size-on-mouse-hover-without-affecting-the-layout-in-css.php 
[darkshadow-url]: https://www.w3schools.com/css/css3_shadows.asp 
[smooth-scroll-url]:  https://stackoverflow.com/questions/7717527/smooth-scrolling-when-clicking-an-anchor-link 
[quora-url]: https://www.quora.com/How-can-I-add-an-event-listener-to-an-image-inside-JavaScript-to-make-the-image-clickable
[stackoverflow-url]: https://stackoverflow.com/questions/3778611/how-do-i-add-a-hyperlink-to-a-background-image
[ben-rumbold-url]: https://github.com/Ben-Rumbold
[john-dick-url]: https://github.com/johndck