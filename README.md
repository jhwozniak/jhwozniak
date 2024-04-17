# Welcome to my personal code repository!
## About me
I am an experienced banker, who for the past 18 years has been managing complex investment finance projects for large corporate clients. 
In October 2022 I decided to take a career break in order to study software development and combine it with my knowledge of finance. 
I have a strong interest in **back-end, system design and databases**. What really drives me is learning how modern software is organized and how it works under the hood of the user's interface. 

## Skills
- Creativity
- Analytical thinking
- Communication
- Project management

## Technology
- **Languages:** Java, Python (Flask, Django), SQL
- **Databases:** SQL Oracle Developer, MS SQL Management Studio, SQLite, relational databases
- **Frontend:** HTML, CSS (Bootstrap), JavaScript (React)
- **Tools:** Visual Studio Code, Eclipse, Linux/Bash, Power BI, Excel

## My projects
Check out some of my noteworthy projects:
### Data:
- [FX](https://github.com/jhwozniak/Data-Analytics/tree/main/FX) is a **Python** script, which fetches currency quotations using API of National Bank of Poland, stores full- and user-filtered data in CSV files, displays basic statistics and downloads data daily at 12:00pm. Works with Pythons' statistics and schedule libriaries.
- [Seven-day-average](https://github.com/jhwozniak/Data-Analytics/tree/main/seven-day-average) is an app in **Python** which is using a New York Times API repository of live, cumulative COVID data to calculate new daily cases, create a 7-day average, and compare this week’s average to the previous week. During implementation it was interesting to learn how to read CSV files and how to practically use lists and dictionaries in Python.
- [DNA](https://github.com/jhwozniak/Data-Analytics/tree/main/dna) is a desktop app in **Python**, which identifies a person based on their DNA. It reads a file with suspect's DNA sample in form of
a sequence of AGCT molecules arranged into a particular shape. Then, it searches for a matching profile in csv database of DNA samples. The most difficult but also enjoyable part of this task was playing with lists and searching for particular string of molecules saved in a text file.
  
### Harvard CS50 "Web programming with Python and JavaScript":
- [Mail](https://github.com/jhwozniak/Harvard-CS50web/tree/main/mail) is an email client that makes API calls allowing users to send and receive emails. It was written in **Python's Django web framework** as a single page application thanks to **Java Script**. Feel free to examine scripting [here](https://github.com/jhwozniak/Harvard-CS50web/blob/main/mail/mail/static/mail/inbox.js). You can watch online presentation [here](https://youtu.be/mlszsqSzGn0). 
- [Commerce](https://github.com/jhwozniak/Harvard-CS50web/tree/main/commerce) is an online eBay-like auction site. Users can bid on film/music/theatre posters, add own listings, comment and observe interersting listings in a watchlist. The app was written in **Python** and it uses **Django web framework**. I designed a data model with a "class single responsibility" principle. There are six interrelated classes (Django models) like Listing, Watchlist, User, Category etc. arranged in star schema around a central Bid model. In this case I used Django's default SQLite database. Frontend was designed with use of HTML,CSS and Bootstrap. You can watch presentation of the project here: https://youtu.be/bvGDxqsqZ-I    
- [Wiki](https://github.com/jhwozniak/Harvard-CS50web/tree/main/wiki) is a **Python** web app based on **Django framework** based on Wikipedia. It is an online encyclopedia, where you can browse, edit and create new encyclopedia entries. You can watch the presentation video here: https://youtu.be/pqB1Wuguz_w
- [Search](https://github.com/jhwozniak/Harvard-CS50web/tree/main/search) mirrors front-end for Google Search, Google Image Search, and Google Advanced Search. It was based around analysis of Google's HTTP GET parameters passed in the URL at each search. Created withe the use of **HTML & CSS** for styling a'la Google. You can watch project's presentation here: https://youtu.be/g3Tbqesk6rs 
    
### Harvard CS50 "Introduction to Computer Science":
- [Finance](https://github.com/jhwozniak/Harvard-CS50/tree/main/finance) is a web app via which you can manage portfolios of stocks. This tool allowed users to check real stocks’ actual prices and portfolios’ values, it also let them buy and sell stocks by querying for stocks’ prices. The app was coded in **Python (Flask, Jinja), HTML, CSS, JavaScript**. It also uses Bootstrap for boosting the interface, SQLite for a database and API of IEX Cloud for checking actual stock prices.
- [The Family Clinic](https://github.com/jhwozniak/Harvard-CS50/tree/main/project) is a web app facilitating work of an imaginary health clinic. It works in patients' as well as in doctors' mode. Tech: **Python (Flask, Jinja)**, SQLite (relational databse), HTML, CSS, Javascript, Bootstrap. Online presentation of the project can be accessed here: https://www.youtube.com/watch?v=vnTr_Kie560
- [Homepage](https://github.com/jhwozniak/Harvard-CS50/tree/main/homepage) is a simple homepage prepared with the use using **HTML, CSS & JavaScript**. It contains several sub-pages and has some dynamic features like buttons, navigation bar and carousel made with the use of Bootstrap and JavaScript.
- [World Cup](https://github.com/jhwozniak/Harvard-CS50/tree/main/world-cup) was an app written in **Python**, simulating the FIFA World Cup. The idea was to simulate N times (ideally high number eg 1000) the football tournament by simulating each game and round. Each game was concluded with a winner which then had to be recorded in some convenient data structure. Getting a winner of a game based on simulating probability based on csv file with list of teams and their actual FIFA rankings. After running N simulations, the program displays sorted stats for each team, which then can be treated as a prediction tool of winning next World Cup torunament.   
- [Readability](https://github.com/jhwozniak/Harvard-CS50/tree/main/readability) is an application written in **Python**. It computes the approximate school grade level needed to comprehend some text. 
- [Speller](https://github.com/jhwozniak/Harvard-CS50/tree/main/speller) is a program in **C** that spell-checks a text file, using a hash table. It required structuring an efficient hash table, dealing with pointers and avoiding memory leaks.
- [Filter](https://github.com/jhwozniak/Harvard-CS50/tree/main/filter-less) is a desktop app written in **C** which required working out several algorithms to modify image files.
- [Runoff](https://github.com/jhwozniak/Harvard-CS50/tree/main/runoff) was an interesting assignment in **C**, in which I implemented a program that runs a runoff election. It required tinkering with multidimensional arrays and searching algorithms.
- [Recover](https://github.com/jhwozniak/Harvard-CS50/tree/main/recover) was another interesting program written in **C**, in which it recovers JPEGs from a forensic image i.e. bit-by-bit copy of a camera card. The task was to recover 50 JPG pictures deleted from a RAW card of a digital camera. It turns out that first three bytes of each JPG file are it's signature and they stay the same for each JPG. So the task was to scan the RAW file byte-by-byte and search for these files, remembering about organisation of file pointers.    
- [Yellow fish](https://github.com/jhwozniak/Harvard-CS50/tree/main/scratch) was a simple and short game in **Scratch**. Just upload the file on [this page](https://scratch.mit.edu/) and enjoy!
  
### Polish-Japanese Academy of Information Technology (PJATK) postgraduate studies "Information systems, software and databases":
- [Database programming](https://github.com/jhwozniak/PJATK/tree/main/PWB) is a repository of various **SQL scripts**, which I prepared during semester. They cover basic as well as advanced SQL queries, RDB normalization problems, indexes, PL/SQL scripts, cursors, views, sequences, procedures, triggers and object-relational databases.
- [Database design](https://github.com/jhwozniak/PJATK/tree/main/PRD) contains selected **data-modelling** solutions in form of [ER diagrams](https://github.com/jhwozniak/PJATK/tree/main/PRD/diagramy%20ER) prepared during semester for specific requirements. You can also run my final semester project [here](https://github.com/jhwozniak/PJATK/tree/main/PRD/projekt). It is a database application in old-school MS Access technology: a simple CRM system for imaginary healthcare clinic. It allows managing clients, visits and doctors in real time and is based on 5-entity star model.
- [Operating systems](https://github.com/jhwozniak/PJATK/tree/main/SOP) contains various projects which I submitted when taking Operating Systems module. They mainly consist of **Bash Shell scripting on Linux** as well various assignments in process and memory management.
- [Flower Shop](https://github.com/jhwozniak/PJATK/tree/main/WDP4_WJ_PD4135/src/zad3) is a desktop app in **Java** which facilitates purchase of flowers in a flower shop. It is a good practice in objected-oriented programming as it required me to structure classes using inheritance and to implement methods with the use of lists.
- [Writer/Reader](https://github.com/jhwozniak/PJATK/tree/main/WDP5_WJ_PD4135/src/zad2) is a desktop **Java** application which manages the process of executing multiple threads making operations on a data file. 
- [Anagrams](https://github.com/jhwozniak/PJATK/tree/main/PRA1_WJ_PD4135/src/zad3) is a **Java** application which loads words from a text file and finds their anagrams. A practical implementation of hash map with key-value pairs, with a value being a list of unique anagrams of a given word.
- [Simple Editor](https://github.com/jhwozniak/PJATK/tree/main/PRA2_WJ_PD4135/src/zad3) is a simple text editor in **Java**, in which you can create and edit own text file. It was developed with use of Java Swing as a frame for graphical interface.
- [Bookstore](https://github.com/jhwozniak/PJATK/tree/main/PRA3_WJ_PD4135/src/zad3) is a practical example of model-view-controller concept in **Java**. The program reads book records from a file, displays them using Java Swing in GUI and then accepts user's interactions like change in title, book's cover or price. The program required implementation of the AbstractTableModel interface.
- [Calculator](https://github.com/jhwozniak/PJATK/tree/main/PRA4_WJ_PD4135/src/zad1) is a short math calculator implemented in **Java** without the use of "ifs" or "switches". The user inputs two numbers and a required arithmetic operation in the command line. The program then searches a hash map for a matching key (arithmetic operation) and a value (a class implementing required interface).
- [Travel Office](https://github.com/jhwozniak/PJATK/tree/main/PRA5_WJ_PD4135/src/zad1) is a database application in **Java** simulating managing of travel offers by a travel office. The offers are loaded from external files, translated into chosen output languages, then inserted into database and finally displayed in GUI window. The project required practical use of OOP (different Java classes), object lists, relational database (SQLite) and GUI (Java Swing).
- [Students](https://github.com/jhwozniak/PJATK/tree/main/PJATK_App) is a .NET desktop application allowing to store and edit students' records. It was written in **C#** and uses MS SQL Server for database management and Windows Forms for graphical interface.

## Getting in touch
You can reach me at: jakubhenrykwozniak@gmail.com




