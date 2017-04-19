# Awesome NoSQL [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/erictleung/awesome-nosql.svg?branch=master)](https://travis-ci.org/erictleung/awesome-nosql)

> "A NoSQL (originally referring to 'non SQL' or 'non relational') database provides a mechanism for storage and retrieval of data which is modeled in means other than the tabular relations used in relational databases." — [Wikipedia](https://en.wikipedia.org/wiki/NoSQL)

Curated list of resources and links about *using* NoSQL databases and things to look for when deciding to use one.

For actual NoSQL databases, you can go [here](https://github.com/sindresorhus/awesome#databases), [here](http://nosql-database.org/), or [here](https://github.com/kahun/awesome-sysadmin#nosql).


## Table of Contents

- [Overview of NoSQL](#overview-of-nosql)
- [Data Structures and Modeling](#data-structures-and-modeling)
- [Trade-Offs in CAP/Brewer's Theorem](#trade-offs-in-capbrewers-theorem)
- [Graph Databases](#graph-databases)
- [License](#license)


## Overview of NoSQL

- [Introduction To NoSQL - Martin Fowler](https://youtu.be/qI_g07C_Q5I) (54:52) - Great introduction to NoSQL databases, the types of NoSQL databases, their history, pros and cons, and how and when to use them.
- [NoSQL Distilled](http://martinfowler.com/books/nosql.html) - Very digestable and affordable book describing the different NoSQL databases and help you make the decision on whether using a NoSQL database is appropriate for your project.
- [Seven Databases in Song](https://youtu.be/jyx8iP5tfCI) (1:43) - Fun song about seven (six are NoSQL) databases with a very condensed overview of how they each work.
- [NoSQL Databases: a Survey and Decision Guidance](https://medium.com/baqend-blog/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.nhzop4d23) - "This NoSQL Toolbox allows us to derive a simple decision tree to help practitioners and researchers filter potential system candidates based on central application requirements."
- [Data Management in the Cloud: Limitations and Opportunities](http://www.cs.yale.edu/homes/dna/papers/abadi-cloud-ieee09.pdf) (PDF) - Discusses limitations and opportunities of data management and data analysis in the cloud.
- [The Five Stages of NoSQL](https://sookocheff.com/post/opinion/the-five-stages-of-nosql/) - Stages of going through picking and using a NoSQL database mirroring the five stages of grief.
- [10 NoSQL Misconceptions](http://www.dummies.com/how-to/content/10-nosql-misconceptions.html) - Some misconceptions about NoSQL databases relating to topics such as what they are, ACID-compliance, and security.
- [10 Reasons Developers Love NoSQL](http://www.dummies.com/programming/big-data/10-reasons-developers-love-nosql/) - A list of ten arguments for why developers like to use NoSQL databases.
- [Distribution, Data, Deployment: Software Architecture Convergence in Big Data Systems](https://resources.sei.cmu.edu/asset_files/WhitePaper/2014_019_001_90915.pdf) (PDF) - Paper to discuss software engineering concerns when dealing with big data systems in terms of distribution, data, and deployment. Also accessible [here](https://doi.org/10.1109/MS.2014.51).


## Data Structures and Modeling

- [Structure Your Database](https://firebase.google.com/docs/database/android/structure-data) - Best practices of structuring your data if your database uses JSON. [Here's](https://www.firebase.com/docs/web/guide/structuring-data.html) an older version of this guide.
- [NoSQL Data Modeling Techniques](https://highlyscalable.wordpress.com/2012/03/01/nosql-data-modeling-techniques/) - This articles provides a short comparison of NoSQL system families from the data modeling point of view and digests several common modeling techniques.
- [Data Modeling Introduction](https://docs.mongodb.com/manual/core/data-modeling-introduction/) - Data modeling discussion specific to MongoDB. However, concepts may carriy over to other document NoSQL databases.


## Trade-Offs in CAP/Brewer's Theorem

- [Visual Guide to NoSQL Systems](http://blog.nahurst.com/visual-guide-to-nosql-systems) - Visual display of trade-offs in the CAP theorem among different NoSQL databases.


## Crowd-Sourced Information

- [/r/nosql](https://www.reddit.com/r/nosql) - Reddit page on NoSQL on general questions and discussions people may have about NoSQL databases.


## Graph Databases

- [Graph Databases Use Cases](https://neo4j.com/use-cases/) - Although documents geared towards Neo4j, concepts are applicable to all graph databases.
- [How the ICIJ Used Neo4j to Unravel the Panama Papers - Mar Cabra](https://youtu.be/S20XMQyvANY) - Learn how graph databases were key to explore who were the main names connected to companies in tax havens, including 140 politicians in more than 50 countries.
- [Graph Databases for Beginners: The Basics of Data Modeling](https://neo4j.com/blog/data-modeling-basics/) - Discusses the basics of modeling your data and which approach you should take.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Eric Leung](https://erictleung.com) has
waived all copyright and related or neighboring rights to this work.
