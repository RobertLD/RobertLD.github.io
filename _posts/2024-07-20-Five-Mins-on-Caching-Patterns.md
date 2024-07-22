
## Exploring Caching Methodologies
There are projects that I will be working on that will require some thought into different caching methodologies, of which I know very little. This post is just going to serve as my general exploration of the caching landscape, and the design patterns that are popular in their implementation.


### Cache Aside
Apparently the most common of caching methodologies. Data retrieval looks as follows
1. When the application requires data, it asks the cache first
2. If the cache has the data, it is returned and the process ends
3. Otherwise, the database is queries, the data is then cached for future use and returned
The benefits of this meithod are clear. It's straight forward to implement and immediately increases performance of repeated requests.

### Write Through
The write-through pattern is a bit more proactive in keeping the cache up to date.  New data is first written to the cache before it is immediately flushed to the DB. This is before any requests for the data have actually been made. I have a hard time seeing much benefit for this approach; but according to the internet.
1. It greatly increases the chance of cache hits (duh)
2. Increases database performance by lowering query  volume
I'll have to explore this pattern more to see what makes it effective.

### Read Through
The read through cache sits in-front of the database and processes all read commands. If the data  does not exist in the cache, it then fetches it from the database caching it for further use.
1. Read heavy clients will find this performant

### Write-back
A write back cache appears to be an overly fancy way of describing a batch. The client constantly writes data to the cache, and it is periodically flushed into the database in a single batch.x