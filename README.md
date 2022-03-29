# Database Concepts

Topics Covered: 

1. Introduction
    1. [What is DBMS (Database Management System)? Application, Types & Example (guru99.com)](https://www.guru99.com/what-is-dbms.html)
    2. [Database Management Tutorial | Best Resource for Learning DBMS (educba.com)](https://www.educba.com/data-science/data-science-tutorials/database-management-tutorial/)
2. DBMS vs File System
    1. [DBMS vs Files System - javatpoint](https://www.javatpoint.com/dbms-vs-files-system)
3. DBMS architecture
    
    [DBMS Architecture: 1-Tier, 2-Tier & 3-Tier | The Hacking Coach](https://www.thehackingcoach.com/dbms-architecture-1-tier-2-tier-3-tier/)
    
    1. 1-tier architecture
    2. 2-tier architecture
    3. 3-tier architecture
4. What is a database schema
    
    [What is a Database Schema? | IBM](https://www.ibm.com/cloud/learn/database-schema)
    
    1. Conceptual Schema
    2. Logical Schema
    3. Physical Schema
    
5. Three-level schema architecture
    1. [DBMS Three schema Architecture - javatpoint](https://www.javatpoint.com/dbms-three-schema-architecture)
    
6. What is the data Independence concept in DBMS
    1. [Data Independence in DBMS: Physical & Logical with Examples (guru99.com)](https://www.guru99.com/dbms-data-independence.html)
    
7. The concept of ER Model and its components and Relationships
    1. [ER Diagram: Entity Relationship Diagram Model | DBMS Example (guru99.com)](https://www.guru99.com/er-diagram-tutorial-dbms.html)
    
8. Why we need keys in the database management system
    
    [DBMS Keys: Candidate, Super, Primary, Foreign Key Types with Example (guru99.com)](https://www.guru99.com/dbms-keys.html)
    
    1. Super key
    2. Candidate Key
    3. Primary key
    4. Foreign key
9. Types of Attributes in ER-Model
    
    [ER Model - Basic Concepts (tutorialspoint.com)](https://www.tutorialspoint.com/dbms/er_model_basic_concepts.htm)
    
    1. Single vs Multivalued
    2. Simple vs Composite
    3. Stored vs Derived
    4. Key vs Nonkey
    5. Required vs Optimal
    6. Complex - Composite + Multivalued 
10. Types of Relationship in the ER-Model (linked to the last section 9)
    1. 1-1 (One to one)
    2. 1-M (One to many)
    3. M-1 (Many to one)
    4. M-N (Many to many)
11. Functional Dependencies in Database
    
    [Functional Dependency in DBMS | Four Types of Functional Dependency (educba.com)](https://www.educba.com/functional-dependency-in-dbms/)
    
    [Functional dependency in DBMS (tutorialspoint.com)](https://www.tutorialspoint.com/Functional-dependency-in-DBMS)
    
    1. Amstrong axioms 
    2. Closure sets of attributes
        1. [Closure in DBMS | Steps to Find Closure | Gate Vidyalay](https://www.gatevidyalay.com/closure-of-an-attribute-set/)
    
    (Note: learning the closure set and functional dependency is important before getting to the normalization, here’s a great series of videos on this concept by knowledge gate: 
    
    [3.1 Functional Dependency in DBMS - YouTube](https://www.youtube.com/watch?v=wez3fXrjBAE)
    
    [3.5 Closure Set Of Attributes With Examples - YouTube](https://www.youtube.com/watch?v=fT0QMtgqPrU))
    
12. Normalization in Database
    
    [What is Normalization in DBMS (SQL)? 1NF, 2NF, 3NF, BCNF Database with Example (guru99.com)](https://www.guru99.com/database-normalization.html)
    
    [DBMS Normalization: 1NF, 2NF, 3NF and BCNF with Examples - javatpoint](https://www.javatpoint.com/dbms-normalization)
    
    1. 1NF
    2. 2NF
    3. 3NF
    4. BCNF
    
    #### (Note: another set of videos with a great explanation of the normalization concept in DBMS from knowledge gate.)
    
13. **Lossless Decomposition in DBMS**
    1. [DBMS - Lossless Decomposition                | i2tutorials](https://www.i2tutorials.com/dbms-introduction/dbms-lossless-decomposition/)
    
14. Practice Questions on all Normal Forms and know the Dependency Preservation
    1. [DBMS - Dependency Preservation  | i2tutorials](https://www.i2tutorials.com/dbms-introduction/dbms-dependency-preservation/)
    
    (Note: another set of videos with a great explanation of dependency preserving decomposition concept in DBMS from knowledge gate.)
    
15. Started with Joins but need to work on SQL for better command over the concepts (check another repo for the SQL cheatsheet)
    
    [DBMS Joins: Inner, THETA, Outer, Equi Types of Join Operations (guru99.com)](https://www.guru99.com/joins-sql-left-right.html)
    
    [DBMS SQL Joins - javatpoint](https://www.javatpoint.com/dbms-sql-joins)
    
    1. Normal Join
    2. Self Join
    3. Conditional Join 
        1. A conditional column join is a fancy way to let us join a single column and two (or more) columns in a single query. We can accomplish this by using a case statement in on the clause of our join.
    4. Equi-Join
    5. Cross Join
    6.  Outer Join
      1. left-outer join
      2. right-outer join
      3. full outer join
      
16. Intro to Transaction and Concurrency
    
    [What is Transaction in DBMS? | Scaler Topics](https://www.scaler.com/topics/dbms/transaction-in-dbms/)
    1. Transaction States
    
17. ACID Properties
    1. Atomicity, Consistent, Isolation, Durability
    2. [https://www.javatpoint.com/acid-properties-in-dbms](https://www.javatpoint.com/acid-properties-in-dbms)
    
18. Schedule
    
    [Types of Schedules in DBMS - GeeksforGeeks](https://www.geeksforgeeks.org/types-of-schedules-in-dbms/)
    
    [DBMS Schedule - javatpoint](https://www.javatpoint.com/dbms-schedule)
    
    [Schedule in DBMS - W3schools](https://www.w3schools.blog/schedule-dbms)
    
    1. Serial 
    2. Parallel
    - Irrecoverable vs Recoverable Schedule
        
    - Cascading vs Cascade-less Schedule
        
19. Concurrency Problems
    
    [Concurrency Control in DBMS | How Concurrency Control work in DBMS? (educba.com)](https://www.educba.com/concurrency-control-in-dbms/)
    
    1. What is Concurrency control and why it is required?
    2. Dirty Read
    3. Unrepeatable Read Problem
    4. Phantom Read
    5. Lost Updates
    
20. Serializability based on schedule
    1. What is serializability and its types
    
    [Serializability in DBMS | Types of Serializability with Examples (educba.com)](https://www.educba.com/serializability-in-dbms/)
    
    [Serializability in DBMS - Scaler Topics](https://www.scaler.com/topics/dbms/serializability-in-dbms/)
    
    2. Conflict Serializability
        
    3. View Serializability
    
21. Locks
    
    [Levels of Locking in DBMS - GeeksforGeeks](https://www.geeksforgeeks.org/levels-of-locking-in-dbms/)
    
    [DBMS Locks | How do locks work in DBMS with Examples? (educba.com)](https://www.educba.com/dbms-locks/)
    
    1. Time Stamp Ordering
    2. Shared and Exclusive locks
    3. 2 Phase Locks, Strict 2Phase and Rig 2Phase Lock
    
    [Two-Phased Locking, Releasing Locks & Deadlocks in Databases | Study.com](https://study.com/academy/lesson/two-phased-locking-releasing-locks-deadlocks-in-databases.html)
    
22. Indexing
    
    [Indexing in DBMS: What is, Types of Indexes with EXAMPLES (guru99.com)](https://www.guru99.com/indexing-in-database.html)
    
    [Indexing in DBMS - Scaler Topics](https://www.scaler.com/topics/dbms/indexing-in-dbms/)
    
    1. Types of Indexing
        1. Primary - indexing on the index table is sparse as the data is sorted but done key values like roll no, etc.
        2. Secondary - indexing on the index table is sparse as the data is ordered but done on the non-key value
        3. Clustered - data is unordered and indexing can be done on key(like pancard no which are distinct but repetitive) or non-key value(a repetitive name, so we use another intermediatory index table for all the occurrences of the specific same name) this indexing can have sparse and dense indexing in combination both.
        
        [When Indexes are not Useable sometimes! · > sidmulajkar](https://sidmulajkar.com/posts/when-indexes-are-not-useable/)
        
    2. B/B+ trees indexing in DBMS( which are evolved trees over the M-way search trees)
        
        [10.2 B Trees and B+ Trees. How they are useful in Databases - YouTube](https://www.youtube.com/watch?v=aZjYr87r1b8)
        
        [B/B+ Trees How they are helpful in the Database? · > sidmulajkar](https://sidmulajkar.com/posts/b-bplus-trees/)
        
        1. How we use the M-way trees and the problem is that no rules are defined for creating a tree using it.
        2. We use the b trees for multileved indexing as it reduces its complexity.
            1. Rules
        3. B+ trees as used for multileveled indexing
            1. What are the differences between the Btree and B+tree?

22. Recovery in DBMS

[DBMS | Database Recovery Techniques - Tutorialspoint.dev](https://tutorialspoint.dev/computer-science/dbms/dbms-database-recovery-techniques)

1. Log-based Recovery
    1. Deferred Recovery - only Redo is possible in the database in case of failure(redo means writing the new value which are committed)
    2. Immediate Recovery - here undo and redo are possible in case of failure
    3. Shadow Copy - In this technique, a transaction that wants to update the DB first creates a copy of the complete DB and all the updates are done on the copy DB leaving the original untouched.
        1. If the transaction completes writing it commits as well, and OS is asked to make sure whether the new update is properly committed or not.
        2. if it is successfully done, the reference pointer to the database is changed from old to new. 
    4. Shadow Paging - Each entry on the database contains a pointer to the page on the disk
        1. The key idea is to maintain two tables - the current page table and the shadow page table
        2. Current page table makes all the changes and the shadow page is never changed.
        3. when the transactions start both the tables are identical. (shadow page is a copy of the DB to rollback in any case of failure)
        4. If the current table is stable with all the writes and commits then for the next new transaction the new base page table will be the current table and the shadow page table would be emptied or removed. 

   23. Hashing in DBMS

[Hashing in DBMS: Static and Dynamic Hashing Techniques (guru99.com)](https://www.guru99.com/hashing-in-dbms.html)

1. Types of Hashing
    1. Static Hashing
    2. Dynamic Hashing
2. What is Collision in Hashing
3. What is Consistent Hashing and do we need them from the system design point of view
    1. [Consistent Hashing. What is consistent hashing and how does… | by Priyanka Hariharan | The Startup | Medium](https://medium.com/swlh/consistent-hashing-68c13951083e)


Another Great Resource for RDBMS Questions from the interview perspective: https://github.com/learning-zone/mysql-interview-questions/blob/master/rdbms-questions.md
