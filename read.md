Logs Analysis Project 

About 
 This is the first project for the Udacity Full Stack Nanodegree.
 In this project we have already a database and we work on it to get some informations. 
The database contains newspaper articles, as well as the web server log for the site.

To run this project we need:
Python3
Vagrant and virtualBox. We launch vagrant VM by "vagrant up" command on the terminal and then "vagrant ssh". 
We load the data by connect the database using psql -d news -f newsdata.sql 
We make some SQL queries to get the number of logs and arrange them by the number of logs so we use 'count' as views . 
The second part is to know the most authers that their articles have the most views number. And the last part is to know the error rates.