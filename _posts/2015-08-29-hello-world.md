---
layout: default
title: "Hello world"
date: 2015-08-29 21:34:00 -0700
comments: true
categories: 
---

This is my programming blog. 
For the most part, I will use this blog if there is some code I wish to blog about. Otherwise, I should stick to my [Blogspot](http://blog.yangmungi.com).


Data
---

Data cannot be normalized properly until all its views are resolved.
At first, data is like a big blob, but as common use cases for consuming the data arise, normalization becomes key.
To help prevent bad state after update, keep data normalized.
Generally, there is not a single denormalization that fits every use case.

Traditional web development usage of databases are representations of state. 
Data tends to be more in the format of events or transactions, and to save only the last state of anything is losing some data.
This is fine if the data is not needed for auditing or regeneration.

Event-sourcing is so far the only name I've heard given to this data representation. The [log-based architecture of LinkedIn](https://engineering.linkedin.com/distributed-systems/log-what-every-software-engineer-should-know-about-real-time-datas-unifying) is also similar.


Information
---

The more potential things that could be talked about in a given context, the more specific the medium of communication must be - things naturally become either more verbose or dense.


Data Representations
---

Hash tables are like object data. 
Incorporate some runtime logic resolution algorithms, and you have what should be OOP.

The best way to deal with hash tables, I think, are white-lists and black-lists. 
Hash table trees, or object trees, or object hierarchies, are pretty cool too.
Data really doesn't have a structure until there exists some logic that requires that data to be processed.


Programming Architecture
---

There are definte advantages to encapsulating the knowledge of remote execution within the system. 
A topology-aware system is much more capable of withstanding external forces than a topology-unaware system; unfortunately, it will dramatically increase complexity.

> ... Organizations which design systems... Are constrained to produce designs which are copies of the communication structures of these organizations...
>
> **Melvin Conway**

Why take the steps to adjust to a workflow catering to a different scale people working on a project? It seems like an excess of overhead.

In Conclusion
---

Nothing I said may be correct, so take with a grain of salt.

Oh yeah, this blog is for coding things. So I should include a coding thing.

``` python carly.py
Hey I just met you,
and this is crazy!
But here's my number.
So call me maybe.
```

Results in the following:

``` bash
$ python carly.py
File "carly.py", line 1
   Hey I just met you,
       ^
SyntaxError: invalid syntax
```

Bye.
