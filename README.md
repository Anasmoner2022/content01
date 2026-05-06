## `go-reloaded`

### A simple tool for text completion, formatting and auto-correction.

**🔴 Mandatory** / **Go** / **1 student** / **1 week**

Your very first project as a student. You will freshen up on your knowledge from the piscine by creating a very simple tool for text completion, formatting and auto-correction. You will learn to process command line arguments and the basics of string manipulation. You will learn to read from and write to the file system.

[View project](https://github.com/01-edu/public/tree/master/subjects/go-reloaded)

## `tetris-optimizer`

### Arrange tetriminos into the smallest possible square.

**🟢 Open** / **Go** / **1 student** / **1 week**

You will open and parse a list of tetriminos from a file. You will need to validate that the teriminos are valid, and create an algorithm which will arrange them into the smallest possible square.

[View project](https://github.com/01-edu/public/tree/master/subjects/tetris-optimizer)

## `Git`

### Learn advanced git skills.

**🟡 Optional** / sh / 1 **student** / **1 week**

This project is designed to introduce you to the world of version control and collaboration using **Git**. Git is a powerful and widely used tool for tracking changes in your projects, collaborating with others, and ensuring the integrity of your code.

[View project](https://github.com/01-edu/public/tree/master/subjects/git)

---

## `atm-management-system`

### Add new features to an ATM management system, as part of an existing C project.

**🟢 Open** / **C** / **1 student** / **1 week**

You will expand an existing C project by adding features to an ATM management system. You will learn about the fundamentals of C, Makefiles, data structures, memory management, pipes and child processes. Optionally you may implement a lightweight database: SQLite

[View project](https://github.com/01-edu/public/tree/master/subjects/atm-management-system)

## `ascii-art`

### Convert a string into a graphic composed of ascii characters.

**🔴 Mandatory** / **Go** / **2-3 students** / **1 week**

You will convert a command line argument into a multi-line graphic using only ascii characters. You will learn about parsing files. You may optionally accept command line flags to add bonus features to your project.

[View project](https://github.com/01-edu/public/tree/master/subjects/ascii-art)

---

## `ascii-art-color`

### Colour the ascii-art project.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a command-line flag to your ascii project which will specify the colour of the output. You'll learn about terminal formatting.

## `ascii-art-output`

### Write the ascii-art project to a file.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a command line flag to your ascii project which will specify a file path. You'll write the output to that file.

---

## `ascii-art-fs`

### Add some flair to the ascii-art project.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a command line flag to your ascii-art project which will specify a path. You'll read the graphic style from the file at that path to create a different appearance.

## `ascii-art-justify`

### Position the ascii-art project nicely in the terminal.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a command line flag to your ascii-art project which will specify alignment. You will need to know how wide the terminal is, so as to position the graphic correctly.

---

## `ascii-art-reverse`

### Reverse engineer the ascii-art project.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will need to reverse engineer your ascii-art project. You will accept a command line flag which specifies a path to a file. You'll open that file which contains an ascii-art project, and print its raw string equivalent to the output. Don't forget to validate the file.

## `push-swap`

### A sorting algorithm and checker

**🟢 Open** / **Go** / **2-3 students** / **2 weeks**

You will create a push-swap program which accepts a list of integer values. Your program will sort the values using two stacks, which can each be rotated, and values can be popped from the top of one stack onto the top of the other. Each rotation or pop action will be written to the standard output. You will also create a checker program which also accepts a list of integer values, as well as a list of actions from your push-swap program. It will simply output OK or KO depending on whether the actions properly sort the list. Your push-swap algorithm must attempt to sort the list in the smallest number of moves.

[View project](https://github.com/01-edu/public/tree/master/subjects/push-swap)

---

## `ascii-art-web`

### A web version of ascii-art.

**🔴 Mandatory** / **Go** / **2-3 students** / **1 week**

Build upon your ascii-art project, by building a web server which generates HTML to display the project in a web browser. You will learn REST methods: GET and POST, and implement basic error handling with appropriate HTTP response codes. You'll describe your project in a readme with markdown.

[View project](https://github.com/01-edu/public/tree/master/subjects/ascii-art-web)

## `ascii-art-web-export-file`

### More features into ascii-art-web.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

Enhance the ASCII-Art-Web project by implementing an export feature that allows users to save their ASCII art creations in various file formats. This functionality will enable users to download their artwork as plain text files, images, or even PDF documents, providing greater flexibility in how they can share and preserve their ASCII masterpieces. Additionally, incorporate options for users to customize the export settings, such as choosing the file name, selecting the desired file format, and adjusting any relevant export parameters to ensure the best possible representation of their ASCII art outside the web application. 

[View project](https://github.com/01-edu/public/tree/master/subjects/ascii-art-web/export-file)

---

## `ascii-art-web-stylize`

### More features into ascii-art-web.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

Develop a comprehensive web application using Go that serves as a graphical user interface for the ASCII-art project. This web server will allow users to interact with the ASCII-art functionality through a user-friendly interface. Users can input their desired text, select from various banner styles, and receive the resulting ASCII art representation. The application will handle these requests using HTTP POST methods, ensuring secure and efficient data transmission between the client and server.

[View project](https://github.com/01-edu/public/tree/master/subjects/ascii-art-web/stylize)

## `ascii-art-web-dockerize`

### More features into ascii-art-web.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

Containerizing the web server using Docker, which significantly enhances its portability and deployment efficiency. This process involves creating a Dockerfile, building a Docker image, and running the application in a container. By doing so, the project becomes more easily transferable across different environments, ensuring consistency in development, testing, and production stages. Additionally, containerization simplifies scaling and management of the application, making it more robust and adaptable to various deployment scenarios.

[View project](https://github.com/01-edu/public/tree/master/subjects/ascii-art-web/dockerize)

---

## `my-ls-1`

### A recreation of ls

**🟢 Open** / **Go** / **2-3 students** / **1 week**

You will recreate ls, which is a command for listing files in a Unix operating system. Your recreation will implement at least the -l, -R, -a, -r and -t flags. You will learn about the file system, access control lists, symbolic files, parsing command line arguments, and accurately displaying data.

[View project](https://github.com/01-edu/public/tree/master/subjects/my-ls)

## `net-cat`

### Create a group chat application where multiple users can connect to a server

**🟢 Open** / **Go** / **2-3 students** / **1 week**

In this project, you will create a group chat application that works like the NetCat utility. The chat will have a server that multiple clients can connect to and send messages in real-time. Each user will have a unique name, and messages will show who sent them and when. If someone joins or leaves the chat, everyone else will be notified. New users will also be able to see earlier messages when they join. If no port is specified, the chat will run on port 8989 by default.

[View project](https://github.com/01-edu/public/tree/master/subjects/net-cat)

---

## `groupie-tracker`

### A full stack project for displaying information about musical acts.

**🔴 Mandatory** / **Go** / **2-3 students** / **2 weeks**

You will create a RESTful API with multiple endpoints, which serves information about musical acts. You will use HTML, styling, and basic JavaScript to create a website to visualise the  JSON data returned by the API. You will learn about events/actions, data manipulation, and relationships. Your website must have a good user experience.

[View project](https://github.com/01-edu/public/tree/master/subjects/groupie-tracker)

## `groupie-tracker-filters`

### Filters for groupie-tracker.

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add filters to groupie-tracker, to enable users to filter by creation date, first album date, number of band members and locations of concerts. You will implement at least one range filter, and one checkbox filter.

---

## `groupie-tracker-geolocalization`

### Geolocation for groupie-tracker

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a geolocation feature to groupie-tracker, which will display the locations of concerts on a map. You will convert the city to coordinates. You will learn about third-party map APIs.


## `groupie-tracker-vizualisations`

### Usability for groupie-tracker

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will improve groupie tracker to ensure that its user experience follows good design principles, defined by Shneiderman’s Eight Golden Rules.

---

## `groupie-tracker-search-bar`

### Search for groupie-tracker

**🟡 Optional** / **Go** / **2-3 students** / **1 week**

You will add a search bar to groupie-tracker, which enables users to find artists, concert locations, band members etc. It must be possible to find an entity based on any of its attributes.


## `lem-in`

### A pathfinding algorithm.

**🔴 Mandatory** / **Go** / **3-4 students** / **2 weeks**

You will create a path-finding algorithm to move ants from one part of a colony to another.  You will parse a file to interpret the layout of the colony, including the position of rooms, and the connections between them. Only one ant may be in a room at a time, so you must control the flow of traffic. You must identify the most efficient route or routes. Your data structure and algorithm choices will be important, to ensure that your algorithm can scale to giant colonies. You may optionally create a visualiser.

[View project](https://github.com/01-edu/public/tree/master/subjects/lem-in)

## `forum`

### A full stack web forum project

**🔴 Mandatory** / **Go** / **4-5 students** / **4 weeks**

You will create a forum which enables users to register, create posts, comment, like and dislike. You will manage access control to ensure that non-registered users can only view the forum. It should also be possible to filter posts. You will create a SQLite database with SELECT, CREATE and INSERT statements. An Entity Relationship Diagram is highly recommended. You must authenticate users and manage sessions. You may optionally use bcrypt to encrypt passwords, and UUID. Your project must use Docker, and you will learn about compatibility/dependency, containerizing an application and creating images.

[View project](https://github.com/01-edu/public/tree/master/subjects/forum)

## `forum-authentication`

### SSO for the forum project.

**🟡 Optional** / **Go** / **4-5 students** / **1 week**

You will implement new authentication methods to the forum project, to enable users to sign in or register with their Github or Google accounts. You may optionally add other SSO providers like Facebook, LinkedIn etc. You will learn about SSO and IAM.

---

## `forum-image-upload`

### Image upload for the forum project.

**🟡 Optional** / **Go** / **4-5 students** / **1 week**

You will enable users to upload images along with their posts in the forum project. You must support at least JPEG, PNG and GIF. You will limit file size, and should be cautious about image dimensions.

## `forum-security`

### Security for the forum project

**🟡 Optional** / **Go** / **4-5 students** / **1 week**

You will secure your forum project, by implementing HTTPS with an SSL certificate, implementing rate limiting, encrypting passwords, and persisting session states on the server. Optionally, you may decide to password protect your entire database. You will learn about cipher suites, certificate authorities, encryption, and UUID.

---

## `forum-moderation`

### Moderation for the forum project

**🟡 Optional** / **Go** / **4-5 students** / **1 week**

You will add moderation capabilities to the forum project. You will create admin and moderator roles. Moderators will be able to approve posts before publication, and delete existing posts. Admins will be able to appoint moderators. You will learn about more advanced authorization.

## `forum-advanced-features`

### Advanced features for the forum project

**🟡 Optional** / **Go** / **4-5 students** / **1 week**

You will add notification features to the forum project, to alert users when their posts have been commented on, liked or disliked. You will create an activity page to enable users to see what posts and comments they have created, and what they have liked and disliked. You will enable users to delete or edit comments and posts. You will learn some more advanced SQL.
