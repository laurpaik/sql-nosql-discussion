![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

# Discussion: Relational and Non-relational Databases

## Objectives

By the end of this, developers should be able to:

-   Identify use cases where relational or non-relational databases are
    appropriate.
-   List three strengths of relational databases.
-   List three strengths of non-relational databases.

## Introduction

You should have read the following:

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

Take five minutes to review these readings. Just skim to refresh your memory.
Then, take fifteen minutes to share your notes with your classmates and to
prepare for discussion. Discuss with each other and attempt to answer the
following questions.

## Discussion

1.  According to Sarah Mei, what are the benefits of using MongoDB?
  2. Good if it scales horizontally instead of vertically
  3. Sharding
  4. If it's non-relational, then you can get everything back all at once!
    5. faster
  5. Large database
  6. Caching (data not changing)
  7. Flexibility
1.  Why wasn't MongoDB a good fit for the project she was developing?
  2. Because they were trying to use relational data
  3. Needed different types
  4. Didn't fully understand the relationships they needed in their data
  5. Basically Mongo's not great for anything that has important relationships
    6. The more important the relationships, the more likely you are to use relational databases (duh)
1.  What should you consider when choosing MongoDB or a relational database like Postgres?
  2. Where the business value of your data lies
    3. If you have an app where data value is the MOST important thing, don't use the thing that dgaf
    4. Relational databases are going to be safer with your data
  3. Time constraints
    4. Mongo is good if you don't have a lot of time to do a thing
1.  Suppose you were building a blog with comments. Should a comment on one
    article appear on any other article? Will you ever view comments apart from
    their article?
  2. No
  3. That's what twitter is for... not even though bc tweets can have subtweets too
1.  Suppose this blog also had tags. Should tags appear on multiple articles?
  2. Yes.
2. Which is the "parent" relation?
  3. Many to many?
  4. Post?
1.  Contrast the strength "ownership" between blog posts and comments, and blog posts and tags.
  2. Ownership is stronger with blog posts and comments than tags
  3. Tags can be connected to tons of comments
  4. If someone makes a comment, it's just tied to the one post
1.  Suppose you had to edit a tag. In a relational database, how many rows need
    to be changed (best and worst case)? In a document database, how many
    documents need to be changed (best and worst case)?
  2. In a relational db, tons
  3. In a non-relational db, just one

## Compare & Contrast

Put together a list of similarities and differences between relational and
non-relational databases. You can start with comparisons provided by specific
vendors, such as the one found in [NoSQL Databases
Explained](https://www.mongodb.com/nosql-explained). You might wish to organize
your thoughts with a [Venn diagram](https://en.wikipedia.org/wiki/Venn_diagram)
or a series of tables.

## Additional Readings

Pick an additional reading to go through with a classmate. Reflect on how the
article changes the discussion. What have you learned?

-   [What the heck are you actually using NoSQL for?](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)
-   [A co-Relational Model of Data for Large Shared Data Banks](http://queue.acm.org/detail.cfm?id=1961297&repost)
-   [A brief history of databases](http://avant.org/media/history-of-databases)
-   [NoSQL Databases: An Overview | ThoughtWorks](http://www.thoughtworks.com/insights/blog/nosql-databases-overview)
-   [When to choose CouchDB vs RDBMS?](http://stackoverflow.com/a/2731207/402618)
-   [CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/)

## [License](LICENSE)

1.  All content is licensed under a CC­BY­NC­SA 4.0 license.
1.  All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
