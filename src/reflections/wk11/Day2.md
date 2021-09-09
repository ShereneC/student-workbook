# Dos Dia - MYSQL RELATIONSHIPS

Today's Reflection: Mark went over the weekend's assignment: Blogger.  It was helpful.  However, he would not go over the Edit Account - said it was just like edit blog.  However, I tried making it this weekend and modeled it after blog and it would not work - kept getting an error that there was no "instance of the object."  So I'm assuming it was not finding the "account."  but I don't know what I did wrong - will need to ask for help on that in tutoring this week.  
We then went through a many to many relationship - I understand the concept, but the sql statement is confusing.  Will work on trying to do that successfully in the afternoon challenge: Contracted.
My Blogger code:
https://github.com/ShereneC/Blogger.git
Mark's example code:
https://github.com/BoiseCodeWorks/late-summer21-blog-CSharp.git

## What is the difference between a primary key and a foreign key

### A primary key is an id that is the id of that particular instance of a class. A foreign key is one that is assigned to it through having a relationship - for example, a creatorID is the id of an account, but it is assigned to a blog through the foreign key.

## What is an Alias?

### When you are joining two tables that have a property key in common, you must make up new names on the fly and those are called aliases.  

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

###       string sql = @"
      SELECT
        a.*,
        p.*,
        dp.id AS doctorpatientId
      FROM doctorpatients dp
      JOIN patients p ON p.doctorId = p.id
      JOIN accounts a ON b.creatorId = a.id
      WHERE p.accountId = @id
      ";

Afternoon Code: https://github.com/ShereneC/contracted.git