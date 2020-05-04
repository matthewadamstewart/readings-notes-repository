# Readings-Notes-Repository

## Class 14 notes for my Readings in Code Fellows 301 Course

[Back To Main](https://matthewadamstewart.github.io/readings-notes-repository/)


### Reading 14a
[Essential: Database Normalization Explained in Simple English](https://www.essentialsql.com/get-ready-to-learn-sql-database-normalization-explained-in-simple-english/)

> The main idea with this is that a table should be about a specific topic and only supporting topics included

* This Minimizes duplicate data
* Helps avoid data modification issues
* Simplifies Queries
* 
![Example before normalization](https://www.essentialsql.com/wp-content/uploads/2014/06/Intro-Table-Not-Normalized.png)

* This slows performance and increases resources needed for database
* When data needs to change the duplicated data now lives in multiple places causing issues with trying to update or modify it all at once 
    * Affects Update, Deleting, Inserting, and also causes Search and Sort Issues


### Reading 14b

> Project Ideas
> What ideas do you have for projects? What would your model be that you can control and update the view with? What API(s) could you use to make this a reality?

> Take a look at this [repo](https://github.com/toddmotto/public-apis) for inspiration about APIs you could use.

> For those of you who were in 201, be sure to look back at the project discussion assignment from that course and see if there is anything from there that was not done that could be carried forward as an idea for this class.

I am very excited about using a name generation api for the fealty generator idea I purposed in 201.

[name generator api](https://en.namefake.com/api)

[save a file to a document as a Blob using this API](https://developers.google.com/web/updates/2011/08/Saving-generated-files-on-the-client-side)