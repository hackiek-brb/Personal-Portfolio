Project: Brian’s Portfolio (A2)
By: Brian Bui (B01043369)
Course: CSCI 1170


-------------------------------------------------------------------------------


NOTE ON CODE REUSE

The HTML structure and content (index.html, education.html, gym.html) were originally created for Assignment 1. For Assignment 2, all deprecated HTML attributes (bgcolor, <font>, align, cellpadding, valign, etc.) were removed and replaced with a proper external CSS stylesheet (style.css). JavaScript (script.js) was added to implement the required interactive features. The CSS and JavaScript files are entirely new for Assignment 2.


-------------------------------------------------------------------------------


FILE STRUCTURE

A2_wl969576/
|
|-- index.html              (Home / Main / About Me page)
|-- education.html          (Education page)
|-- gym.html                (Gym Progress page)
|-- style.css               (Main stylesheet, all visual styling)
|-- script.js               (All JavaScript features)
|-- code_review.pdf         (Part 1: Code Review document)
|-- README.txt              (This file)
|
|-- images/
|   |-- logow.png                       (BrB logo — white version)
|   |
|   |-- index/
|   |   |-- index1.jpeg                 (About Me photo)
|   |   |-- index2.jpeg                 (Social Life photo)
|   |   |-- sclogo1.png                 (Instagram icon)
|   |   |-- sclogo2.png                 (LinkedIn icon)
|   |   |-- sclogo3.png                 (Facebook icon)
|   |   |-- slogo1.jpg                  (Dal Hacker's Society logo)
|   |   |-- slogo2.png                  (AWS Cloud Club logo)
|   |   |-- slogo3.jpg                  (Dal Language Exchange logo)
|   |
|   |-- education/
|   |   |-- woodlawn.jpg                (Woodlawn High School photo)
|   |   |-- highschool1.jpg             (Last day at Woodlawn)
|   |   |-- highschool2.jpg             (Teacher-Student day)
|   |   |-- highschool3.jpeg            (Favourite friends and teacher)
|   |   |-- dalhousie.jpeg              (Dalhousie University photo)
|   |   |-- uni1.PNG                    (Job Fair day)
|   |   |-- uni2.jpg                    (Codechella week)
|   |   |-- uni3.jpg                    (CS building)
|   |
|   |-- gym/
|       |-- gym1.JPG                    (Me and my bro photo)
|       |-- gym2.jpg                    (Day 1 photo)
|       |-- gym3.JPG                    (Day 500 photo)
|
|-- music/
|   |-- music.m4a                       (Music audio file)
|
|-- video/
    |-- pr.mp4                          (Bench press personal record video)


-------------------------------------------------------------------------------


ASSET LIST

IMAGES:

logow.png           - Personal logo (BrB signature). Created by Brian Bui.
index1.jpeg         - Personal graduation photo. Taken by Brian Bui.
index2.jpeg         - Personal mirror photo. Taken by Brian Bui.
sclogo1.png         - Instagram logo. Source: Instagram brand assets.
sclogo2.png         - LinkedIn logo. Source: LinkedIn brand assets.
sclogo3.png         - Facebook logo. Source: Meta brand assets.
slogo1.jpg          - Dal Hacker's Society logo. Source: Dal Hacker's Society
slogo2.png          - AWS Cloud Club at Dalhousie logo. Source: AWS Cloud Club
slogo3.jpg          - Dal Language Exchange Society logo. Source: Dal Language
woodlawn.jpg        - Woodlawn High School exterior photo. Source: HRCE.
highschool1.jpg     - Personal photo from Woodlawn. Taken by Brian Bui.
highschool2.jpg     - Personal photo from Woodlawn. Taken by Brian Bui.
highschool3.jpeg    - Personal photo from Woodlawn. Taken by Brian Bui.
dalhousie.jpeg      - Dalhousie University campus photo. Source: Dal website.
uni1.PNG            - Personal photo at Dal Job Fair. Taken by Brian Bui.
uni2.jpg            - Personal photo at Codechella. Taken by Brian Bui.
uni3.jpg            - Personal photo at CS building. Taken by Brian Bui.
gym1.JPG            - Personal gym photo. Taken by Brian Bui.
gym2.jpg            - Personal gym photo (Day 1). Taken by Brian Bui.
gym3.JPG            - Personal gym photo (Day 500). Taken by Brian Bui.


MEDIA:

music.m4a           - Personal music file. Source: YouTube.
pr.mp4              - Personal bench press video. Recorded by Brian Bui.


EMBEDDED MEDIA

YouTube video embedded via iframe (gym.html):
Title: "How to Build a Perfect Physique" (motivation video)
URL:   https://www.youtube.com/embed/Jaep7tUCJ1Q
Source: YouTube.


-------------------------------------------------------------------------------


ACM REFERENCES

-Meta Platforms, Inc. n.d. Facebook Brand Resource Center. Retrieved March 2026 from https://www.meta.com/brand/resources/facebook/logo/
-LinkedIn Corporation. n.d. LinkedIn Brand Guidelines. Retrieved March 2026 from https://brand.linkedin.com/en-us
-Meta Platforms, Inc. n.d. Instagram Brand Resources. Retrieved March 2026 from https://about.instagram.com/brand
-Dalhousie University. n.d. Dalhousie University Official Website. Retrieved March 2026 from https://www.dal.ca
-Halifax Regional Centre for Education. n.d. Woodlawn High School. Retrieved March 2026 from https://wdn.hrce.ca
-Dalhousie Hacker's Society. 2026. Dalhousie Hacker's Society Instagram. Retrieved March 2026 from https://www.instagram.com/dalhackerssociety
-AWS Cloud Club at Dalhousie University. 2026. AWS Cloud Club LinkedIn Page. Retrieved March 2026 from https://www.linkedin.com/company/aws-cloud-club-dal
-Dalhousie Language Exchange Society. 2025. Dal Language Exchange Instagram. Retrieved March 2026 from https://www.instagram.com/dallangexchange


-------------------------------------------------------------------------------


HTML FILES

------------------------------------------------

index.html — Home / About Me Page


Purpose: Landing page of the portfolio. Contains the About Me section, Social Life section, a name greeting input, background music player, society logos, and social media links.

Relative paths used:
images/logow.png            
images/index/index1.jpeg
images/index/index2.jpeg
images/index/sclogo1.png
images/index/sclogo2.png
images/index/sclogo3.png
images/index/slogo1.jpg
images/index/slogo2.png
images/index/slogo3.jpg
music/music.m4a
style.css
script.js

JS features used:
greetVisitor()      - notification on page load
updateGreeting()    - real-time name greeting
setTheme()          - colour scheme buttons
toggleSidebar()     - hamburger sidebar toggle
initBackToTop()     - back to top scroll button

------------------------------------------------

education.html — Education Page


Purpose: Displays secondary (Woodlawn High School) and post-secondary (Dalhousie University) education history, photo grids, descriptive text, and a course table.

Relative paths used:
images/logow.png
images/education/woodlawn.jpg
images/education/highschool1.jpg
images/education/highschool2.jpg
images/education/highschool3.jpeg
images/education/dalhousie.jpeg
images/education/uni1.PNG
images/education/uni2.jpg
images/education/uni3.jpg
images/index/sclogo1.png
images/index/sclogo2.png
images/index/sclogo3.png
style.css
script.js

JS features used:
setTheme()          - colour scheme buttons
toggleSidebar()     - hamburger sidebar toggle
initBackToTop()     - back to top scroll button

------------------------------------------------

gym.html — Gym Progress Page

Purpose:
Documents gym journey from Day 1 to Day 500. Contains motivational text, progress photos, an embedded YouTube video, and a personal record bench press video.

Relative paths used:
images/logow.png
images/gym/gym1.JPG
images/gym/gym2.jpg
images/gym/gym3.JPG
images/index/sclogo1.png
images/index/sclogo2.png
images/index/sclogo3.png
video/pr.mp4
style.css
script.js

JS features used:
setTheme()          - colour scheme buttons
toggleSidebar()     - hamburger sidebar toggle
initBackToTop()     - back to top scroll button


-------------------------------------------------------------------------------


CSS FILE — style.css

Purpose: Main stylesheet for all three pages. Removes all deprecated HTML presentation attributes and handles layout, colour themes, typography, responsive design (tablet and mobile), sidebar, topnav, and component styling.

------------------------------------------------

CSS VARIABLES (:root, body.light, body.ocean)

Purpose: Define colour tokens for each of the three themes. All colours across the site reference these variables so that changing a theme class on <body> instantly updates the entire page.

:root       - Dark theme (default). Black backgrounds, light grey text.
body.light  - Light theme. White/grey backgrounds, dark text.
body.ocean  - Ocean theme. Dark navy blue backgrounds, light blue text.

------------------------------------------------

Variables defined per theme:
--bg            Background colour of the page
--sidebar-bg    Background colour of the sidebar and table headers
--topnav-bg     Background colour of the top navigation bar
--text          Main text colour
--text-muted    Secondary text colour (captions, IDs, etc.)
--link          Link colour
--link-hover    Link hover colour
--border        Border colour for dividers, tables, buttons
--row-hover     Table row hover background
--btn-bg        Button background colour
--btn-border    Button border colour
--btn-hover-bg  Button background on hover 
--btn-hover-fg  Button text on hover
--shadow        Box shadow colour
--hr            Horizontal rule colour
--notif-bg      Notification banner background

------------------------------------------------

LAYOUT

#topnav
Purpose: Sticky top navigation bar containing the hamburger button, brand logo, page links, and theme buttons.

#page-body
Purpose: Flex container holding the sidebar and main content side by side.

#sidebar
Purpose: Left navigation panel. Collapses to zero width when the .collapsed class is applied. On tablet/mobile it becomes a fixed overlay.

#sidebar.collapsed
Purpose: Hides the sidebar by setting width and opacity to 0.

#main-content
Purpose: Main scrollable content area. Takes remaining flex space after the sidebar.

------------------------------------------------

COMPONENTS

.content-row
Purpose: Two-column flex row for side-by-side content (text + image).

.content-row.reverse
Purpose: Reverses column order so image appears on the left.

.content-col
Purpose: Flexible column inside a content-row.

.content-col.img-col
Purpose: Fixed-width image column that does not grow.

.photo-grid
Purpose: Centered flex row for 2-3 photos side by side.

.course-table
Purpose: Styled HTML table for the course list on education.html.

.society-row
Purpose: Flex row of society logos, centered with gap spacing.

.social-row
Purpose: Flex row of social media icons, centered.

.theme-btn / .theme-btn.active
Purpose: Styles for the three colour scheme buttons. Active state inverts the button colours to indicate the selected theme.

#sidebar-toggle.active
Purpose: Highlights the hamburger button when the sidebar is open.

#greeting-section, #name-input, #greeting-text
Purpose: Styles the name input box and greeting text on index.html. Input text is centered. Greeting text is italic and muted.

#notification-banner / #notification-banner.show
Purpose: Fixed banner that slides down from above the topnav.
         .show class sets top: 76px to make it visible.

#back-to-top
Purpose: Fixed button in the bottom-right corner. Hidden by default; shown via JavaScript when the user scrolls down 300px.

------------------------------------------------

RESPONSIVE (Media Queries)

@media (max-width: 900px) — Tablet breakpoint
- Sidebar auto-collapses and becomes a fixed overlay when opened.
- Brand logo is centered in topnav using flex:1 on all three children.
- Content rows stack vertically (flex-direction: column).
- Images scale to max-width: 480px centered.
- Theme buttons shrink to font-size: 11px.
- Photo grid reduces gap to 30px.
- Body font-size reduced to 16px.

@media (max-width: 600px) — Mobile breakpoint
- Sidebar overlay expands to full viewport width.
- Page links in topnav are hidden; only theme buttons remain.
- Theme buttons shrink to font-size: 10px.
- Photos scale to 90vw.
- Social icons shrink to 60px.
- Course table scrolls horizontally with white-space: nowrap.
- Video/iframe elements scale to 100% width.
- Name input widens to 80vw.
- Body font-size reduced to 14px.


-------------------------------------------------------------------------------


JAVASCRIPT FILE — script.js


------------------------------------------------

setTheme(scheme)

Purpose: Applies one of three colour schemes to the page by adding or removing CSS classes on <body>. Updates the active button highlight and saves the choice to localStorage so it persists across pages and sessions.

Input: 
scheme (string) — one of "dark", "light", or "ocean"

Output: 
None. Side effects: modifies body classList, localStorage, and .theme-btn active states.

Example:
setTheme("ocean");
-Adds class "ocean" to <body>, saves "ocean" to localStorage,
-highlights the Ocean button.

Dependent code:
CSS classes body.light, body.ocean, .theme-btn, .theme-btn.active in style.css
HTML elements: buttons with class="theme-btn" and data-theme attribute

------------------------------------------------

restoreTheme()

Purpose: Reads the saved colour scheme from localStorage on page load and re-applies it by calling setTheme(). Prevents a flash of the wrong theme on page load.

Input:  None

Output: None. Calls setTheme() with saved value or "dark" as default.

Dependent code: setTheme(), localStorage key "brianTheme"

------------------------------------------------

showNotification(message)

Purpose: Slides a notification banner down from the top of the page with a given message. The banner auto-dismisses after 4 seconds. The user can also close it manually with the X button.

Input: message (string) — text to display in the banner

Output:
None. Side effects: modifies notification-banner classList (adds "show"), sets a 4-second timeout to call dismissNotification().

Example:
showNotification("Welcome to Brian Bui's Portfolio!");
-> Banner slides down and displays the message for 4 seconds.

Dependent code:
#notification-banner, #notification-msg in all HTML files
#notification-banner.show in style.css
dismissNotification()

------------------------------------------------

dismissNotification()

Purpose: Hides the notification banner by removing the "show" class, causing
it to slide back up off-screen.

Input:  None

Output: None. Side effect: removes "show" from #notification-banner.

Dependent code: #notification-banner in style.css

------------------------------------------------

greetVisitor()

Purpose: Checks localStorage for a previous-visit flag. Displays a different notification message for first-time visitors versus returning visitors, then passes the message to showNotification(). Only called on index.html via a pathname check in the DOMContentLoaded listener.

Input:  None

Output: None. Calls showNotification() with a greeting string.

Example:
First visit:
greetVisitor(); -> shows "Welcome to Brian Bui's Portfolio!"
                -> sets localStorage key "brianPortfolioVisited"

Subsequent visits:
greetVisitor(); -> shows "Welcome back to Brian's Portfolio!"

Dependent code:
showNotification(), localStorage key "brianPortfolioVisited"

------------------------------------------------

toggleSidebar()

Purpose: Shows or hides the sidebar by toggling the "collapsed" CSS class on #sidebar. Also toggles the "active" class on the hamburger button to visually indicate the open/closed state. Saves the state to localStorage.

Input:  None

Output: None. Side effects: toggles #sidebar.collapsed, toggles #sidebar-toggle.active, updates localStorage key "brianSidebar".

Dependent code:
#sidebar, #sidebar.collapsed, #sidebar-toggle, #sidebar-toggle.active in style.css
restoreSidebar()

------------------------------------------------

restoreSidebar()

Purpose: Reads the saved sidebar state from localStorage on page load. On tablet and mobile (viewport <= 900px), the sidebar always starts collapsed regardless of the saved state.

Input:  None

Output: None. Side effects: may add "collapsed" to #sidebar and remove "active" from #sidebar-toggle.

Dependent code:
toggleSidebar(), localStorage key "brianSidebar"

------------------------------------------------

initBackToTop()

Purpose: Attaches a "scroll" event listener to the window. When the user scrolls more than 300px down, a Back to Top button becomes visible. Clicking the button smoothly scrolls the window back to the top.

Input:  None (attaches event listeners to window and #back-to-top)

Output: None. Side effects: shows/hides #back-to-top button on scroll, scrolls to top on click.

Example:
-User scrolls 400px down → button appears.
-User clicks button → window.scrollTo({ top: 0, behavior: "smooth" })

Dependent code:
#back-to-top in all HTML files
#back-to-top styles in style.css

------------------------------------------------

updateGreeting()

Purpose: Reads the current value of the name input field (#name-input) and updates #greeting-text in real time as the user types. If the field is empty, the greeting is cleared. Called via the oninput event on the input element in index.html.

Input: None. Reads #name-input.value from the DOM.

Output: None. Side effect: sets textContent of #greeting-text.

Example:
-User types "Khoa" → greeting-text shows "Hello, Khoa!"
-User clears input → greeting-text shows ""

Dependent code:
#name-input, #greeting-text in index.html
#greeting-section, #name-input, #greeting-text in style.css

------------------------------------------------

DOMContentLoaded Initialisation

Purpose: Runs all setup functions once the DOM is fully loaded.

Order of execution:
1. restoreTheme()     - apply saved colour scheme 
2. restoreSidebar()   - apply saved sidebar state
3. greetVisitor()     - show notification, only on index.html (checked via pathname)
4. initBackToTop()    - attach scroll event handler

Dependent code: All functions listed above.
