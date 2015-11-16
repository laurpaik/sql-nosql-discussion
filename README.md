![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)

Discussion: Relational and Non-relational Databases
===================================================

Obectives
---------

By the nd of this discussion, students should be able to:

- Identify use cases where relational or non-relational databases are appropriate.
- List three strengths of relational databases.
- List three strengths of non-relational databases.

Introduction
------------

Read the following:
- [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained) (5 minutes)
- [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click through to at least one detailed example; 10 minutes)
- [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/) (10 minutes)

Discussion
----------

1. According to Sarah Mei, what are the benefits of using MongoDB?
1. Why wasn't MongoDB a good fit for the project she was developing?
1. What should you consider when choosing MongoDB or a relational database like Postgres?
1. Suppose you were building a blog with comments. Should a comment on one article appear on any other article? Will you ever view comments apart from their article?
1. Suppose this blog also had tags. Should tags appear on multiple articles? Which is the "parent" relation?
1. Contrast the strength "ownership" between blog posts and comments, and blog posts and tags.
1. Suppose you had to edit a tag. In a relational database, how many rows need to be changed (best and worst case)? In a document database, how many documents need to be changed (best and worst case)?

Compare & Contrast
------------------

On your own time, put together a list of similarities and differences between relational and non-relational databases. You can start with comparisons provided by specific vendors, such as the one found in [NoSQL Databases Explained](https://www.mongodb.com/nosql-explained). You might wish to organize your thoughts with a [Venn diagram](https://en.wikipedia.org/wiki/Venn_diagram) or a series of tables.

Additional Readings
-------------------

- [What the heck are you actually using NoSQL for?](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)
- [A co-Relational Model of Data for Large Shared Data Banks](http://queue.acm.org/detail.cfm?id=1961297&repost)
- [A brief history of databases](http://avant.org/media/history-of-databases)
- [NoSQL Databases: An Overview | ThoughtWorks](http://www.thoughtworks.com/insights/blog/nosql-databases-overview)
- [When to choose CouchDB vs RDBMS?](http://stackoverflow.com/a/2731207/402618)
- [CAP Twelve Years Later: How the "Rules" Have Changed](http://www.infoq.com/articles/cap-twelve-years-later-how-the-rules-have-changed)
- [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/)

[License](LICENSE)
------------------

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
