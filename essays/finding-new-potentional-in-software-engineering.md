---
layout: essay
type: essay
title: "Finding New Potential in Software Engineering "
# All dates must be YYYY-MM-DD format!
date: 2023-12-12
published: true
labels:
  - Software Engineering
  - Configuration Management
  - UI Frameworks
  - Bootstrap 5
  - React
  - GitHub / Git
---


*My personal experience of learning software engineering fundamentals through ICS 314*

<p align="center">
    <img width="1000px" class="img-fluid" src="../img/technical-essays/finding-potentional-in-swe/swe-stack.jpeg" alt="">
</p>

<br>

## Compiling & Developing the Toolkit

There is a common saying that all great things come from small beginnings.  This is something that I have always considered and believed in. It is true that not everyone becomes an expert overnight, and while pure talent may beat out hard work, it is eventually the slow growth of knowledge and skills that shapes an expert into a master of their own craft overtime. The repetitive cycle of practicing, failing, learning, and redoing ultimately help us to advance in our “expertise status” through small baby steps, one step at a time. It is these combinations of elements that help us to define and refine our skills in our set of tools. Like an artist eagerly painting their canvas or a farmer fervently planting their crops, the right tools need to be utilized correctly and consistently resharpened to perform their desires, in which eventually, their progress will reveal their masterpiece and reap their harvest. In other words, though developing a true skill takes time, everyone has their own starting point and must start from somewhere….

<img width="420px"  class="rounded float-start pe-4" src="../img/technical-essays/finding-potentional-in-swe/swe-concepts.png" alt=""> 


Which is why at the start of this Fall 2023 semester, I wasn’t really sure what software engineering was. I also didn’t really know what to expect, as I haven’t really been able to work on meaningful software-related projects that can enhance or showcase my skills. And so… ICS 314 was that first stepping stone in both my academic and software engineering journey. Though I’m not certain of what the future promises, I can firmly say that it is a step in the right direction of my goal to work in software development.


During my experience in ICS 314, I have learned many new practices to help improve my abilities in web development. This not only includes the technical skills, but also the soft skills that can really play a part in team settings and work environments for positions in the computer science field. One of my biggest takeaways from this class is that the ability to work with a group on a common goal or project is a highly-valued skill, as you can better understand fundamental software principles from the help of peers and practice applying your knowledge into something tangible (aka. learning by doing!). Learning about software engineering conventions for the first time was a steep but necessary learning curve in forming basic technical capabilities. In general, however, I feel like I have gained a stronger understanding of some of the core concepts that software engineering entails. These include the following main areas:

<br>
<br>

## **Configuration Management (CM)**

<img width="420px"  class="rounded float-start pe-4" src="../img/technical-essays/finding-potentional-in-swe/devops.png" alt=""> 

In the realm of software development, configuration management (CM) is a process that consistently manages the states and progress of projects. Having a good system to keep track of a project or product’s performance can definitely help maintain the organization and quality of the development process as a whole. Managing the layout or design of a system is also important in the aspect of trial testing and deploying the product. It helps make the design and organization process more effective because having effective CM can allow possible errors to easily be identified along the way. This speeds up the operations of planning and finding alternate solutions to these found problems. The approach to configuration management attempts to solve 3 conceptual problems that often occur when working on software projects:

* <span style='color: #E685B5;'>**Double maintenance problem**</span> : This occurs when different copies of the same file need to be separately updated, which wastes both time and effort. CM prevents this from happening by allowing updates to all respective versions/copies of a file. 
* <span style='color: #E685B5;'>**Shared data problem**</span> : This occurs when only one person can access a file at a time. CM allows for multiple users to have access for better collaboration. 
* <span style='color: #E685B5;'>**Simultaneous update problem**</span> : This occurs when multiple people update a file at the same time, in which only one of the person’s changes gets taken into effect. CM tries to prevent this “clobbering,” so that updates from both parties are considered accordingly.

In addition, CM also relates to version control and defect tracking systems. Version control, which is the idea of keeping multiple versions of a certain software system, is necessary for revising and updating certain components of a project. Defect tracking systems help monitor the progressional status in the process, checking for any unwanted errors or changes to a specific version of a project. This is also a key component to CM because there is a cause-and-effect relationship between changes made to a system. Hence, the results of these changes might cause other unintended problems to occur, which then require more revisions in configuration.

<p align="center">
    <img width="400px" class="img-fluid" src="../img/technical-essays/finding-potentional-in-swe/github.png" alt="">
</p>

I was able to practice configuration management through a <a href="https://git-scm.com/book/en/v2/Distributed-Git-Distributed-Workflows" target="_blank">**distributed CM workflow**</a>. This system works on the basis of copying and exchanging a person’s version of a project. Users make copies of another person’s version of a project to make their own personal updates. They can then send those changes back to the original person. The overall model consists of a “push-and-pull” technique, where developers pull or fetch changes made by other developers and push their changes to a main repository for other developers to possibly fetch from. This is usually done from a centralized master “branch,” which can represent the final polished version of a project.


In my ICS 314 class, this was done through <a href="https://git-scm.com/" target="_blank">**Git**</a> (version control management system) and <a href="https://github.com/" target="_blank">**GitHub**</a>. I found the idea of holding all aspects of a project in a GitHub repository to be very effective for organizing all of its contents. More importantly, the practice of using branches on GitHub was a very interesting approach. Having different branches allowed me to easily compare the different versions of a project, which facilitated the process of making decisions for a specific design or functional component. Cloning and updating changes via pulling and pushing to the main branch also made it efficient in collaborating with other peers, since incremental consistent updates can slowly build the ultimate vision of the desired outcome.

One of the main things that helped me understand configuration management was the merging conflicts that occurred on GitHub. These merging conflicts usually occurred when multiple users edited the same line of the file while pushing their changes. Although it was very frustrating to have these conflicts at first, I was able to get more comfortable in fixing these issues. Due to the easy interface from GitHub Desktop, merge conflicts enabled me to recognize other possible implementation and design solutions that other peers had thought of. Therefore, I can see myself utilizing configuration management and using GitHub as a platform for future projects because it organizes the version history to maintain all of one’s progress. In the context of efficiency, being able to work on changes independently and locally are significant in making meaningful impact and advancements in the development process.

<br>
<br>

## **User Interface (UI) Frameworks**

In terms of web development, I have been able to improve my technical abilities in design through the concept of web frameworks. User-Interface (UI) frameworks are pre-built components or libraries that can help one design elements in a more aesthetic and efficient manner. Utilizing UI frameworks in product or project designs can overall make the display feel more professional and of higher quality. In addition to an attractive format, UI frameworks also simplify the development of coding the layout due to the approach of recycled material. UI frameworks allow developers to easily reuse components for creating interfaces. Since these elements are often intended to be implemented in a ready-to-use format, the default designs often contain a structure that is simple and neat. It also enables developers the freedom and flexibility to customize the basic makeup of a component to their intended theme, style or look. Furthermore, the benefit of UI frameworks also come with the purpose of creating a uniform theme and look throughout the project as a whole. This not only allows the project to feel cohesive in the layout throughout an application, but it also enables consistent results when being viewed across multiple browsers and varying media platforms or devices.

<div class="text-center p-4">
  <img width="300px" src="../img/technical-essays/finding-potentional-in-swe/bootstrap-2.png" class="img-thumbnail" >
  <img width="300px" src="../img/technical-essays/finding-potentional-in-swe/React.jpeg" class="img-thumbnail" >
</div>

Throughout the semester, I have been able to work with UI frameworks, such as <a href="https://getbootstrap.com/docs/5.3/getting-started/introduction/" target="_blank">**Bootstrap 5**</a> and <a href="https://react.dev/" target="_blank">**React**</a>, to efficiently design interfaces for web applications. I found Bootstrap and React to be very favorable frameworks due to the simplicity of their responsive designs. Simply put, I liked how these frameworks were <a href="https://www.browserstack.com/guide/how-to-implement-mobile-first-design" target="_blank">**mobile-first**</a>, which is the notion of automatically formatting designed elements to specific screen sizes without having to make any customizations. Due to React and Bootstrap’s mobile-first functionality, I could purely focus on the overall look of the layout of a web page without really having to consider how it would look differently on a tablet or phone.  Adding on to this, I found icons from Bootstrap 5 to be very useful in contingent with other navigation bar and other heading components. More importantly, however, I was able to use predefined React components to format elements in a more conventional and natural style. As someone who has never worked with web development before, taking advantage of these preset components allowed me to not have to worry about the frequent nesting and formatting of raw HTML tags and heavy CSS styling. Some of the React components that I found to be useful include the buttons and nav bar dropdowns/links for specific designs to forms and the nav bar header respectively. I also found React Bootstrap's grid system to be efficient in dividing the elements evenly within a specific space of the body. The usage of these tags and properties aided my skills in readjust spacing or aligning issues because I was able to learn differences between margins and padding of elements more effectively. It also made customization easier through different types of variant property fields.       

The following images show some examples of web pages that I helped to design using React and Bootstrap 5:

<div class="text-center p-4">
  <img width="650px" src="../img/technical-essays/finding-potentional-in-swe/ui-sustainer2.png" class="img-fluid" alt="">
    <img width="650px" src="../img/technical-essays/finding-potentional-in-swe/Recreation-pt1.png" class="img-fluid" alt="">
</div>



<div class="text-center pe-4" >

<i>Home page of Sustainer web app final project (left) and home page of Hana Tea website recreation (right) using UI frameworks
</i>

</div> 

<br>

I overall feel like a UI frameworks is a crucial aspect to creating clean designs in app interfaces. It creates both a consistent and simple look for a <a href="https://courses.ics.hawaii.edu/ics314f23/morea/ui-frameworks/reading-color-block.html" target="_blank">**colored block-style format**</a> or design pattern. I find this to be very applicable to future projects, specifically towards the front-end development procedures. Though I might not use the same frameworks in the future, I think that understanding how UI frameworks work can definitely assist in producing designs efficiently and portraying specific themes. On a broader, more conceptual level, user-interface frameworks speed up the development and decision-making process of design choices, since time won't be wasted on recoding layouts or elements to look a specific way based on screen size.

<br>
<br>

<img align="right"  class="rounded ps-4" width="300px"  src="../img/technical-essays/finding-potentional-in-swe/swe-background.png" alt="">

## Looking Towards the Future

In general, learning these foundational software engineering principles has allowed me to get a better perspective on what software development is all about. Taking ICS 314 has not only allowed to get an ideal taste of common practical procedures in a possible workplace setting for development, but it has also allowed me to unlock new interests in the different aspects of software engineering. From this, I have realized that there is much more grown potential through a variety of jobs in the rapidly growing field of computer science. I look forward to developing and refining my skill sets by taking the next step toward advanced software engineering concepts through ICS 414. I'm not too certain if I'll end up working in software development, but like an artist's and farmer's work, the journey towards the vision takes time. Even though time is a deciding factor, I've realized that appreciating the journey is part of this process ... _But truly in the end, only time will tell._

