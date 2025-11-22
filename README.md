# LaForant - Valorant Frontend Mockup

LaForant is a responsive web design project that replicates the visual style and user experience of the official Valorant game website. This project serves as a showcase of fundamental frontend development skills, specifically focusing on raw DOM manipulation, responsive layout design without heavy frameworks, and interactive UI components using jQuery and vanilla JavaScript.

Built in 2020/2021 as part of my Human & Computer Interaction coursework at BINUS University.

### Features

  * **Interactive Agent Roster:** A dynamic carousel/slider allowing users to browse through different game characters (Agents) and view their specific details.
  * **Client-Side Form Validation:** A robust pre-registration form that validates user input (email format, password strength, age verification) in real-time using JavaScript before submission.
  * **Responsive Navigation:** Fully functional navigation bar featuring dropdown menus for desktop and a collapsible "burger" menu for mobile devices.
  * **Immersive UI/UX:** Usage of CSS animations and transitions to create engaging hover effects and smooth scrolling experiences.
  * **Multi-Page Layout:** distinct pages for Home, Agents, Maps, and System Requirements, linked together to form a complete site structure.

### Tech Stack

  * **Markup:** HTML5
  * **Styling:** CSS3 (Custom layouts, Flexbox, CSS Grid)
  * **Scripting:** JavaScript, jQuery 3.6.0
  * **Assets:** FontAwesome (Icons), Google Fonts (Poppins)

### Project Structure

```
LaForant-Frontend/
├── asset/               # Game assets (Agent images, Logos, Backgrounds)
├── css/                 # Stylesheets for individual pages
│   ├── style-home.css
│   ├── style-agent.css
│   └── style-pre_reg.css
├── html/                # Main HTML pages
│   ├── home.html        # Landing Page
│   ├── agents.html      # Character Roster
│   ├── maps.html        # Map Showcase
│   └── pre-regis.html   # Registration Form
├── js/                  # JavaScript logic
│   ├── script-home.js   # Homepage interactivity
│   ├── script-navbar.js # Responsive navigation logic
│   └── script-pre_regis.js # Form validation logic
└── README.md
```

### How to Run This Project

Since this is a static frontend project, no server or database installation is required.

1.  **Clone the repository**

    ```bash
    git clone https://github.com/riopramana21/LaForant-Valorant-Frontend-Mockup-.git
    ```

2.  **Launch the Application**

      * Navigate to the `html` folder.
      * Open `home.html` in any modern web browser (Chrome, Firefox, Edge).

### Demo Screenshots

*(To be added...)*

### Security & Best Practices

  * **Input Validation:** Strict client-side validation is implemented to ensure data integrity (e.g., preventing submission if passwords don't match or if the email format is incorrect).
  * **Code Separation:** Clear separation of concerns is maintained by keeping HTML structures, CSS styling, and JavaScript logic in distinct directories.
  * **Semantic HTML:** Usage of semantic tags (`<header>`, `<nav>`, `<section>`, `<footer>`) to improve accessibility and SEO structure.

### Future Improvements

  * **Framework Migration:** Refactor the codebase to use a modern frontend framework like React.js or Vue.js for better component reusability.
  * **Backend Integration:** Connect the Pre-registration form to a real backend (Node.js/Laravel) to store user data.
  * **API Integration:** Fetch agent and map data dynamically from the official Riot Games API instead of hardcoding content.
