# AprioriAlgorithm

WIKI

Apriori is an algorithm for frequent item set mining and association rule learning over transactional databases. It proceeds by
identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets
appear sufficiently often in the database. The frequent item sets determined by Apriori can be used to determine association rules which
highlight general trends in the database: this has applications in domains such as market basket analysis.

Files
Main.java
This file has method calls to candidate generator and Support counter

CandiateGen.java
This file contains methods to generate candiates C1, C2, etc.,

SupportCounter.java
This file generates Support count L1, L2,etc., 

Association rule reference
http://staffwww.itn.liu.se/~aidvi/courses/06/dm/lectures/lec7.pdf
http://www2.cs.uregina.ca/~dbd/cs831/notes/itemsets/itemset_apriori.html
