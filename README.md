# WEB-Assignment2
Made by Diyar Kabyken

Objective:
The objective of this assignment is to learn and apply modern CSS layout techniques, specifically Flexbox and CSS Grid. The project covers building navigation bars, card rows, complex page structures using grid areas, responsive image galleries with hover overlays, and combining Flexbox and Grid into a complete portfolio layout.

Part 1: Flexbox

Task 0: Navigation Bar
In this task, I created a header element containing a logo on the left side and navigation links on the right side. I converted the header into a flex container using `display: flex`. I used `justify-content: space-between` to position the logo and links on opposite sides, `align-items: center` to align them vertically, and `gap` to add spacing between the navigation links.

<img width="1816" height="97" alt="image" src="https://github.com/user-attachments/assets/fc1e791f-c46a-4745-a077-19e21b73f5a9" />
<img width="418" height="238" alt="image" src="https://github.com/user-attachments/assets/5d0bb582-951e-4e57-9636-2c70ac09e2db" />
<img width="396" height="265" alt="image" src="https://github.com/user-attachments/assets/556aac56-2137-406a-961f-a203823978cc" />

---

Task 1: Card Row
In this task, I created a container with three cards, where each card contains an image, a title, a short description, and a button. Using `display: flex`, the cards were aligned horizontally in a row. By default, `align-items: stretch` ensured that all cards maintain equal height regardless of content length. I added consistent spacing between cards using `gap` and implemented a hover effect that lifts the card slightly using `transform: translateY(-5px)` and adds a box shadow.

<img width="1847" height="937" alt="image" src="https://github.com/user-attachments/assets/664235d1-80ab-4acd-9130-babd103824c2" />
<img width="1240" height="530" alt="image" src="https://github.com/user-attachments/assets/6d11ad00-5ba8-44d8-a80e-bef1b950d161" />


---

Part 2: Grid System

Task 2: Page Layout with Grid Areas
In this task, I set up a page layout consisting of a header, sidebar, main content area, and footer. I converted the main container into a grid container using `display: grid` and defined columns and rows. Using `grid-template-areas`, I assigned specific areas so that the header spans across the top, the sidebar is placed on the left, the main content is on the right, and the footer spans across the bottom.

<img width="1869" height="507" alt="image" src="https://github.com/user-attachments/assets/ebac053c-2251-42d2-88c0-8df821ea14b6" />
<img width="1246" height="197" alt="image" src="https://github.com/user-attachments/assets/dd9a932a-1ea3-4bdb-ab36-29adafa46df0" />

---

Task 3: Image Gallery
In this task, I created an image gallery containing nine images. I defined the gallery container as a grid using `display: grid` and created three equal-width columns using `grid-template-columns: repeat(3, 1fr)`. I added equal spacing between gallery items using `gap`. Additionally, I implemented a hover effect where an image caption overlay appears when the user hovers over an image.

<img width="1882" height="940" alt="image" src="https://github.com/user-attachments/assets/916a1bf5-5654-420a-b21c-77465a25a432" />
<img width="998" height="695" alt="image" src="https://github.com/user-attachments/assets/05946eed-9148-4c0d-98b1-a88d50734031" />

---

Part 3: Combining Flexbox & Grid

Task 4: Portfolio Page
In this task, I built a complete portfolio page structure combining both Flexbox and Grid. I used Flexbox inside the header for the navigation bar. For the main body, I used CSS Grid to divide the layout into a project section on the left and a sidebar on the right. Inside each project card, I used Flexbox to structure the title, description, and button, ensuring proper alignment. The footer spans across the bottom of the page.

<img width="1869" height="637" alt="image" src="https://github.com/user-attachments/assets/75cc6662-947a-421f-9f2a-db2178ba7a13" />
<img width="1036" height="683" alt="image" src="https://github.com/user-attachments/assets/3422966b-2012-4fef-895c-b93ae584e01d" />

---

Summary of Work Process
The project began by creating the HTML structure in `index.html` for all required tasks. In `style.css`, Flexbox properties such as `display: flex`, `justify-content`, `align-items`, and `gap` were applied for navigation and card alignment. CSS Grid properties including `grid-template-areas`, `grid-template-columns`, and `gap` were utilized to build page structures and image galleries. Finally, Flexbox and Grid were combined in the portfolio page section to demonstrate layout flexibility before uploading the final project to GitHub.
