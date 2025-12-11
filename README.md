

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
## <a name="_1tq70yrz0whw"></a>**1. Required Software and Dependencies**
Before running the game locally, make sure you have:

1. PHP 8.0 or higher

   1. Used for all backend game logic (turns, damage, sessions, OOP classes like Thug, Doctor, Occultist, and BattleManager).
1. A web server with PHP support (choose one):
   1. XAMPP (Windows/macOS/Linux, includes Apache + PHP)
   1. WAMP (Windows)
   1. MAMP (macOS/Windows)
   1. Or the built-in PHP development server (php -S)
1. Modern web browser
   1. Any up-to-date browser (Chrome, Firefox, Edge, etc.) to run the HTML/CSS/JavaScript frontend.
1. (Optional) Git
   1. If you want to clone from a remote repository instead of downloading a ZIP.

Note: No external PHP frameworks are strictly required; the project uses vanilla PHP with OOP for the game logic.


<a name="_5p00potkjv2m"></a>\
\
\
\
**2. Step-by-Step Installation Instructions**
---------------------------------------------

### <a name="_6gqqqedg7rzh"></a>**A. Download or Clone the Project**

1. Option 1 – Download ZIP
   1. Download the project as a .zip file.
   1. Extract it to a folder, for example:\
      ` `C:\ProjectAlice (Windows) or ~/ProjectAlice (macOS/Linux).

Option 2 – Clone with Git

1. git clone <your-repository-url> project-alice

### <a name="_m6hp5ndicqle"></a>**B. Place the Project in Your Web Server Directory**

If you’re using XAMPP (Windows/macOS/Linux):

1. Locate your htdocs folder, for example:

\
   ` `C:\xampp\htdocs\ (Windows) /Applications/XAMPP/htdocs/ (macOS)

1. Move the entire project folder into htdocs, e.g.:

\
   ` `C:\xampp\htdocs\ProjectAlice\

If you’re using WAMP:

- Place the folder inside C:\wamp64\www\ProjectAlice\

If you’re using MAMP:

- Place the folder in Applications/MAMP/htdocs/ProjectAlice/

If you’re using the built-in PHP server, you can keep the folder anywhere.

## <a name="_f35ko1jqzjfo"></a>**3. Configuration Steps**

Depending on how your project is structured, you may have one or more configuration files (e.g., config.php, env.php, .env). Adjust these to match your local setup.

1. Open the configuration file
   1. Look for a file named something like:
      1. config.php
      1. config/database.php
      1. .env
   1. This is where you typically set:
      1. Base URL (e.g., http://localhost/ProjectAlice/)
      1. Session settings or other environment options.
1. Set the Base URL (if applicable)

Example (inside config.php):\
\
` `$config['base\_url'] = '<http://localhost/ProjectAlice/>';


1. Check PHP Version
   1. Make sure your PHP version is 8.0+ as recommended for modern OOP features used in the project.


## <a name="_h9j1k29s3yo"></a>**4. How to Start the Game Locally**

You have two common options: using XAMPP/WAMP/MAMP or using the built-in PHP development server.

### <a name="_4wnk87w0o6nw"></a>**Option A: Run with XAMPP/WAMP/MAMP (Apache)**

1. Start the Web Server
   1. Open the XAMPP/WAMP/MAMP control panel.
1. Access the Game in Your Browser

Open your browser and go to: <http://localhost/ProjectAlice/>  

1. Start Playing
   1. You should see the game’s main screen (e.g., character selection for Thug, Doctor, or Occultist and the turn-based battle UI).
   1. Open the same URL in another browser window or another device on the same network if you want to test the 2-player setup.

### <a name="_vfo8hw2f5d2p"></a>**Option B: Run with PHP’s Built-In Development Server**

If you don’t want to configure Apache manually, you can use the built-in PHP server (good for quick local testing).

1. Open a Terminal / Command Prompt

Navigate to the project folder:\
\
` `cd path/to/project-alice

1. Start the PHP Dev Server

If your main entry point is index.php in the root:\
\
php -S 

localhost:8000

If your entry point is inside a public folder:\
\
cd public

php -S localhost:8000

1. Open the Game in Your Browser

Go to:  http://localhost:8000

1. Test the 2-Player Turn-Based Flow
   1. Open another tab or browser and go to the same URL to simulate a second player.
   1. The backend PHP OOP classes will handle turn order, HP updates, and skill effects while the frontend (HTML/CSS/JS) renders the battlefield and UI.
