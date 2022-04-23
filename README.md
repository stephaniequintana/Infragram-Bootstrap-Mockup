# Infragram Bootstrap Mock-up
The sole purpose of this code is to demonstrate how Bootstrap's powerful grid can be utilized for the re-design of the Infragram sandbox User Interface. It does not include titles, links or logos, but rather is meant to propose the Bootstrap grid layout that will allow for different mobile and desktop versions of the page. Please note **this is code is not a functioning representation of the Infragram processing tool and has included images along with minimal JavaScript code to  emulate how the code might appear in differing layouts.**

Bootstrap is full of incredible features that we are able to utilize to make our site exactly what we envision without the use of media queries. Here, I have employed the `order` property along with a multitude of `display` properties to effectively create different full-screen layouts for the mobile and desktop versions of the image processor and it's toolbox of features.

As Bootstrap 4 is designed, it is required that some of the code be duplicated (with differing display properties) to achieve the layouts without media queries. Another option, which would not result in duplicate code (but would require the use of media queries), would be to utilize the powerful, two-dimentional CSS Grid property. I believe this could be used within a Bootstrap container, but only in Bootstrap 5 and not in version 4.

Please see the html file for specifics.

![gif of the responsive design](assets/infragram.gif)

![Screen Shot 2022-04-22 at 5 54 22 PM](https://user-images.githubusercontent.com/81270711/164844048-e20dbfbf-7047-43ca-8f49-ea8011329e37.png)

![Screen Shot 2022-04-23 at 12 56 13 AM](https://user-images.githubusercontent.com/81270711/164881372-452de6f2-53c1-49e4-a6d5-796aaccf9bea.png)

<!--![mobile wireframe](assets/mobile.png)-->
<!--![desktop wireframe](assets/desktop.png)-->
---
## Buttons in rows vs columns on smaller screens
As above, with desktops being wider, it makes sense to have the toolbars in left/right columns. That type of design, though, significantly decreases the pixel real estate that should be dedicated to the image itself on smaller, portrait-style screens. It also lends toward a seemingly crowded UI. Please see the differences below from differing processing tool sites (noting that the photopea image width is adjusted for their ad space):

|  from https://pixlr.com       | from https://photopea.com  |  
| ----------- | ----|
| | (width adjusted for right column ad space) |
| ![pixlr](https://user-images.githubusercontent.com/81270711/164542925-0990cf1d-6af4-425f-9306-0d19926fd24c.png) | ![Screen Shot 2022-04-22 at 7 50 03 AM](https://user-images.githubusercontent.com/81270711/164717787-8ef1f344-5f43-469b-99d4-b6b9768f6dc3.png) | 
  


