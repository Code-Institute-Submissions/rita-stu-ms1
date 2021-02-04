# ms1: Raising Tomatoes

## About this project
[Raising Tomatoes](https://rita-stu.github.io/ms1) is an information-based website designed to provide answers and solutions to common tomato-growing problems. 

The site aims to include advice, instructions and tips for the visitor through web page articles and PDF downloads about how to grow and raise tomatoes successfully, in any climate.

__User Goals__
The goal of the site, for the user, is that they can quickly and easily find answers to common problems related to planting/growing and raising tomatoes.

__User Type__: How the Site Aims to Help the User

Whether a first-time grower or a seasoned grower, the user can find answers to their questions and solutions to the issues they face. User issues and problems include:

* where to source seeds and/or baby plants
* how to plant and grow from seed
* solutions to issues regarding plant health
* how to choose which types/varieties to grow
* pest problems
* how to maintain tomato plants (when to feed  and water, where to get good food)
* how and when to harvest tomatoes
* where to source seeds (links to external sites)
* tips about various tomato-related topics (downloadable PDFs with CTAs/links embedded)

__Other Services to Help the User__

The website aims to provide information about the best, most user-friendly products required by the user to start (or continue) to successfully grow tomatoes.

The service aims to offer the following solutions:

* outdoor growing: quality grow-pots and garden tools
* indoor growing: grow-pots designed for indoor growing (drainage)
* general growing: solutions and tips (location/types of tomatoes)

__Website Owner Goals__

The goal of the website owner merits a mention here because the site owner's motivation has an important influence on the overall design and development of the site, for example, certain desired user actions require certain technologies, which should be decided by the website owner.


## UX
The process aims to create a straightforward, user-friendly approach without distraction. As an information-based service, the design needs to support a lot of written content, structured in such a way that any user can effectively navigate the site, without "tripping over" unnecessary links or objects.

__Keeping the User in Mind__
The design is simple and to-the-point, offering an easy-to-follow pathway to allow users to quickly and easily find what they’re looking for.

Visitors to this site are mainly seeking information on a particular topic, in this case growing tomatoes. The user wants to know many things from how to source seeds to how to plant them successfully. The user's end goal is good fruit from healthy, self-grown tomato plants.

__UX With the Site Owner in Mind__
Keeping site-owner goals in mind, the end goal of the site is to generate revenue using online monetisation methods.

To achieve this, the site needs to provide a lot of content in different formats (online articles, downloadable documents, email newsletters) and will require the user to take some form of action (sign up to a newsletter or make contact via form or email). The design and development of the site will influence how the website can accommodate these needs.

__<a name="story">User Needs via User Stories</a>__

Here are nine user stories of potential visitors looking for solutions about growing tomatoes:

1. As a user, I want to find information about the best type of tomatoes to grow in my area (re available space, climate, soil, etc) with a view to raising four or five different varities.
2. A regualr user, I want to know where I can buy good heirloom tomato seeds.
3. I'm new to this site. I don't know what to feed my tomato plants and I'm looking for ideas. Can you help?
4. A new user, I LOVE tomatoes and I eat them daily. I'm thinking about growing tomatoes myself. I'd like an overview of everything I would need to start growing my own tomatoes (tools, soil, food).
5. I just found your website! I'm looking for information and resources about starting a home veggie garden – I'm interested in herbs, carrots, peas, tomatoes and courgettes. Which are the easiest, and quickest to grow? What type of soil is best? How much space would I need? How would I obtain good quality seeds?
6. I've visited this site before and I came here today because I have a greenfly problem! I need to find out how to combat pests in my veggie garden, specifically my tomato plants. I'd prefer non-chemical solutions, if possible.
7. I'm new here and I really want to grow my own tomatoes but my problem is space. I live in an apartment with a small balcony, so I have very limited space for growing anything. Any ideas?

These user needs are assessed in the [Testing](#test) section to see how and if the website offers a solution.

## Features

### Existing Features

__Feature 1: Navigation__
To help the user find their way about, the site layout has two navigation menus, a main one top-right (__nav__), and a secondary menu centred just above the footer (.flex-nav).

The navigation system is easy to find and easy to follow. Each nav menu links to pages that aim to offer solutions to user requests.

__nav Dropdown Menu__

The top nav utilises a dropdown menu from one of five links, __Seeds__, which has three additional links to __Heirloom Seeds__, __Hybrid Seeds__, and __About Seeds__. This dropdown menu allows the user a more specific choice.
 
__flex-nav Menu__
 
The flex-nav menu was originally a dropdown, a duplicate of __nav__
but due to positioning and responsive issues, and time constraints, it was changed to a regular ole menu inside a flexbox. It contains the main five links only – from here, users need to get to the heirloom and hybrid seeds pages via Seeds.

__Footer Nav__
There is a footer menu with links to the disclaimer and privacy policies (.policies), and a link to the contact page. This the only position for these links - they are not the priority of most visitors, but they are there if anybody is interested in viewing the site's policies.

A note on the contact page: should any user wish to contact the website owner, there are plenty of contact opportunities already on every page (email address top and bottom of each page, plus contact form). The decision was made to not clutter either navs (nav or flex-nav) with another link. This lack of clutter will be more user-friendly on handheld (small screen) devices.

__Embedded Links__

All written content includes __embedded links__ to take the user to more information on a specific topic. Some links lead to external sites, for example those in the Related Content section (lower page).

__Feature 2: Forms__

There are __two subscriber forms__ (.subscr), one at the very top of each page and one at the bottom, near the footer. The subscriber form is developed and designed as an unobtrusive call-to-action (CTA) to benefit users who wish to receive weekly updates (tips, advice, solutions).

There are two email links (mailto:) at the top and bottom of every page to offer the user another form of making contact with questions or queries.

__Feature 3: Downloads__

The design aims to accommodate downloadable PDFs to offer the user an offline/printable version of the information they've been looking for.

### Features Left to Implement

* __Selector Tool__: would be a very useful feature to offer users (time constraints and lack of current skills means developing a working tool for this project is a bit beyond me at the moment);
* __Recipes__ page, including downloadable PDFs;
* __Site expansion__: include non-seasonal veg/herbs;
* Blog: an active blog with comments enabled for healthy, open discussion between users.


## Technologies Used

    • __HTML__
    • __CSS__: employed to enhance the html code. CSS ideas from w3schools were utilised, in particular flexboxes, responsive design code and Google fonts code.
    • __Google fonts__: two Google fonts were used throughout the site – Roboto and Exo
    • __Bootstrap__ v4.3: nav menu with dropdown function was used for the main navigation menu
    • __GIMP__: used to resize images and create .png versions
    • __Gitpod__: used to write code and documentation for deployment to Github.
    • __Github__: used to store the project as a live site for reveiw by assessors.
    • __Figma__: used to create a wireframe as a mockup of design ideas before writing the code (creating the site).




## Content

__Written Content__

__Media__



## Testing

__<a name="test">User Stories Tested</a>__


__Responsive Test__


__Bugs Found__

excessive-code-footer.png
excessive-code-footer-FIX.png

02.02.21
********
hr-border-issue.png: <hr> displays single-px grey border on top.
FIX: set border-color same as background-color



## Problems/Issues

1. __RESOLVED__: Resposive design not employed correctly in footer and header – text is not wrapping on smaller screen view, likely due to using the wrong type of code. Everywhere else it’s working as it should.
2. __RESOLVED__: Bootstrap nav: can’t get it to align right, mentor suggested float property.
3. UNRESOLVED: Bootstrap nav: cannot change the colour of the links, no matter how many things I try – list-item, nav-item, etc. Nothing worked. SOLUTION: Need to ask mentor tomorrow (if time).
4. __RESOLVED__: Bootstrap nav: cannot get the position right. I wanted it as part of the top flexbox, and had to use -margin property (i.e. -20px), which will interfere with responsive design. SOLUTION: redo flexbox to incorporate it?? Might have to leave it as is, due to time restraints.
5. UNRESOLVED but CHANGED: Social media links in footer: I did them as standard, did not take into account responsive design. SOLUTION: redo as flexbox. (no time)
6. __RESOLVED__: Social media links in footer: I tried to use the FontAwesome icons but they don’t exist for most of these sm companies. For consistency, I didn’t use any. SOLUTION: create own icons using sm company logos. Display as small round images with each link embedded, or similar.
7. UNRESOLVED: Subscribe (to Newsletter) box not complete. I don’t have the JS skills yet, but would like to have had a basic reaction, i.e. when link is clicked, form confirms subscription (says “thanks for subscribing” or similar).
8. UNRESOLVED: Subscriber forms: cannot move script to any other position within html file. I don’t know why. Further, tried to use “required” for name element of form, but no luck so far (there’s no “name” attribute to add it to; I tried a couple of options but nothing changed so far.
9. UNRESOLVED: Make galleries more user friendly (and a little prettier!): add popup, containing link to more detailed info, with brief info about each type of tomato, such as variety/breed, type (determinate/indeterminate), price, best breeders/sellers. Time constraints.
10. UNRESOLVED: Fix form on lower end of each page (lwr-flex-left): textarea displays ever-so-slightly shorter than Name and Email when using size attribute – I had size="40" for both fields, and textarea set to rows=”5” cols=”5”, but textarea displayed shorter than the other two so I reset Name and Email to size=”20”. I would like to know what the problem is.
11. __RESOLVED__: hr-border-issue.png: <hr> displays single-px grey border on top. FIX: set border-color same as background-color.
12. __RESOLVED__: Excessive code in stylesheet. FIX: removed.





## Deployment



## Content

__Written Content__


__Media__


## Acknowledgements
I wish to acknowledge those who supported me through this project, including those who don't know that they did.

Thank you to my mentor for his support and ideas.