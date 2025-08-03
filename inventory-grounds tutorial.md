# inventory-grounds tutorial 🍵
🌱 What We're Building 🌱

This tutorial will guide you through creating a simple inventory management tool. It's perfect for anyone learning PHP and MySQL because it focuses on a core concept: connecting a web page to a database. The goal is to build something simple, functional, and user-friendly.

In this project, we'll practice:

    Connecting to a database with PHP.

    Fetching and displaying dynamic data.

    Using secure, accessible HTML to present that data.

    The joy of building a full-stack app from scratch.

🛠️ What It Does

Our inventory program lets you manage a list of products and categorize them.

    You can select a workshop (category) from the sidebar to filter the project list.

    The main table dynamically displays all the projects for that specific workshop.

    You'll see each project's code, name, price, and description.

    You'll also have buttons to Modify or Delete each project.

🧠 What You'll Learn

This is a great stepping stone for anyone wanting to get into back-end development. You'll learn:

    How to write PHP code to interact with a database (using PDO for secure connections).

    How to structure a simple MySQL database with tables and relationships.

    The importance of dynamic data display, where your HTML is built with real information from the server.

    How to build a user interface that is both beautiful and accessible.

🧑‍💻 How The Code Works

The magic of this program happens behind the scenes.

    When you click a workshop link, the page sends a request to the server with a category_id in the URL.

    The PHP code on the server-side receives this ID and uses it to perform a database query.

    The database sends back all the relevant project data.

    The PHP code then takes this data and builds the HTML table dynamically, populating each row with a project's details.

The end result is a clean, organized web page that feels simple to the user, but is powered by a cozy, robust back-end system.

♿ Accessibility Notes

I believe accessible code is cozy code. Here's how we made sure this project is screen-reader friendly:

    The page includes a "Skip to main content" link so keyboard users can navigate quickly.

    The HTML table uses proper <thead> and <tbody> tags to give the table structure.

    Buttons to modify or delete projects include a clear aria-label so a screen reader user knows exactly what each button does.

💡 Want to Build It?

Ready to build your own inventory management system? Check out the source code and make it your own!

👉 [ View the GitHub Repo](https://github.com/duh-nicole/inventory-grounds)

Or remix it into your own unique vibe!

📝 Written with ☕ and chill at [Softstack Studios](https://github.com/duh-nicole)

