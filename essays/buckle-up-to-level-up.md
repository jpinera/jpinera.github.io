---
layout: essay
type: essay
title: "Buckle Up to Level-Up!"
# All dates must be YYYY-MM-DD format!
date: 2023-10-05
published: true
labels:
  - Bootstrap 5
  - UI / UX Design
  - Web Development
  - Front-end Engineering
  - IntelliJ IDEA
---

<img class="rounded float-start pe-4" height="400px" src="../img/technical-essays/buckle-up-to-level-up/bootstrap-2.png" alt="logo">

## **New Territory**

Web development just got a little more interesting for me… or so it seems that way. I have always been somewhat intrigued by front-end development, but haven’t really gotten the chance to actually learn it until now. With the help of this class, I was able to find out for sure. As someone who has had no prior web development experience, I wasn’t really sure what to expect. At first, learning the basics of coding with raw _Hypertext Markup Language_ (HTML) and _Cascading Style Sheets_ (CSS) to make webpages was definitely a brutal and tedious process. It made me question my abilities of designing a decent-looking layout and understanding how <a href="https://www.w3schools.com/tags/tag_div.ASP#:~:text=Definition%20and%20Usage,the%20class%20or%20id%20attribute." target="_blank"><span style='font-family: monospace; color: ##87B2F3;'>**div**</span> **elements** </a> worked. It also caused doubt on whether this was something I was actually interested in. However, at once, the practice of using a _user-interface_ (UI) framework to develop and recreate web pages from professional-looking websites has further piqued my interest in front-end work.

A web UI framework is a collection of design elements and components that are pre-built within as a default. These types of frameworks provide sets of CSS classes to elements in order to create a cleaner style in organizing web pages. From my experience so far, I have found these to be challenging and confusing at first, but rewarding and fulfilling long term. I noticed that UI frameworks can simplify the development process in trying to lay out all the components as desired. It can also provide a more aesthetically-pleasing look to the webpage. Most importantly, however, there is more consistency in the design over several browsers and across the different screen sizes of tech devices.



<img width="370px" class="rounded float-start pe-4" src="../img/technical-essays/buckle-up-to-level-up/ui-design-1.jpeg" alt="ui-1"> 

## **Taking UI Design to the Next Level**

Over the past couple of weeks, I got to experience implementing a UI framework called <a href="https://getbootstrap.com/docs/5.3/getting-started/introduction/" target="_blank">**Bootstrap 5**</a>, which includes built-in CSS styles and _JavaScript_ (JS) components, to improve the design of websites. One of the main benefits for using Bootstrap is that it is centered around the idea of being “mobile-first.” This means that the default behavior for classes in Bootstrap revolves around formatting the display to the mobile environment. No customization or additional special code is required to redesign the intended UI and compensate for mobile-sized screens. Ultimately, the shift in a first-class mobile approach resolves the issue of coding the same application multiple times for the varying screen sizes and different operating systems between devices. Ultimately, the functionality embedded within UI frameworks like Bootstrap 5 is what makes it a highly versatile tool.

### Climbing the Mountain

Though I have not climbed any physical mountains in real life, I have experienced the process of scaling the steep learning curve several times throughout my academic career. This time was no different from the others.  The following discusses my first thoughts and reactions to using Bootstrap 5.

### Hours & Hours:

Initially, I wasn’t in favor of using Bootstrap. The amount of time that I initially invested into learning its documentation didn’t seem to be all that worthwhile. I was mainly overwhelmed by the number of different classes that were made in Bootstrap to customize components. Looking at all the variations of a class for a specific element was also challenging because I couldn’t differentiate the purposes of each class variation. As an example, here are a couple of class options that you can utilize in Bootstrap when designing a _navigation bar element_:

* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-nav**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-expand**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-brand**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-toggler**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-link**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-item**</span> 
* <span style='font-family: monospace; color: #E685B5;' target='_blank'>**.navbar-text**</span>  ... and much more.

All of these options made the styling of elements difficult to understand.

In addition to this, I realized that there were generally a lot more nested tags in my html file when working with the Bootstrap classes. The following shows a sample code of what this might look like in designing all elements of a full navigation bar at the top of a webpage.

```html
<div class="px-0 justify-content-center pb-2 bg-light">
  <div class="navbar">
    <div class="container">
      <ul class="nav justify-content-start">
        <a class="navbar-brand" href="#">
          <li class="nav-item">
            <i class="bi bi-instagram"></i>
          </li>
        </a>
      </ul>
      <ul class="nav justify-content-center">
        <li class="nav-item"><a class="navbar-brand" href="#">
          <img src="boardroom-logo.png" alt="logo" width="70px">
        </a></li>
      </ul>
      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="navbar-brand" href="#"><button type="button" class="btn btn-dark">Menu</button></a></li>
      </ul>
    </div>
  </div>
</div>
```

As you can see, there is a lot to take in. Attempting to comprehend each pairing of these nested tags was an insurmountable headache. It was also complicated to originally figure out which Bootstrap class to use for each html tag and which HTML tag to wrap in for a specific element.

The most troubling issue that I’ve encountered with Bootstrap so far is learning how to adjust the spacing and alignment of elements, containers, and text. I found that there are varying approaches to take when wanting to align a component in a specific way. The wide varying number of options to choose from is what made it difficult in learning how each class is used.

Adding on, the main caveat to all of these choices is that the options you choose are dependent on the entity that needs to be aligned, as well as the size of the space that you are working with. There were times when using the align-items-center class did not vertically center the elements that I wanted mainly because the space of the row or container was not set to my desired height. I also thought that the difference between **align-items** and **justify-content** were troubling to distinguish between horizontal and vertical alignment. Using mx-auto and my-auto to center different forms of content, like images and text, didn’t seem to help with centering as well. Even though this was the case, however, I further realized that these classes only apply to the container’s position relative to the web page- not to the content within the container itself. In order to center the content, I would have to use other text alignment classes, like text-center. Furthermore, learning about flex-box utilities such as **d-flex** and **flex-column** added on to the mounting heap of aspects that I didn’t understand when it came down to fixing the positioning of such elements.

## **Reaching a Turning Point**
Although it seems like I’ve only had troubling issues and setbacks with Bootstrap, there are some positive takeaways that I can see today.

### Responsiveness
One of the main things that I first noticed is that elements would seamlessly adjust with the same relative scaling and positioning of the size of the screen. An example of this aspect can involve menu tabs in a navigation bar that merge into a dropdown menu when the size of the screen is shrinked or below a certain threshold of pixel width. I found this to be really neat and beneficial with web design because the main “theme” of the design can be reused across several platforms. The feature is very simple implementation-wise because unlike raw HTML and CSS, we don't need any additional code to consider the possible conditions of screen size. Thus, the responsive component that is functionally embedded within web UI frameworks like Bootstrap allowed me to appreciate the software more.

### The Upside of the Learning Curve
As I started to get more familiar with Bootstrap, I realized that it is helpful in learning the basic foundation of how a designed layout works. One of the layouts that I found to be valuable is the <a href="https://getbootstrap.com/docs/5.3/layout/grid/" target="_blank">**grid system**</a> implementation. Learning about the grid structure allowed me to visualize different rows of elements because I was able to know the size of the containers. Resizing the height of these rows accordingly enabled me to fix other issues relating to text alignment on a web page. Within each row div, I was able to understand how the length and width of a certain number of columns can affect the spacing of any element. The grid layout also helped me to think more about designing content evenly through separate divisions (divs), so that elements can be more visually appealing and cohesive with one another.

There are also many new elements that I have been able to style more simply with Bootstrap, as opposed to only CSS. Some of the components that I found to be useful include the buttons, navigation bar tabs, dropdown menus, and icons. The defaults for each of these components also come with different sets of customization options, such as changing colors or element sizes, which makes the intended effect much  easier to implement. The overall look and feel of the website can also match the designed layouts found on professional websites. As an example, here is an attempt to recreate <a href="https://www.hanatea808.com/" target="_blank">**Hana Tea's**</a> website. The left side of the image shows the original, while the right shows my recreation with Bootstrap.

<div class="text-center" pe-4>
    <p><strong>ORIGINAL:</strong> &nbsp;  <strong>RECREATION:</strong> </p>      
</div> 

<div class="text-center p-4">
  <img width="400px" src="../img/technical-essays/buckle-up-to-level-up/HanaTea-Website-Real-pt1.png" class="img-thumbnail" >
  <img width="400px" src="../img/technical-essays/buckle-up-to-level-up/Recreation-pt1.png" class="img-thumbnail" >
</div>

Aside from the slight differences in font and spacing, the web pages look pretty similar. In general, by using Bootstrap, I would say that you can get an almost identical layout design that is found on other clean-looking websites. Thus, the initial investment has resulted in positive long term results for learning more about formatting components and web development.

### Upon further Inspection, Inspection, Inspection…

In addition to the grid system on Bootstrap, inspecting the elements via Chrome Developer Tools assisted in my comprehension for how containers worked. Viewing the Styles and Computed sections of the elements specifically allowed me to see the font families and font sizes used for a particular website. With Chrome Developer Tools, I was able to look at the margin and padding surrounding the content in each element. This enabled me to make quick adjustments when necessary. It also made me better grasp the concept of having every single component placed in its own box or container. As a result, element inspection facilitated my “debugging” process in terms of fixing the spacing between such elements. I could break down each individual aspect of a nested tag to fix the spacing accordingly, which allowed me to understand which Bootstrap classes to use for a specific HTML tag. I was also able to learn other techniques of formatting, such as overlapping images with text or creating a “tinted” background image via an overlayed mask of black transparent color.



**Possible pic**



## **Comparing Bootstrap vs Raw HTML & CSS**

<img width="300px" class="rounded float-start pe-4" src="../img/technical-essays/buckle-up-to-level-up/compare-bs-html-2.jpeg" alt="compare">

I would definitely prefer to use Bootstrap over raw HTML and CSS styling because adjusting and customizing such styles is much easier to implement. Other reasons for my preference are indicated and mentioned above. The following images show a set example of producing similar web pages with just raw CSS and with Bootstrap.  

**Pic of browser history and css comparison**

A much more complicated stylesheet is needed to produce the same design when using raw HTML and CSS compared Bootstrap. This is because the style aspects of Bootstrap are initiated in the classes of the divs of the HTML file.

## **On to the next step in the level?**

I don’t feel as comfortable as I would like with Bootstrap to advance to the next step of implementing a fully functional website.  With this being said, I still look forward to learning about other aspects of front-end development. This includes working with open-source JavaScript libraries, such as <a href="https://react.dev/" target="_blank">**React**</a>, which allows the components of the website to be more interactive. Using active links, buttons, and input forms to redirect to other sites and collect certain user information is something that can continue to enhance my skill set of tools in my software engineering journey. It would definitely be engaging and interesting to see how these both Bootstrap 5 and React work hand-in-hand to produce a cohesive webpage overall.

<p align="center">
<img width="350px" class="img-fluid" src="../img/technical-essays/buckle-up-to-level-up/React.jpeg" alt="react">  
&nbsp;       
&nbsp;
&nbsp;
<img width="400px" class="img-fluid" src="../img/technical-essays/buckle-up-to-level-up/ui-ux-design.png" alt="ui-ux">
</p>

Understanding the components to UI design and learning how to perform it well is an important skill mainly because UI associates with the concept of User-Experience (UX). The main difference is that UI focuses on design, while UX focuses more on the overarching product via functional components. However, both aspects are needed to create a fully-operative website that is compelling, cohesive and effective in fulfilling a user’s needs or solving a problem. This is ultimately the next step towards covering the main basics of front-end web development.



## **Still a Long Way to Go**

<img align="right" width="250px"  src="../img/technical-essays/buckle-up-to-level-up/ui-design-4.jpeg" alt="ui-4">

As with anything, a lot of practice is needed to 1) develop more familiarity and 2) refine your expertise in a specific area. While there is still much more that I can learn in designing elements on webpages with a framework like Bootstrap 5, I feel like utilizing it is a step in the right direction to designs that are of high-quality. Perhaps using UI frameworks can not only improve designs, but can also enhance work flows for front-end development. This is beneficial in software engineering as a whole because teams can work more efficiently in the design process for projects. Similar to coding standards, UI frameworks provide consistent results, which allows teams to work effectively and in unity. The final version of the product or project will therefore look more polished and refined just from this consistency. However, this is merely my opinion from my experience…So what do you say? **_Buckle up to level up with Bootstrap 5!_**



<p align="center">
<img width="700px"  src="../img/technical-essays/JS-1/Arrow_operator2.png">
</p>





