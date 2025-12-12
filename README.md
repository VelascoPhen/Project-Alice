

**PROJECT DOCUMENTATION**

**: PROJECT ALICE**





**PREPARED BY: GROUP 4**

ENRIQUEZ, ZEYRUS VIN

EUGENIO, MICHAEL ANGELO

GARCIA, CHELSEA

ROJO, QUEEN

SOLER, TEEJAY

VELASCO, PHENELOPE






**SUBMITTED TO:**\
Mr. Dowelle Dayle Mon




IN REQUIREMENT FOR\
FINAL PROJECT FOR OBJECT ORIENTED PROGRAMMING






**SUBMITTED ON:**

**December 12, 2025**\


The following documentation provides an overview of Project Alice, a competitive, turn-based RPG implemented as a web application.

1. **Project Overview**

**Game Title:** Project Alice (2-Player Turn-Based RPG)

**Concept and Description**

Project Alice is a 2D, turn-based, dark fantasy PvP role-playing game (RPG). It draws inspiration from the eerie atmosphere and tactical mechanics of the *Fear & Hunger* series. The game is centered on two players who engage in combat, vying for control of the eldritch entity known as Alice —a being of great power and mystery. The development focus is placed on delivering a tense and strategic combat experience that challenges skill and decision-making, rather than complex lore.

**Game Objectives and Win/Lose Conditions**

Players initiate the match by selecting one of three distinct character classes: Thug, Doctor, or Occultist. Each class possesses unique skills and abilities, which are managed through the OOP structure. Combat is turn-based, with the first strike determined by a coin flip. Players continue the match until one player's HP reaches zero. An alternative victory condition is achieved by capturing Alice.

1. **Technology Stack**

This project utilizes a standard Client-Server Architecture implemented via a modern web stack.

|**Layer**|**Technology**|**Purpose**|**Suggested Version**|
| :-: | :-: | :-: | :-: |
|**Backend**|PHP|Handles all core gameplay logic: turn processing, damage calculations, session management, and implementing the OOP class hierarchy|<p></p><p></p><p></p><p>8\.0 or higher</p>|
|**Frontend**|HTML, CSS, JavaScript|Manages the responsive user interface, skill buttons, health bars, and turn indicators. Delivers player interactions|<p></p><p></p><p>ES6+ (ECMAScript 2015)</p>|
|**Version Control**|GitHub, VSCode LiveShare|Ensures collaborative development, change tracking, and code versioning.|<p></p><p>N/A</p>|
|**Design Tools**|Figma, Canva|Used for creating UI mockups, layout designs, and visual assets.|<p></p><p>N/A</p>|

`	`**3. Team Members and Contributions**

|**NAME**|**CONTRIBUTION**|
| :-: | :-: |
|1. Phenelope Velasco|<p>**Team Leader:**</p><p>- Team Leader; Lead Front-End Developer; Back-End Developer; Oversaw project documentation; Coordinated team tasks and workflow; Ensured integration of gameplay mechanics with the user interface.</p>|
|2. Chelsea Garcia|- Front-End Developer; Assisted in UI/UX implementation; Contributed to documentation; Supported responsive design and layout consistency.|
|3. Queen Rojo|- Front-End Developer; Implemented visual and interactive elements; Assisted with documentation and design alignment.|
|4. Michael Angelo Eugenio|- Back-End Developer; Responsible for core gameplay logic, damage calculation, and turn-based mechanics; Debugger & QA tester; Contributed to project documentation; Game Designer – assisted in gameplay balancing.|
|5. Teejay Soler|- Sound Effects Designer; Created and integrated audio assets to enhance the gaming experience.|
|6. Zeyrus Vin Enriquez|- Game Designer; Collaborated on gameplay mechanics and balance; Assisted in Front-End development; Supported UI/UX refinement and playtesting.|

\
\
**4. How to Play [**CLICK HERE**](https://drive.google.com/file/d/1M8-xITDtjoR2Yspy63qFQQb0eUJwn3_B/view?usp=sharing)**

\
**5. How to run the Program**
# <a name="_1tq70yrz0whw"></a>0. Important: Do NOT run by opening files in VS Code / Live Server
Because this project uses PHP for the backend, it must be served by a PHP-enabled web server. Opening the HTML file directly (file://) or using VS Code Live Server will not execute PHP and may break routing/paths.

Correct way:

- Run the project through localhost (Apache/XAMPP/WAMP/MAMP) or the built-in PHP server.
- Then open the page in your browser using a URL like:

http://localhost:5080/CODE/HTML/menu\_load.html
# 1\. Required Software and Dependencies
- PHP 8.0 or higher (needed for the backend OOP classes and game logic).
- A web server with PHP support (choose one): XAMPP / WAMP / MAMP, or PHP's built-in development server (php -S).
- A modern web browser (Chrome, Edge, Firefox).
- Optional: Git (if you will clone the repository).
# 2\. Place the project in the correct folder (Document Root)
Your URL example (http://localhost:5080/CODE/HTML/menu\_load.html) means the folder named CODE must be inside the web server's document root.

Two common setups:

**Setup A (Recommended for your exact URL):** Set your document root to the folder that contains CODE.

- Example structure:

<your-doc-root>/\
`  `CODE/\
`    `HTML/\
`      `menu\_load.html\
`    `CSS/\
`    `JS/\
`    `PHP/   (if applicable)\
`    `ASSETS/

**Setup B (Default XAMPP/WAMP/MAMP):** Put the whole project inside htdocs/www and include the project folder name in the URL.

- Example (file path):

C:\xampp\htdocs\project-alice\CODE\HTML\menu\_load.html

- Then the URL becomes:

http://localhost/project-alice/CODE/HTML/menu\_load.html
# 3\. Start the server and open the project
## Option A: PHP built-in server (fastest, easiest to use port 5080)
\1) Open Command Prompt / Terminal\.

\2) Change directory to the folder that contains CODE (this will be your document root)\.

cd path\to\your\doc-root

\3) Start the server on port 5080:

php -S localhost:5080 -t .

\4) In your browser, open:

http://localhost:5080/CODE/HTML/menu\_load.html

- Keep the terminal window open while you are testing.
## Option B: XAMPP / WAMP / MAMP (Apache)
\1) Put your project folder in the server web root:

- XAMPP: C:\xampp\htdocs\
- WAMP: C:\wamp64\www\
- MAMP: Applications/MAMP/htdocs/

\2) Start Apache from the control panel\.

\3) Open the correct URL:

http://localhost/<project-folder>/CODE/HTML/menu\_load.html

- If you specifically need port 5080 with Apache:

Edit Apache's configuration to change the port (advanced). In XAMPP, update the Listen/ServerName port in httpd.conf and any relevant VirtualHost/SSL configs, then restart Apache.
# 4\. Common issues and quick fixes
**PHP not working / page shows raw PHP:** You are not running through a PHP-enabled server. Use Option A or Option B above (do not use file:// or VS Code Live Server).

**CSS/JS/images not loading (404):** Check your paths. If you want to reference from the server root, prefer absolute paths like /CODE/CSS/battle.css (only if CODE is in the document root).

**Wrong URL:** Confirm where CODE is located. If CODE is inside a project folder, your URL must include that folder name (e.g., /project-alice/CODE/...).

**Port already in use:** Choose another port (e.g., 8000) or stop the app using 5080. Then update the URL accordingly.
##
[**VIDEO DOCUMENTATION LINKS**](https://drive.google.com/drive/folders/1xPwpZlL_HvNAxu87VlaWpRVhhB_odcSg?usp=sharing)
