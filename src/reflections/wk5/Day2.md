# Dos Dia - USING AN ORM TO INTERACT WITH A DATABASE

Today's Reflection: Today we created a real database location using MongoDb - Mark set up the Greg's List app to connect to the MongoDB database.  
Concepts:
MongoDB
Mongoose - Object Relational Mapper


## What are the three types of relationships?

### One to One, One to Many, Many to Many

## What are the benefits of the traditional linking of relationships instead of Embedding

### I'm not sure why, but it keeps file size lower, and its able to pageinate them better.

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

### If N and M are close in number then use Two-way embedding, if M is much larger than N, use one-way embedding.  The challenge is if both categories are frequently changing, there will be more updating to do in the database.

Afternoon Code: https://github.com/ShereneC/late-summer21-gregslist-node.git
                https://sherenec.github.io/late-summer21-gregslist-node/ (Pages)