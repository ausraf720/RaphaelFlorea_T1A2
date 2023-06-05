# Coder Academy Assignment T1A2 - Raphael Florea

## Important links:

[Github](https://github.com/ausraf720/RaphaelFlorea_T1A2) 
<br>

[Presentation](https://www.youtube.com/watch?v=kmw_dUbu6JQ) 
<br>

[Website](https://raphael-florea-t1-a2.vercel.app/)

## NOTE

The homepage is found inside the src folder as 'index.html'. That is where the website should be opened from, and it's opened from there in Vercel.

## Purpose

The website contains these three types of information that I want to present:
* My professional contact details
* A page detailing my skills, education, and experience
* A blog to showcase some of my hobbies and problem solving abilities relating to computer science

Thus, the main goal and purpose of the website is to provide a hub for this information that is highly accessible,
and conveys the information in a clear and captive manner. It achieves being accesible and also captivating as described in the section below.

## Functionality and Features

### _Homepage_

The homepage, and also subsequent webpages, was designed to have a more mechanical and sci-fi theme to it. In particular, the sci-fi theme is achieved in a number of ways:
* Links to other pages and the main profile picture are enclosed within hexagons
* Using a hexagonal background
* Black, green, white, and grey are the predominant colours of the homepage and others
* 'Monaco' is the default font, a font already associated with software development

The most technically complicated part of the website is the ability for each hexagon's borders to rotate around its parent hexagon when hovered over, giving a mechanical appearance to the hexagon. This was achieved through:
* Using keyframes to create infinite animation loops, with 6 intervals for 6 sides
* Using some SCSS to help reduce the number of lines of code

This homepage is also able to adjust to different size screens to become more accessible, by changing the layout of the hexagon as follows:
* For mobile screens, the hexagons are placed close to each other in a honeycomb formation, with the profile picture in the center
* Tablet screens have enough width that the hexagons can now have some space between them, and the hexagon buttons are arranged in a 2x2 matrix with the profile pic now on top and larger
* PC screens have all the hexagon buttons in a single row below the profile pic

In addition to the hexagons, the title of the page is my name only, for simplicity's sake. It's position is fixed, as to remain at the top of the page and visible at all times.

At the bottom of the page is a footer that displays a Github icon and LinkedIn icon, with links to both of my accounts for those services respectively. They also have animations, where they will enlarge when hovered over.

### _Blog (Machine)_

The current blog is about a project of mine involving 'redstone' in the game Minecraft, and it is a project I want to showcase in some capacity as it demonstrates my ability to understand logic circuits and binary.

At the top of this page, and the rest of the pages, is a navbar. This navbar helps the entire website to be accessible in the following ways:
* The position is fixed, so it's always on the screen
* There are always links to the three other pages the user is not currently viewing
* An individual link will enlarge and gain a white background when hovered over, for clarity

For the main section of this page, the blog posts are contained in a flexbox formation. Firstly, this allows for a different number of columns per screen size:
* 1 column for mobile users
* 2 columns for tablet users
* 3 columns for desktop users

Likewise, flexbox allows for the possibility to have indivual posts become enlarged slightly when hovered over, without compromising the structure of the page. Thus, users can easily hover over a post to see the post's content more easily without issues.

Each post contains an image, a summary title, and a description of the image.

Finally, the page has its own title post with larger text and different colours to distinguish itself from the rest of the content, a quick overall description of the project, and has an image showing the current state of the project. The width of this section changes depending on screen, where it appears proportionally less wide the larger the screen. This is so it becomes less instrusive for larger screens.

### _About_

This page has a very similar structure to the blog. However, the information relates to skills and experience, so within each article is a summary of a specific set of skills or experience relating to a certain topic. The articles used here are the same class to the ones in the blog, but there are some differences to the content:
* Instead of a single image, multiple icons are used that relate to the skills/experience being listed
* The title describes the topic of skills/experience being listed
* An unordered list of skills/experience is provided

Aditionally, there is a link to a resume underneath the page's title instead of an image, and a short description of my personal attributes under that section.

Asides from the above differences, the about page is otherwise the same as the blog page.

### _Contact_

This page is much simpler than the others, featuring only a small list of contact information. The section used to house this list utilises the same class as the titles for the previous two pages, for simplicity and clarity, with some notable features:

* On each line, there is an icon to represent the type of contact, and next to it a direct link to the contact itself
* The LinkedIn and Github contacts go to the same links as featured on the homepage
* The other two links are email addresses, which prompt the user to open up their email provider to send an email to that particular address

Otherwise, this page contains no other extra sections, as there is no need for it.

## Target Audience

The target audience are professionals in the IT industry, most likely those who are potential future employers or at least those wishing to colaborate with me on software development projects.

## Tech Stack

Here are the following scritping languages that were used:
* HTML
* CSS
* SASS

## Sitemap
<br>

![Sitemap](./docs/Sitemap.png)
<br>

## Screenshots

### Homepage screenshots
![Homepage upper](./docs/screenshots/homepage_desktop.png)
<br>

![Homepage lower](./docs/screenshots/homepage_scrolled_down.png)
<br>

![Homepage tablet](./docs/screenshots/homepage_tablet.png)
<br>

![Homepage mobile](./docs/screenshots/homepage_mobile.png)
<br>

![Hexagon still](./docs/screenshots/hex_still.png)
<br>

![Hexagon animated](./docs/screenshots/hex_animated.png)
<br>

![Homepage icons](./docs/screenshots/icon_hover_enlarged.png)

### Blog screenshots
![Blog upper](./docs/screenshots/blog_desktop_heading.png)
<br>

![Blog lower](./docs/screenshots/blog_desktop_lower.png)
<br>

![Blog tablet](./docs/screenshots/blog_tablet.png)
<br>

![Blog mobile](./docs/screenshots/blog_mobile.png)
<br>

![Blog post](./docs/screenshots/blog_post_enlarged.png)
<br>

![Blog navbar](./docs/screenshots/navbar.png)
<br>

### About screenshots
![About desktop](./docs/screenshots/about_desktop.png)
<br>

![About tablet](./docs/screenshots/about_tablet.png)
<br>

![About mobile](./docs/screenshots/about_mobile.png)
<br>

### Contact screenshots
![Contact desktop](./docs/screenshots/contact_desktop.png)
<br>

![Contact tablet](./docs/screenshots/contact_tablet.png)
<br>

![Contact mobile](./docs/screenshots/contact_mobile.png)
<br>

![Contact link](./docs/screenshots/contact_link.png)
<br>

![Contact email](./docs/screenshots/contact_email_opening.png)
<br>

## Wireframes

### Homepage wireframes
![Homepage desktop](./docs/wireframes/homepage_wireframe_desktop.png)
<br>

![Homepage tablet](./docs/wireframes/homepage_wireframe_tablet.png)
<br>

![Homepage mobile](./docs/wireframes/homepage_wireframe_mobile.png)
<br>

### Blog wireframes
![Blog desktop](./docs/wireframes/blog_wireframe_desktop.png)
<br>

![Blog tablet](./docs/wireframes/blog_wireframe_tablet.png)
<br>

![Blog mobile](./docs/wireframes/blog_wireframe_mobile.png)
<br>

### About wireframes
![About desktop](./docs/wireframes/about_wireframe_desktop.png)
<br>

![About tablet](./docs/wireframes/about_wireframe_tablet.png)
<br>

![About mobile](./docs/wireframes/about_wireframe_mobile.png)
<br>

### Contact wireframes
![Contact desktop](./docs/wireframes/contact_wireframe_desktop.png)
<br>

![Contact tablet](./docs/wireframes/contact_wireframe_tablet.png)
<br>

![Contact mobile](./docs/wireframes/contact_wireframe_mobile.png)
<br>


