# node_Express_API_Ajax

    Umuzi Remote work
    1. Syllabus
    2. Topics
    3. Workshops
    4. Projects
        Android with Kotlin Projects
            Constraint Layout Using Layout Editor
            Data Binding Basics
            Linear layout using the Layout Editor
            User Activity
        Androids
            Incremental Counter
            Information Page
        Angular Tutorial
        Assertive programming kata
        Bootcamp Writing Assignment
        Build your first personal website
        Capstone project
            Gmail Text Scraper
            Pair Stairs
            Spaced Repitition machine to help you remember what you read
            The Quizmaster
            build a Chrome Extension that measures time spent in meetings
        Consume Github API
        DAGs with Airflow
        Data-science-specifics
            MEDIUM: Cross-validation & Simple Linear Regression
            Dashboard Assignment
                EASY: Google Data Studio Assignment
                HARD: Live Dashboard Assignment
                EASY: Plotly Dashboard Assignment
                HARD: Webscraping and Live Dashboard Assignment
            Data Modelling Challenges
                HARD: Network Intrusion
            Data Visualisation Projects
                MEDIUM: Evolution of Linux Visualisation
                MEDIUM: Financial Services Use in Tanzania
            MEDIUM: Data Wrangling
            MEDIUM: Decision Trees
            Introduction to Jupyter Notebooks
            MEDIUM: K-Means Clustering Assignment
            Logistic regression
                MEDIUM: Predict breast cancer
                MEDIUM: Predict credit card approvals
            MEDIUM: Multivariate Linear Regression
            MEDIUM: Natural language processing
            MEDIUM: OOP for data science
            MEDIUM: Statistical Thinking
            Webscraping Assignment
        Distributed workloads with ZeroMQ
        Email random inspirational quote
        ExpressJS
        Game of life: Angular elements
        Git Basic Exercises
        Java Projects
            File IO + Logging + Errors
            Introduction to Spring Boot
                Introduction to Spring Boot - part 1
                Introduction to Spring Boot - part 2
                Introduction to Spring Boot - part 3
                Introduction to Spring Boot - part 4
            Java Generics
            Java collections
            Java data structures
            SQL Extended
        Level 1 programming katas
        Linux challenges
            Advanced Linux challenges
            Beginner Linux challenges
        Memory Game: rebuild using a modern web frontend framework
        Memory game in vanilla js
        Memory game using Angular Material
        Nodejs Challenges
            1: Node & File IO
            2 (alt): Node & mongoDB assignment
            3: Express, forms and templates
            4: Expose a JSON API
            Add a little Ajax
            Node & SQL assignment
        OOP Excercises
            Animals
                Animals Part 1. OOP basics
                Animals Part 2. Adding Tests
            Bank Accounts
            Dice
            Person
        Pre bootcamp challenges
        Python projects
            Database migrations with SQLAlchemy
            Django - exposing a REST api with a real database
            Getting to know Python
            Python and Kafka
            Python and MongoDB
            Python and Spark
            create a REST api to interact with actual database
            expose a simple JSON rest api
        RabbitMQ
        SQL
        Semitone Challenge
            1. semitone difference - basic algorithm
            1. Make a simple GUI
            3. Advanced algorithm
            4. A gui that is more...awesome
            Add Redux to your semitone game
        Test Driven Development
            Password Checker
                Add logging to password checker
                password-checker
            MEDIUM: Resturaunt menu system
            EASY: factorials
            MEDIUM: lots and lots of tdd katas
            MEDIUM: recursive search
            EASY: simple-calculator part 1
            MEDIUM: simple-calculator part 2
            string-calculator
            HARD: ten-pin bowling scoring system
        Validating user input for web
        consuming APIs with the requests module
        iOS Mobile
            Codable, File Manager, URL
            Drag and Drop, Multithreading and Delegation
            More Swift, Gestures and Animations
            Multithreading Layout and Other Functionality - Animated Set
            Multithreading Layout and Other Functionality - Graphical Set
            Swift and More
    5. Katas
    6. Department Processes
    Code Review Feedback Notes
    Contact
    Credits
    How to Contribute
    Online Learning and bootcamp

More

    Github repo
    Credits

Edit this page
Umuzi Tech Department > Projects > Nodejs Challenges > Add a little Ajax
Add a little Ajax
Story points 	8
Tags 	node ajax
Hard Prerequisites 	
TOPICS: Introduction to Ajax
PROJECTS: Express, forms and templates
PROJECTS: Expose a JSON API
PROJECTS: Node & File IO

There is no need to create a new git repo for this code submission. This is a continuation of your previous work.
a new static resource

Create a new HTML static web page just like the form page you made before. You can even copy-paste your form’s html here. Usually copy-pasting pieces of code is a bad idea, this time it’s ok.

Serve your new page from the following url: http://localhost:[YOUR_PORT]/single-page-app
form submissions

The submit button should make an AJAX call to the addNewVisitor. It should not redirect the user to any kind of “thank you” page
list existing visitors

Create an html table on the same page (on your single page app). Use an ajax call to /viewVisitors to populate the table
delete visitors, and update the table

Add a “delete” button to each line of the table. When the user clicks “delete” then

    make a request to /deleteVisitor:id and delete that visitor
    update the information displayed in the table

Also make sure that if you create any new visitors then they are visible in the table
Resources

    TOPICS: Introduction to Ajax

RAW CONTENT URL



