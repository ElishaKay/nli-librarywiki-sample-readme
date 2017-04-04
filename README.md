Welcome friends to the Github Repo of NLI's librarywiki project.

A live demo is available here: http://84.95.208.20:14180/index.php/000017959

Screenshots:

<img src="ben-gurion.PNG">


- [Features](#features)
- [Getting Started](#getting-started)
- [Querying the Database](#querying-the-database)
- [Project Structure](#project-structure) 
- [License](#license)




Features
--------


- **Local Authentication** using Email and Password


Getting Started
---------------

The first steps is to make set up your local environment.

1) Download python version 3.6.1

https://www.python.org/downloads/

2) Download Pycharm IDE

https://www.jetbrains.com/pycharm/download/#section=windows

3) Clone the repository and install the dependencies via Pycharm:

```bash
# Get the latest snapshot
git clone https://github.com/AdirShemesh/LibraryWiki/

# Install Dependencies via Pycharm IDE

<img src="pycharm.png">

# Install Dependencies via Pycharm IDE



```


<hr>

Querying the Database
---------------

To query the database, navigate to:

http://84.95.208.20:7474/browser/




Project Structure
-----------------

| Name                               | Description                                                  |
| ---------------------------------- | ------------------------------------------------------------ |
| **app**/                           | This module crawls trough NLI's data and transforms it into linked data, stored in the DB (neo4j).                                                                                         |
| **mediawiki**/                     | This module takes care of taking data from the DB (neo4j) and creating wiki pages in the mediawiki.                                                                                      |
| **tests**/                         | Just tests                                                   |
| **tests**/add_authorities.py       | Testing                                                      |


<img src="LibraryWiki-files.PNG">


**Note:** lorem ipsum


