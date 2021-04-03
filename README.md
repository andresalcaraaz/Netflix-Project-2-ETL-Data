# Netflix-Project-2-ETL-Data



Project Overview: ETL

The goal of the project is to take the role of a data engineer tasked with building a database that meets certain specifications.
Design of the database using a provided requirements file and data tables from IMDB.

 Database Requirements
An actors table with unique actors and actress' names that also contains a numerical field for age and a boolean field to identify if the actor or actress is currently alive, deceased, or unknown.
A film table that contains a character field for the original title, a numerical field for the average critic rating, a character field for the type of film (movie, television show, etc.) and a datetime field that has the runtime of the film in HH:MM (hours then minutes, separted by a colon) format. In addition to the required fields, there should be additional fields for other relevant metadata.
A producers table that contains only producer's names and links to the film table.
A characters table with unique character names that links the actors and film tables together.