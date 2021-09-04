# Tres Dia CONNECTING TO A MYSQL DATABASE

Today's Reflection: Mark built out the artistapi backend showing us how to use sql and dapper.  Um, very new and something else I need to memorize as far as syntax goes, but the concepts are the same as far as how the gets, posts, puts & deletes work.  
Tasked with building a castles & knights back-end for the afternoon challenge.  Didn't quite finish.
https://github.com/BoiseCodeWorks/late-summer21-artistapi.git 
https://github.com/ShereneC/KnightsTale.git

## In a SQL table, what is the difference between information in a row and information in a column?

### The row contains all information for one object of the model or class.  The columns contain each of the properties contained on the model.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

### CREATE TABLE [characters](
  id int 
  name VARCHAR(255)
  age VARCHAR(255)
  description(255)
)

## What is the difference between the following statements:

### Delete from means you are going to delete objects or instances from the table.  Drop table means you are going to delete all instances in the table and the table itself -  be careful with that one!

Afternoon Code: https://github.com/ShereneC/KnightsTale.git