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

## **New Territory**

Web development just got a little more interesting for me… or so it seems that way. I have always been somewhat intrigued by front-end development, but haven’t really gotten the chance to actually learn it until now. With the help of this class, I was able to find out for sure. As someone who has had no prior web development experience, I wasn’t really sure what to expect. At first, learning the basics of coding with raw _Hypertext Markup Language_ (HTML) and _Cascading Style Sheets_ (CSS) to make webpages was definitely a brutal and tedious process. It made me question my abilities of designing a decent-looking layout and understanding how [<span style='font-family: monospace; color: ##87B2F3;'>**div**</span> **elements**](https://www.w3schools.com/tags/tag_div.ASP#:~:text=Definition%20and%20Usage,the%20class%20or%20id%20attribute.) worked. It also caused doubt on whether this was something I was actually interested in. However, at once, the practice of using a _user-interface_ (UI) framework to develop and recreate web pages from professional-looking websites has further piqued my interest in front-end work.

A web UI framework is a collection of design elements and components that are pre-built within as a default. These types of frameworks provide sets of CSS classes to elements in order to create a cleaner style in organizing web pages. From my experience so far, I have found these to be challenging and confusing at first, but rewarding and fulfilling long term. I noticed that UI frameworks can simplify the development process in trying to lay out all the components as desired. It can also provide a more aesthetically-pleasing look to the webpage. Most importantly, however, there is more consistency in the design over several browsers and across the different screen sizes of tech devices.

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

Adding on, the main caveat to all of these choices is that the options you choose are dependent on the entity that needs to be aligned, as well as the size of the space that you are working with. There were times when using the align-items-center class did not vertically center the elements that I wanted mainly because the space of the row or container was not set to my desired height. I also thought that the difference between align-items and justify-content were troubling to distinguish between horizontal and vertical alignment. Using mx-auto and my-auto to center different forms of content, like images and text, didn’t seem to help with centering as well. Even though this was the case, however, I further realized that these classes only apply to the container’s position relative to the web page- not to the content within the container itself. In order to center the content, I would have to use other text alignment classes, like text-center. Furthermore, learning about flex-box utilities such as d-flex and flex-column added on to the mounting heap of aspects that I didn’t understand when it came down to fixing the positioning of such elements.

## **Reaching a Turning Point**
Although it seems like I’ve only had troubling issues and setbacks with Bootstrap, there are some positive takeaways that I can see today.

### Responsiveness
One of the main things that I first noticed is that elements would seamlessly adjust with the same relative scaling and positioning of the size of the screen. An example of this aspect can involve menu tabs in a navigation bar that merge into a dropdown menu when the size of the screen is shrinked or below a certain threshold of pixel width. I found this to be really neat and beneficial with web design because the main “theme” of the design can be reused across several platforms. The feature is very simple implementation-wise because unlike raw HTML and CSS, we don't need any additional code to consider the possible conditions of screen size. Thus, the responsive component that is functionally embedded within web UI frameworks like Bootstrap allowed me to appreciate the software more.

### The Upside of the Learning Curve
As I started to get more familiar with Bootstrap, I realized that it is helpful in learning the basic foundation of how a designed layout works. One of the layouts that I found to be valuable is the grid system (LINK) implementation. Learning about the grid structure allowed me to visualize different rows of elements because I was able to know the size of the containers. Resizing the height of these rows accordingly enabled me to fix other issues relating to text alignment on a web page. Within each row div, I was able to understand how the length and width of a certain number of columns can affect the spacing of any element. The grid layout also helped me to think more about designing content evenly through separate divisions (divs), so that elements can be more visually appealing and cohesive with one another.

There are also many new elements that I have been able to style more simply with Bootstrap, as opposed to only CSS. Some of the components that I found to be useful include the buttons, navigation bar tabs, dropdown menus, and icons. The defaults for each of these components also come with different sets of customization options, such as changing colors or element sizes, which makes the intended effect much more easier to implement. The overall look and feel of the website can also match the designed layouts found on professional websites. As an example, here is an attempt to recreate Hana Tea’s (LINK) website. The left side of the image shows the original, while the right shows my recreation with Bootstrap.
Include image of hanatea recreation w/ Bootstrap
Aside from the slight differences in font and spacing, the web pages look pretty similar. In general, by using Bootstrap, I would say that you can get an almost identical layout design that is found on other clean-looking websites. Thus, the initial investment has resulted in positive long term results for learning more about formatting components and web development.

Upon further Inspection, Inspection, Inspection…
In addition to the grid system on Bootstrap, inspecting the elements via Chrome Developer Tools assisted in my comprehension for how containers worked. Viewing the Styles and Computed sections of the elements specifically allowed me to see the font families and font sizes used for a particular website. With Chrome Developer Tools, I was able to look at the margin and padding surrounding the content in each element. This enabled me to make quick adjustments when necessary. It also made me better grasp the concept of having every single component placed in its own box or container. As a result, element inspection facilitated my “debugging” process in terms of fixing the spacing between such elements. I could break down each individual aspect of a nested tag to fix the spacing accordingly, which allowed me to understand which Bootstrap classes to use for a specific HTML tag. I was also able to learn other techniques of formatting, such as overlapping images with text or creating a “tinted” background image via an overlayed mask of black transparent color.
Possible pic

Comparison bootstrap vs raw html and css styling
I would definitely prefer to use Bootstrap over raw HTML and CSS styling because adjusting and customizing such styles is much easier to implement. Other reasons for my preference are indicated and mentioned above. The following images show a set example of producing similar web pages with just raw CSS and with Bootstrap.  
Pic of browser history and css comparison
A much more complicated stylesheet is needed to produce the same design when using raw HTML and CSS compared Bootstrap. This is because the style aspects of Bootstrap are initiated in the classes of the divs of the HTML file.

On to the next step in the level?
I don’t feel as comfortable as I would like with Bootstrap to advance to the next step of implementing a fully functional website.  With this being said, I still look forward to learning about other aspects of front-end development. This includes working with open-source JavaScript libraries, such as React (link), which allow the components of the website to be more interactive. Using active links, buttons, and input forms to redirect to other sites and collect certain user information is something that can continue to enhance my skill set of tools in my software engineering journey. It would definitely be engaging and interesting to see how these both Bootstrap 5 and React work hand-in-hand to produce a cohesive webpage overall.

Understanding the components to UI design and learning how to perform it well is an important skill mainly because UI associates with the concept of User-Experience (UX). The main difference is that UI focuses on design, while UX focuses more on the overarching product via functional components. However, both aspects are needed to create a fully-operative website that is compelling, cohesive and effective in fulfilling a user’s needs or solving a problem. This is ultimately the next step towards covering the main basics of front-end web development.

Still A Long Way to go:
As with anything, a lot of practice is needed to 1) develop more familiarity and 2) refine your expertise in a specific area. While there is still much more that I can learn in designing elements on webpages with a framework like Bootstrap 5, I feel like utilizing it is a step in the right direction to designs that are of high-quality. Perhaps using UI frameworks can not only improve designs, but can also enhance work flows for front-end development. This is beneficial in software engineering as a whole because teams can work more efficiently in the design process for projects. Similar to coding standards, UI frameworks provide consistent results, which allows teams to work effectively and in unity. The final version of the product or project will therefore look more polished and refined just from this consistency. However, this is merely my opinion from my experience…So what do you say? Buckle up to level up with Bootstrap 5!

If you wanted to learn how to swim for the first time, how would you go about doing so? If you had to choose between learning from a swim instructor or learning by jumping right into the water, which one would you pick? One has a certain structure to help you build up the basics, while the other lets you figure out the basics randomly through experience. In the second option, you ultimately get to decide what basics you want to stick to, or rather, the dynamic fluidity of the “rules” you conform can influence your skill level as a swimmer. If you chose the latter and have had coding experience before, then JavaScript (JS) might be the coding language for you. For beginners that have a passion for programming with little to no programming experience, JS may or may not be the best option, depending on your viewpoint. Personally, I view JS as Java’s better older brother because just like an older brother, JS just seems to make everything look easy, or if anything, _easier_. Although I just started learning how to code in JS, I am enjoying my journey with it so far, possibly making it my new favorite language. 

Before the semester even started, all I knew about JS was that it was used for web development. I was nervous about learning the new syntax and rules at first, only to later find that there aren’t many rules at all. As a whole, I find its lack of limitations to be very liberating and user-friendly compared to other languages such as Java, C, or even Python.


## Functions are priority: They are _first class_

<img width="210px"  class="rounded float-start pe-4" src="../img/technical-essays/JS-1/Function_objects.png">

After exploring a little bit in JS, I realized that a majority of its dynamic flexibility revolves around its implementation with functions. In JS, functions are first-class. This means that functions are treated just like any other object or variable. You can assign a variable to a function, or even a function to another function. Functions can be parameters for a function or act as return values within another function. The collection of these functions can therefore produce hierarchical data structures that are very organic or fluid in nature. Unlike other languages, such as Java, JS allows functions to be generated dynamically at run-time, which can prevent the occurrence of spending a significant amount of time time looking for such tedious bugs in larger-scale projects. The possibilities when working with functions are quite literally… endless. 


## Syntax and Technicalities Seem Innovative

Some interesting aspects that I found to be effective are some of the syntax and keywords integrated in JS. These components allowed me to write simpler lines of code and made small programming assignments effortless. Staying on the topic of functions, I learned about the short-hand notation syntax for writing functions. From ES6, using the arrow markers (**=>**) can be used to connect the function header with the function’s body of code in a much simpler manner. This was beneficial, especially for functions that were more straightforward, since a function can be defined by just one line of code, as seen in the example below. In comparison to writing functions in Java, which involves writing a function header and body via multiple lines of code, I found the shortcut to be quite refreshing at first glance. 

<p align="center">
<img width="700px"  src="../img/technical-essays/JS-1/Arrow_operator2.png">
</p>

In addition to simple syntax, I was intrigued by the keywords and technicalities in JS. An example of this was the <span style='color: purple;'>**let**</span> keyword. This is similar to declaring any type of variable in Java in that the variable is scope-based and unique to the name that it’s given. However, the main difference that I found is that there is flexibility in changing or converting data types of a variable. Unlike Java, you don’t have to declare a variable’s specific data type, thus making reassignment of variables in JS much more convenient. This applies to other instances as well, such as objects and data structures, where a single array can contain a combination of integers, strings, other arrays, or any other type. 

Due to the flexibility of automatic data type conversion in JS, chunks of code can be free from errors during compile time. While experimenting with the language, I found that a practical benefit of this case is from the comparison of two types in conditional statements. The comparison operator "<span style='color: red;'>**==**</span>” in JS can allow two different data types to be checked. For instance, the **string** <span style='color: green;'>**"8"**</span> and the **integer** **8** will result in true when its corresponding comparison "<span style='color: red;'>**==**</span>” is used. In contrast to Java, using "<span style='color: red;'>**==**</span>” requires the same data type to be compared, which is similar to the strictly equal comparison operator "<span style='color: red;'>**===**</span>” for JS. 


## Standardized ES6 with JavaScript: More Shortcuts

There were a couple of ES6 syntax shortcuts that I thought were noteworthy. The first included the **for…of** syntax used in iteration loops, which iterates over repeatable objects. The syntax was a bit tricky at first, but I later found it to be a helpful shortcut in accessing the elements of any object, like arrays. Furthermore, the spreads operator (**...**) was another shortcut that I found to be insightful because accessing an element from an object, or expanding upon a previously established one, seemed much more effortless. In general, I’m still uncomfortable with utilizing the ES6 syntax, but I hope to get more use out of it as I continue to work with JS overtime.

## Possible Drawbacks?

As with everything in life, there are some disadvantages that can act as stumbling blocks when working with JS. As a novice programmer who is trying to re-sharpen their coding skills through this course, some of the advantages in JS did lead to confusion and misunderstanding. There were several times where I struggled understanding the syntaxial shortcuts dealing with functions and for loops, which caused lots of issues with debugging. Since I was already used to coding in Java previously, adjusting my mindset to not having to worry about data types for variables was also quite a challenge, making it time-consuming to just understand small snippets of sample code. With enough practice and familiarity, however, I believe that some of these disadvantages are inconsequential towards the positive upside of JavaScript’s features in the long run. 


## Approaching Software Engineering "Athletically"

Developing your software engineering from an “athletic” perspective involves the consistency of attempting practice activities called “workouts-of-the-day,” or WODs. I find this strategy to be both challenging, yet rewarding in a couple of ways. One of the main benefits that I get from practicing WODs includes the “hands-on” technique of solving coding problems. By doing so, I’m not only able to critically think about solving the problem itself, but I’m also becoming more familiar with JS and its syntax.

<img width="505px" class="rounded float-start pe-4" src="../img/technical-essays/JS-1/athletic_se1.png">

Similar to any workout, intensity and duration play important factors towards positive progress and reliable outcomes. The intensity of a practice WOD produces my motivation to focus, think quickly, and complete it successfully. I find the time pressure of completing the WOD to be beneficial as well. I think that the stress created from the time limit allows me to use my resources effectively and helps me to get a better sense of time management when working through the problem. 

Adding on to this, the aspect of reiteration from the practice WOD forces to me learn in an effective way. From this, I’m able to produce two main benefits. The first is to experiment with different methods in solving the problem. Attempting the problem multiple times allows me to find other solutions that could possibly be more efficient and save time coding. Improving this aspect will enhance my coding and logic comprehension. Instead of memorizing the same solution via “muscle memory,” I can be more comfortable with the parameters surrounding a specific type of problem and become more aware of its corresponding “simpler” solutions, so that I can save time coding on the actual WOD. The second luxury of constant repetition relies on the habitual nature to practice a WOD everyday, which I believe is a good habit to create and maintain throughout my potential career in tech. Hence, the approach to train in this format contains adequate and essential foundations of consistency and sustainability.


## Overall Thoughts

To sum it up, using JavaScript (JS) as another tool in your software engineering arsenal can be beneficial. Factors that play into maximizing the dynamic benefits of JS and effectively putting it into use will depend on one’s own motivational intentions and habitual practices for it. Though my feelings toward JS might change later on in my software development journey, I seem to be enjoying it as of right now. In consideration with one’s own coding skills and experience, as well as the type of project that one is pursuing, I would say that JavaScript is overall a user-friendly language for web development. However, it is not for everyone. So why not “dive in the waters” and give it a try? 
