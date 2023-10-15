---
title: "General Software Engineer Interview Guide (How to get into FAANGs)"
date: 2023-10-14
---

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fcolacap.github.io%2Fsoftware-engineer-interview-guide.html&count_bg=%2340D135&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)


## Table of Contents
- [Whom This Guide is for](#whom-this-guide-is-for)
- [What Courses to Take at School](#what-courses-to-take-at-school)
- [Resume](#resume)
- [Interview Prep](#interview-prep)
	- [Data Structures and Algorithms](#data-structures-and-algorithms)
	- [Computer Systems](#computer-systems)
	- [Programming Interviews Exposed](#programming-interviews-exposed)
	- [Cracking the Coding Interview](#cracking-the-coding-interview)
	- [Leet Code](#leet-code)
	- [Competitive Programming](#competitive-programming)
	- [Object Oriented Design (OOD)](#object-oriented-design)
	- [Design Patterns](#design-patterns)
	- [System Design](#system-design)
	- [Real Life Examples/Concepts/Products to Familiarize Yourself](#real-life-examples)
- [Types of Interviews](#types-of-interviews)
- [Applying to Companies](#applying-to-companies)
- [How to Negotiate Better](#how-to-negotiate-better)
- [Leveling Guide](#leveling-guide)
- [Case Study](#case-study)
- [Additional Materials](#additional-materials)


## Whom This Guide is for
This guide is slightly geared towards students preparing for the general web backend software engineering (SWE) interviews and career prep. However, a lot of the contents in this guide will the overlap with other types of SWE and covers up to senior engineer interviews. So anyone from students to senior engineers can use this guide as one of the sure-fire paths you can take to go from 0 to your dream company.

*If you are a student who are not yet certain which path (frontend? backend? game? embedded? infra? etc?) you are going to pursue, still get prepared as outlined in this guide. General web backend SWE is the best starting point, in terms of job/company/position/opportunities and TC (Total Compensation, a.k.a. money). Then, do as many internships at different companies as possible to find out which career path you want to pursue for after graduation.*

## What Courses to Take at School
*For non-students, skip to the next section.
For non-UBC students, refer to your school's courses that teach similar topics.*
   * For Interview Prep (Learn these courses really well)
       * (Must) CPSC 221 Data Structures and Algorithms (DSA)
       * (Partially must) CPSC 213 Intro to Computer Systems
       * (Strongly suggested) CPSC 320 Intermediate DSA
   * For career for “general web” SWE but not necessarily for interview prep
       * (Must) CPSC 304 Intro to Database
       * (Suggested) CPSC 404 Advanced Database
       * (Suggested) CPSC 416 Distributed Systems
           * These two courses below are prerequisites to this course. I’m not sure how useful these two prerequisite courses are. However, knowing about distributed systems is really crucial in being successful as a web backend engineer and doing well in system design interviews (more on this later). So take these prerequisite courses if you can take 416 considering the timeline/credits/graduation date/etc. Otherwise, it might be better to focus on other courses you are interested in.
               * CPSC 313 Computer Hardware and Operating Systems
               * CPSC 317 Internet computing
   * Other courses to consider depending on your interest
       * Whether you should deep dive and master a topic or take one each to get the feel of each topic/field, is something you need to seriously consider, decide early on, and plan ahead to meet the prerequisites of the courses you want to take.
       * AI
           * CPSC 322 Introduction to Artificial Intelligence
           * CPSC 330 Applied Machine Learning
           * CPSC 340 Machine Learning and Data Mining
           * CPSC 422 Intelligent Systems
           * CPSC 440 Advanced Machine Learning
       * Graphics / 3D
           * CPSC 314 Computer Graphics
           * CPSC 424 Geometric Modeling
           * CPSC 425 Computer Vision \
CPSC 426 Computer Animation
       * Game
           * CPSC 427 Video Game Programming
           * Having courses related to Graphics above will be really beneficial if you are interested in working on the client side of AAA-game/VR/AR development.
       * Programming Language
           * CPSC 311 Definition of Programming Languages
           * CPSC 312 Functional and Logic Programming
           * CPSC 411 Introduction to Compiler Construction
       * General Software Engineering
           * CPSC 210 Software Construction
           * CPSC 310 Introduction to Software Engineering
           * CPSC 319 Software Engineering Project
           * CPSC 410 Advanced Software Engineering

## Resume
   * For students and people with no experience:
	   * Hackathons
	       * Until you have at least one internship at a reputable company, have as many hackathons and game jams (up to 5) on your 1-page resume.
	   * Side projects
	       * Open Source
	           * The more popular the open source project is, the better.
	       * Personal
	           * Great if it has real users
	       * School
	           * Capstone projects are great since they are for a real company that spans for a few months in a group of members.
	           * Other than the capstone project, put if there is nothing else to put on the resume.
	   * Competitive Programming
	       * More on this later
	   * Teaching Assistant (TA) for CS courses
	       * Can slightly boost your resume and give you money.
	   * As the resume fills up, get rid of the lowest priority ones from the hackathon and side project sections to keep things in 1 page. You need to evaluate each hackathon and side project case by case to figure out which is of lower value.
	   * Experience/companies to go for
	       * Aim for getting internships or new grad positions at **named** “**tech”** companies. This is especially important when you don’t have experience as having experiences at named tech companies on resume will give you a much higher chance to get interviews at your dream companies when you try to move later.
	           * Trading/hedge fund companies are exceptions. If you go for companies like Jane Street, Two Sigma, and etc, that’s great even if they are not “tech” companies.
	       * If your first new grad position out of university is at a no-name non-funded tiny local startup, you will have an extremely hard time moving up to your dream company later on as recruiters from those dream companies won’t consider your resume. So make sure your first job out of school counts.
	           * It does not have to be FAANG or other top tier tech companies in the Bay Area. It just needs to be a “tech” company with a strong engineering culture and is either public, funded, or named (out of the three, as you can probably expect, ‘named’ is the most important one for resume boosting).
	           * Your first job and position will affect your next career opportunities tremendously. So make sure you get enough internship experience at good enough companies to help you get interviews for your new grad position at great companies.
	       * Do not go for non software engineer positions, such as a QA/tester, if your goal is to become a software engineer. Your internship experience as a QA engineer will not give you the necessary experience needed as a software engineer. Also, your resume becomes less appealing than your peers who went for software engineer positions.
    * For people with experience:
	    * Try to focus on mentioning your achievements/impacts with measurable results.
		    * When working, try to track all of your work and record any notable stuff in an ongoing basis. That way, by the time you are to move to another company, you have a readily-available list of achievements to write down on your resume.
		    * Examples:
			    * Setting new coding/testing standards
			    * Improving the memory footprint by 15%
	    * Also, mention your leadership.
		    * Examples:
			    * mentoring juniors
			    * leading a project
			    * leading group discussions

## Interview Prep
### Concepts You Need to Know for Interviews
   * <a id="data-structures-and-algorithms"></a>Data Structure and Algorithms
       * Important Data Structures (ones in **bold** are “exceptionally” important)
           * Basic
               * **String**
               * **Array**
                   * 1d, 2d (matrix)
               * Linked List
               * **Set**
               * **HashMap** (Dictionary)
               * **Stack**
               * **Queue**
               * **Tree**
                   * BST
               * Heap
               * Graph
           * Intermediate
               * Bits (Bit array, Binary)
               * **Trie**
               * Monotonic Stack
               * Monotonic Queue
           * Advanced (Just know that they exist. Not necessary to study ‘most of the time’. For those rare interviews that give you these, just accept the un-luck and move on.)
               * AVL Tree
               * Red Black Tree
               * Segment Tree
               * B-Tree
               * NP-complete problems
           * Make sure you know the time/space complexities (big o notation) of each operation that can be done on each data structure. For example, what the time complexity is for:
               * Array insertion
               * Putting an element in a heap
               * Finding an element in a linked list.
               * Etc 
               * Make sure you **UNDERSTAND** why it takes that much time/space rather than memorizing them. This is the whole point of learning data structures.
       * Important Algorithms
           * Basic
               * Greedy
               * Two Pointers
               * **Recursion**
                   * Being able to convert it to an iterative version
               * Sorting
                   * QuickSort
                   * MergeSort
                   * HeapSort
                   * CountingSort
                   * **TopologicalSort**
               * Searching
                   * Binary Search
               * **Traversals** (Tree, Graph)
                   * BFS, DFS
                   * In order, pre order, post order
           * Intermediate
               * Divide and Conquer
               * Dynamic Programming (DP)
                   * Memoization
                   * Tabulation
                   * Sliding Window
               * Bit Manipulation
           * Advanced
               * Dijkstra
               * A*
           * Misc
               * QuickSelect
       * Big O Notation
		  You are going to need to explain the time and space complexity for your solutions during the interviews. So understand these concepts really well.
           * Time Complexity
           * Space Complexity
       * Supportive Material
           * [Abdul Bari Youtube](https://www.youtube.com/channel/UCZCFT11CWBi3MHNlGf019nw/videos)
               * This person explains Algorithm stuff freaking well. If you need a verbal/visual explanation of concepts, search for the topic on his channel and watch the video.
           * [Graph Algorithms for Technical Interviews - Full Course](https://www.youtube.com/watch?v=tWVWeAqZ0WU)  
	           * I think schools should tell students to watch this video during their DSA courses. Freaking awesome video.
   * <a id="computer-systems"></a>Computer Systems
       * Learning the whole course is not required for interview prep but you should still know these concepts
           * Stack vs Heap memory
               * Stack overflow
           * Concurrency
               * Threads
               * Locks, Semaphores, Mutex, etc
           * Locality of reference, spatial locality

### How to Study (in order)
   * <a id="programming-interviews-exposed"></a>[Programming Interviews Exposed](https://www.google.com/search?q=Programming+Interviews+Exposed) (PIE)
       * If you are a student, depending on your commitment and timeline, you may want to start this part of the step and onwards before taking/finishing the DSA course above. It’s always better to start early as long as you can commit and study on your own. (you are basically learning the materials in the DSA course by yourself instead of being taught by the instructor.) If you wait until you finish the DSA course to start preparing for the interviews, you may not have enough time to get prepared in time (especially if you are in a 2 year bachelor program like BCS at UBC).
       * Chapters to read (Based on the 3rd edition)
           * Introductory stuff (Chapters 1~3)
           * Thoroughly read the chapters for the topics mentioned above. These directly help with the actual coding interviews
               * Ch 4. Linked Lists
               * Ch 5. Tree and Graph
               * Ch 6. Array and String
               * Ch 7. Recursion
               * Ch 8. Sorting
               * Ch 9. Concurrency
               * Ch 13. ~~Graphic~~ and Bit Manipulation
                   * Graphic part is not necessary
           * These will help with verbal questions asked during interviews
               * Ch 10. Object Oriented Programming
               * Ch 16. Knowledge based questions
               * Ch 17. Non Technical Questions
           * Appendix. Resumes
           * <a id="pie-design-patterns"></a>**(Come back after doing LeetCode)** 11. Design Patterns
   * <a id="cracking-the-coding-interview"></a>[Cracking the Coding Interview](https://www.google.com/search?q=cracking+the+coding+interview) (CTCI)
       * Chapters to read (Based on the 4th Edition)
           * Read all the introductory stuff before the section “Interview Questions”
           * **Solve every single questions** in these chapters
               * Ch 1. Array and Strings
               * Ch 2. Linked Lists
               * Ch 3. Stacks and Queues
               * Ch 4. Trees and Graphs
               * Ch 5. Bit Manipulation
               * Ch 8. Recursion
               * Ch 9. Sorting and Searching
           * Also do the chapters on “C++” (Ch. 13)  and/or “Java” (Ch. 14) (depending on the language you used)
           * Read and understand Ch 18. Threads and Locks but solving the problems is optional.
           * <a id="ctci-object-oriented-design"></a>**(Come back after doing LeetCode)** Ch 7. Object Oriented Design
           * <a id="ctci-system-design"></a>**(Ignore for internships. Comeback to this when prepping for New Grad/Entry level positions)** Ch 12. System Design
   * <a id="leet-code"></a>[LeetCode](https://leetcode.com/)
       * [Grind 75](https://www.techinterviewhandbook.org/grind75?grouping=weeks&hours=16&weeks=10) (Newer version of [Blind 75](https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions))
           * Recommended workload: 2 hours a weekday, 3 hours a weekend day => 16 hours a week. This will yield a total of 10 weeks to finish the 169 questions in Grind 75.
           * **Remember, you are probably taking courses at this point. Use your time wisely.**
           * Choose the language you are the most comfortable with.
               * If you don’t have a preference, yet, Python is suggested as it will make interview-question-type of questions easier to code with.
           * **After you’ve done all the Easy questions, you are now prepared to “start” applying for internships.**
           * The more Medium+ questions you solve, the higher the chance of doing well on your interviews.
           * After finishing the 169 questions in Grind 75, you are probably good enough to do well on ‘many’ leetcode style interviews. The author of Grind 75 mentions that the returns of solving more problems diminish after 169 questions. I do agree with the diminishing returns in terms of value / effort perspective. However, even though the return does get diminished, a return is a return. The more returns you have, the higher chance of you doing the interviews well. So I suggest you to, at least, do more leetcode until you finish the [Company tagged questions](#company-tagged-questions) section below. Company tagged questions are usually of high quality and you can also increase the chance of seeing the problems you have practiced during the real interviews. (This should not be the purpose of solving leetcode problems. The purpose should be to learn/practice and get better at solving problems. However, it’s a side effect which will greatly increase your chance of passing the interviews.)
           * Make use of the “Discussion” section after solving a problem to see how others have solved the problem. If there are better solutions, learn from them and try implementing them yourself.
               * Also, you can use this section to get some help when you are stuck on a problem. However, spend at least half an hour on your own before referring to the discussion section for solutions.
       * Go back and do the “Come back after doing leet code” steps above. Then come back and proceed from here.
	       * [step 1](#pie-design-patterns)
	       * [step 2](#ctci-object-oriented-design)
	       * [step 3 (unless for internships)](#ctci-system-design)
           * **Finish these before your final round (on site) internship interviews.**
           * **You are now prepared to start applying for New grad / entry level positions.**
       * <a id="company-tagged-questions"></a>Company tagged questions
           * These are the questions that were actually asked by these companies in real interviews. Questions in real interviews are, many times, repeated especially for the 1st phone interviews.
           * Either pay for Leetcode subscriptions
           * Or use some other sources like [this](https://github.com/xizhengszhang/Leetcode_company_frequency)
           * Do as many from FAANGs and from the specific companies you are applying for. A lot of the questions used by FAANGs are of high quality _(I’m basing off of the link I linked above and not from the actual leetcode’s company tagged questions as I have not paid for the leetcode subscription)_. You’ve probably already solved many of the ones while doing the Grind 75 since many questions overlap. Do the ones that weren’t covered by Grind 75.
       * Now, do 1 leetcode problem a day.
           * Choose any good question you want
               * Focus on the topics you are weak on.
               * Can repeat good questions you already solved.
               * Good questions usually have a high # of “likes” with low # of “dislikes”.
               * Medium level ones are usually the best choice for reward/time ratio.
               * The questions from number 1~700 are usually of higher quality than the later ones.
           * Doing 1 a day will make your interview life so much easier down the road. Also will give you higher chances for higher TC positions.
           * Practice and practice until you are comfortable with finishing medium questions in 25 minutes and hard questions in 45 minutes, on average. Knowing and understanding how to solve is important but being able to implement it fast is also pretty crucial in a timed interview environment (not so much in real life though. This is one of the many aspects why the current interview process is so controversial).
           * Someone said “_One leetcode a day keeps unemployment away_”
       * Supportive Material
           * [NeetCode YouTube](https://www.youtube.com/c/NeetCode/videos)
               * If you are having a problem understanding a LeetCode problem or want to understand the solution deeper, search for the problem in his channel and watch it. His videos are the most easily understood.
               * Many times, I find watching his videos are better in making me understand why the solution is the solution than reading the posts in the discussion section.
               * There are some problems that he has not covered. If you are having a problem with a problem that is not covered on his channel, that’s unfortunate. 
           * [BackToBackSWE](https://www.youtube.com/c/BackToBackSWE/videos) 
               * Try this channel if you weren’t able to find the problem on NeetCode. This channel is also very good at explaining.
   * <a id="competitive-programming"></a>[Optional] Competitive Programming (ACM-ICPC)
       * If you like doing this kind of Data Structures and Algorithms stuff, try competitive programming. Find the team at your school and join them if possible.
           * [UBC ACM](https://www.cs.ubc.ca/students/undergrad/life/acm) 
       * [Google CodeJam](https://codingcompetitionsonair.withgoogle.com/)
       * [Code Forces](https://codeforces.com/)
       * [Facebook (Meta) Hacker Cup](https://www.facebook.com/codingcompetitions/hacker-cup/)
       * If you become good at competitive programming, DSA interview questions will become so easy for you.
       * Also, if you get placed in some top ranks in those competitions, and put it on your resume, it will make your resume outstanding. (not sure about experienced positions but probably useful at least up to intermediate positions)
           * Even without being placed in top ranks in competitions, just becoming an “official” member of your school’s ACM team will still boost your resume.
       * You can also earn money if you are placed as one of the top rankers! (probably impossible for most of us though)
   * <a id="object-oriented-design"></a>Object Oriented Design (OOD). Also known as Low Level system Design (LLD)
       * [The chapter on Object Oriented Design in CTCI](#ctci-object-oriented-design)
       * [Leetcode OOD discussion](https://leetcode.com/discuss/interview-question/object-oriented-design)
           * Look at what kind of OOD questions there are.
       * Watch some OOD/LLD YouTube videos.
       * Example Questions
           * Design a Shopping Cart
           * Design a Movie Ticketing System
           * Design Tic Tac Toe
       * **You now have a pretty good chance to do well on many New Grad / Entry level interviews.**
   * <a id="design-patterns"></a>Design Patterns
       * [The chapter on Design Patterns in PIE.](#pie-design-patterns)
       * You probably won’t get asked specifically about design patterns but you should be able to apply appropriate patterns when you are doing OOD interviews or at least be able to discuss them.
   * <a id="system-design"></a>System design (High Level system Design, HLD)
       * Important Concepts
           * Load Balancing
           * Caching
           * Consistent Hashing
           * Database
               * Data Partitioning
               * Data Redundancy / Replication
               * SQL and NoSQL
               * CAP Theorem
           * Networking
               * HTTP requests
                   * REST vs SOAP vs GraphQL
               * Websockets
               * TCP/UDP
           * Eventual Consistency
           * Availability
           * Durability
       * [Gaurav Sen System Design Playlist](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
           * Watch every single video in this playlist
           * Do in parallel while studying the Grokking the System Design Interview. Just watch one video each time you eat lunch/dinner.
           * Watch the fundamentals/concept videos first and then the “design something” videos.
       * [Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview)
           * Pay for 1 month ($69 CAD) and finish this course within 1 month unless you want to subscribe.
           * Read “Glossary of System Design Basics”
               * **You are going to pretty much ace almost all New Grad/Entry level position interviews at this point.**
           * and then read “System Design Problems”
               * **After both Guraev San’s videos and this course, you are now ready to start applying for experienced level positions.**
       * [Microsoft Cloud Guide](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/dn589781(v=pandp.10)) (suggested)
           * Asynchronous Messaging Primer
           * Data Consistency Primer
           * Data Partitioning Guidance
           * Data Replication and Synchronization Guidance
       * [Microsoft Cloud Design Patterns](https://docs.microsoft.com/en-us/previous-versions/msp-n-p/dn600223(v=pandp.10)) (suggested)
           * Cache-Aside Pattern
           * Circuit Breaker Pattern
           * Compensating Transaction Pattern
           * Compete Consumers Pattern
           * Command and Query Responsibility Segregation (CQRS) Pattern
           * Event Sourcing Pattern
           * Index Table Pattern
           * Priority Queue Pattern
           * Queue-Based Load Leveling Pattern
           * Retry Pattern
           * Sharding Pattern
       * Practice
           * Go through all the design problems you saw on Gaurav's videos and the Grokking course and try coming up with your own design without looking. Then compare.
           * Look at any other products you use and think and come up with a system design for the product.
           * Make sure to think/understand what will happen and how to resolve when any/every component of the system fails. 
               * If the primary db/cache fails, what happens and how to resolve it?
               * If one of the workers fails,
               * If the queue fails,
               * etc
           * **Now you should be pretty ready for experienced level tech interviews.**
       * Tech Blogs (Additional Material)
           * Read anything interesting from tech blogs of other companies. Tech companies usually have tech blogs where they describe the problems they faced and how they solved it. Will let you learn a ton from practical problems rather than just from academic problems.
           * Some example blogs
               * [Dropbox](https://dropbox.tech/)
               * [Instagram](https://instagram-engineering.com/)
               * [Uber](https://eng.uber.com/)
           * **Now you should be able to do pretty well on many experienced level tech interviews**
       * Additional Materials (I personally watched the first bullet point but did not watch/read the other 3 bullet points, yet)
           * [System Design Interview YouTube](https://www.youtube.com/c/SystemDesignInterview)
               * This is also one of the most praised channels for having in depth videos of system designs. However, there are only 6 videos. It might be a bit hard to understand if you are a non-native speaker like me.
           * InfoQ videos
               * I heard these videos are really helpful. Some examples are:
               * [https://www.infoq.com/presentations/Pinterest/](https://www.infoq.com/presentations/Pinterest/)
               * [https://www.infoq.com/presentations/Twitter-Timeline-Scalability/](https://www.infoq.com/presentations/Twitter-Timeline-Scalability/) 
               * [https://www.infoq.com/presentations/dropbox-infrastructure/](https://www.infoq.com/presentations/dropbox-infrastructure/) 
               * Etc
           * [ByteByteGo & System Design Interview Book by Alex Xu](https://bytebytego.com/) 
           * [System design Udemy Course by a Facebook TechLead](https://www.udemy.com/course/system-design-a-comprehensive-guide/) 
	* <a id="real-life-examples"></a>Real life examples/concepts/products to familiarize yourself
		* Coding
	       * Web Crawler
	       * Quad Tree
	       * Parsing strings like YAML, XML, JSON, CSV, Lisp and etc.
	       * Deduping/finding duplicates
	           * Hashing/Checksum
	   * System Design
	       * Cloud stuff (AWS, Azure, GCP, etc)
	           * S3
	           * Cloudflare
	           * HDFS
	           * etc
	       * Message Queues
	           * Kafka
	           * Active Mq
	           * etc
	       * DBs
	           * MySql
	           * Cassandra
	           * MongoDB
	           * etc
	       * Cache
	           * Redis
	           * Memcached
	       * Logging/Searching
	           * Kibana
	           * ElasticSearch
	       * VM/Container
	           * Docker
	           * Kubernetes
	       * ZooKeeper
   * **[Leetcode Discuss](https://leetcode.com/discuss/interview-question) / Glassdoor**
       * Many people post the actual interview questions they were asked on LeetCode and Glassdoor. The chance of the same question being asked is actually surprisingly high. There were so many times where I searched the specific companies I’m interviewing for on LeetCode and Glassdoor before the interview and had exactly the same question on my actual interviews. So make use of these available tools. This applies to both coding and system design interviews.

## Types of Interviews
   * DSA / Coding / Pair Programming*
       * This interview is the base of most of the interviews. There are some companies trying to avoid leetcode style questions but the majority is still using this type of interview at this moment.
       * You are given a question that is either directly from Leetcode, variation of it using different words, or some question that follows the same/similar pattern as questions on Leetcode.
       * Some companies “say” their interviews are not Leetcode style and call it Pair Programming but I was given a Leetcode style question during their Pair Programming interview (ie. Cash App). So still be prepared for a possible DSA interview when a company says Pair Programming interview.
   * Problem Solving Exercise / General Programming / Live Coding / Pair Programming*
       * This interview is a coding interview where you are given a question that is more like a real life problem than the Leetcode style questions.
       * "A few" companies do this interview by having the candidate implement the solution on their own without them (the interviewers) being present. (They explain the problem, goes away, and come back when the time is up.)
       * You can use whatever resource you need.
           * Google
           * Stackoverflow
           * Documentations
       * It is accessing whether you have the ability to solve a problem on your own and how you approach solving a problem.
       * So practice building programs on your own using the internet.
       * This is not about solving problems relating to Data Structures or Algorithms. This is about solving problems relating to real problems(..?).
       * Examples:
           * Build a program that can download (save to disk) all the images from a given URL.
           * Build a Web Crawler that crawls a given URL and crawls all the URLs in that URL.
   * OOD (This interview may still be called a ‘coding’ interview probably. So you still need to be prepared for possible OOD questions when doing coding interviews)
       * This interview is about designing the low level design (object oriented design) of a system.
       * You would be gathering requirements, coming up with class designs, db schemas, and implementing the solution.
       * Out of so many interviews I did for internships, new grads, and senior positions, I think I only had one OOD question.
       * Many interviewers still ask a lot of OOP (objected oriented programming) concepts/fundamentals during the regular coding interviews even if they don’t specifically ask an OOD question. So be sure you know the CS/OOP fundamentals.
           * Polymorphism
           * Inheritance
           * Override vs Overload
           * Abstract class vs Interface
           * Virtual vs abstract method
           * Pass by reference vs pass by value
           * etc
   * System Design
       * This interview is about designing the high level design of a system.
       * You’d need to come up with the functional requirements, non-functional requirements, db schemas, capacity plannings, APIs, and the actual diagram of the design.
       * You’d need to explain all the tradeoffs you make, how different components will communicate with each other, what needs to be monitored/measured, and etc.
       * <a id="level-determinant-interviews"></a>This interview and behavioral interviews are usually the level determinant interviews.
           * If you interview for a senior role and you do badly on these, you are likely to get down-leveled to an intermediate role.
           * Doing well on coding interviews will not make you a senior if you don’t do these interviews well.
       * Some companies give you system design interviews from intermediate levels. Some do from senior levels. Few do not have system design interviews at all even for senior positions.
       * New grad level interviews can still have system design ‘concept’ questions. They don’t ask you to design the whole system but can ask to design a small portion of the system or ask what something is (what is consistent hashing?, how does it work?, implement it, etc)
   * Behavioral / Culture fit
       * This interview is about explaining how you worked/behaved and how you would work/behave.
       * Many behavioral interviewers also ask questions that are more of technical deep dive questions on top of behavioral questions during behavioral interviews. So prepare both types.
       * [Example questions](https://www.levels.fyi/blog/amazon-leadership-principles.html)
           * These are example behavioral questions for Amazon’s leadership principle. Many companies ask the same or similar questions.
       * Usually one of the level determinant interviews. ([as mentioned in the System Design section](#level-determinant-interviews))
   * Technical Deep Dive / Resume deep dive
       * This interview is about describing one or two pretty recent complex/big/interesting projects you worked on. For experienced positions, be sure to pick a project that you led.
       * Sometimes they want you to draw diagrams and give specific details about the classes and etc
       * Other times they want you to verbally describe the high level and focus more on what you did and talk about some behavioral stuff related to the project.
           * What specifically did you do?
           * How did you coordinate with the team members?
           * What would you do differently if you were to go back and do it again?
           * What was the biggest challenge?
           * Was it successful and how did you measure the success?
           * etc
   * Code Review
       * This interview is about measuring your ability as the code reviewer.
           * Whether you can find bugs by tracing the code
           * How you give feedback
           * What you focus on during the review
           * etc
       * You are given a code and you’d need to actually review the code and leave comments during the interview.
       * Example questions they might also ask
           * What do you look for when you code review?
           * How do you deal with it when the code author does not agree with your feedback?
           * How do you give feedback?
           * Do you treat juniors and seniors differently?
           * The purpose of Code Review interviews seems to gauge whether the candidate has the ability to trace the code to find bugs and also be able to give constructive and critical feedback.
   * In general:
       * Interns:
           * mostly get DSA (Data Structures and Algorithms) questions (LeetCode style), potentially a few LLD/OOD design questions, and maybe some knowledge based questions on language and/or CPSC fundamentals.
           * There are usually 2-4 technical interviews where each will be about 30~60 min each. (ie. Amazon gave me two 30min phone interviews for internship but Microsoft did one full onsite interview where there were four 60 min interviews)
       * NewGrad/Entry level positions
           * start getting more LLD/OOD design questions than Interns. Also, you may be asked about the concepts/fundamentals of system design (ie. consistent hashing, caching, load balancers, and etc) but not the actual HLD questions like Design Facebook. You “may” get a question like that but focused on a very small subset of the system.
           * Usually one 45~60 min tech phone interview and on site that has 4~6 60 min interviews
       * Experienced positions (intermediate & senior. Don’t know about staff+)
           * will now start getting real system design questions. Also, behavior interviews and technical deep dive interviews (where the interviewer will deep dive on 1-3 projects you did) will also be there.
           * Similar format as the new grad but different types of interviews.
       * Basically, interviews get harder as you go from intern -> new grad -> experienced. So try hard to get the internships at companies you want to work and get a return offer while doing internships. This is by far the easiest way to work at the company you want to work at.

## Applying to Companies
   * In person
       * It is best to apply in person at events like career fairs and/or information sessions at your school. Having the chance to talk and show your passion when giving your resume to the recruiter/engineer will boost your chance of getting the interview.
   * Referrals
       * Not all companies existing on earth will come to your school. So for these companies, you’d need to apply online rather than applying in person.
       * Find people who can refer you to those companies. Do not apply and ask for the referral. They need to refer you first in order for the referrals to work properly.
       * The chance of getting an interview with a referral vs without is unbelievable (it was 4x better chance for me. 16% vs 64% out of approximately 60 companies). If you are not applying in person nor with referral, assume getting an interview is lucky unless your resume has a top tier company name.
       * You can also make use of [Blind](https://www.teamblind.com/) to find referrals.
           * There are plenty of posts on Blind asking for referrals and offering to refer. Either find the posts and DM those who commented on those posts or write a post yourself.
           * You can DM 10 people per month on Blind for free. So plan accordingly or pay.
       * If you are not in a situation where you can get access to a Blind account (need a work email or a friend who has an account), find some other online communities where you can ask for referrals. Many people are willing to offer a referral since they get referral bonuses. Then, when you get your first internship/job, make the account using your work email so you have the blind account for your subsequent job searches.
   * Timeline (priority)
       * Usually takes 3+ weeks from the initial recruiter call to the onsite when things go smooth. There are many factors that can delay such as:
           * Non-overlapping availability between you and their interviewers
           * Team matching takes time for companies that do team matching
           * Some recruiters are just so slow in responding.
           * They going on hiring freeze
           * The position gets filled
           * Etc
       * Calculate and schedule carefully to align as many onsite interviews as possible within the same time period. Offers usually have a deadline (you can extend to some degree). You want to avoid being in a situation where you get an offer from your tier 2 company whose deadline will end before you even do the interviews with your tier 1 companies. You would need to choose between accepting the tier 2 company now or reject the offer from your tier 2 company and continue with tier 1 company interviews and risk not getting any offers if you don't do well with the tier 1 company.
       * Also, be mindful of the risk of having the position get filled by another candidate when delaying interviews to align the onsite interviews
   * [Levels.fyi General](http://levels.fyi) [Levels.fyi For Internships](https://www.levels.fyi/internships/)
       * This site shows the TC (Total Compensation) for each level. Find out how much you can earn at each company for the level you are applying for.
           * You can also gauge whether you are being low balled or not when you get an offer.
           * Mostly the TC you see on this site is for US positions. For companies which have lots of data points, there is an option to choose the specific city or different country to see the TC for that specific region.
       * Different companies have different leveling systems. You can also use this tool to compare the levels
       * A senior level in company A might be equivalent to an intermediate level in company B. So use this tool to gauge what level you should be applying for. Many companies also include the minimum YOE (Year Of Experience) in their job description. You can also make use of that to determine which level you should be applying for for that specific company.
       * In general (YOE is not the determinant but your impact is. YOE is just a tool to give you a rough idea)
           * 0 - 2 YOE is New Grad / Entry / Junior
           * 2 - 5 YOE is Intermediate
           * 5 - 8 YOE is Senior
           * 8+ YOE is staff+

## How to Negotiate Better
**(Read these “before” starting applying to companies. Interns can ignore this, for now)**
   * <a id="ten-rules-for-negotiating-part1"></a>**[Ten Rules for Negotiating a Job Offer (part 1)](https://haseebq.com/my-ten-rules-for-negotiating-a-job-offer/)**
   * **[How Not to Bomb Your Offer Negotiation (part 2)](https://haseebq.com/how-not-to-bomb-your-offer-negotiation/)**
   * [Salary Negotiation: Make More Money, Be More Valued](https://www.kalzumeus.com/2012/01/23/salary-negotiation/) 
   * Notes from these articles:
       * Show excitement about the offer/role/company so they know you are interested in working at the company and worth their time negotiating to hire you.
       * Write every detail down
       * Keep the door open. Never let them know that you are inclined to take the offer until the negotiation is absolutely finished.
       * Keep your information secret as possible so they don’t get the upper hand.
       * Mention that you have an offer, when you do, to other companies to expedite the interview process. This will let you have as many interviews ending at a similar timeline to have as many valid offers to evaluate and use for negotiation.
       * The author of [Ten Rules for Negotiating a Job Offer](#ten-rules-for-negotiating-part1) says that big companies are usually relatively slower in the interview process than smaller ones and also that they give less exploding offers (the offers that have a deadline of 48~72 hours). Given that, it is wise to start applying to bigger companies first to make sure all interviews end at a similar time. However, you also need to make sure to interview with low tier companies first so you are more experienced in doing interviews when it is time to interview with top tier companies of your preference (which often means big companies). So plan wisely.
       * Have alternatives and present the alternatives to the other party as something worth pursuing. (ie. staying at current company, keep interviewing at other companies, going to grad school, taking an offer from another company, etc)
       * Try not to give the numbers you want first. However, if you ever need to before passing all the interviews, give some objective numbers like industry average. And mention that that is the point to start with rather than that is the numbers you are aiming for.
       * State reason for any requests to improve the offer. Money is only one of the parts of the offer. Negotiate all dimensions of the offer. (ie. vacation days)
       * Assert your value
       * Stock options are risky as they are not yours until you exercise. This means, if you leave/quit without exercising, you lose them. Even if you exercise, if the company is not public, you cannot sell them.
       * The recruiter you are talking to is probably trying to close the deal as soon as possible by trying their best to give you what you want within reasonable limits. The real people that decide the offer numbers are probably the hiring committee. So do not feel bad trying to negotiate with the recruiter. The recruiter does not care too much about whether you are getting more money or not. The money is not coming out of their pocket.
       * Mention that you’d need some time to think it over, discuss with your family or significant other, and etc. This will buy you some time easily if you need some time.
       * Bottom Line: **NEVER EVER LET GO OF YOUR NEGOTIATING POWER UNTIL YOU SIGN while staying honest to build a positive relationship.**

## Leveling Guide
   Higher level means higher TC!
   You are an IC (Individual Contributor) when you are a software engineer. You get an opportunity to move into management roles from senior levels. In this guide, only the IC track is considered.
   
   * [Dropbox's Leveling Framework](https://dropbox.github.io/dbx-career-framework/) 
       * Not all companies have the same leveling system but many overlap.
   * Level 1 (New Grad / Entry / Junior)
       * Talk with your lead about how to grow
       * Look at your company’s specific leveling guide (if there is one. There should most likely be)
       * Focus on having good code and LLD/OOD
           * Try to apply the design patterns and OOD stuff you learned.
           * Investigate the codebase at your company and see what kind of design patterns are already at use and how they are actually being used in the industry.
       * One LeetCode problem a day
       * Books / Things to read
           * [Google's Code Review Guide](https://google.github.io/eng-practices/review/) 
           * Pragmatic programmers?
           * Code Complete?
           * Clean Code?
   * Level 2 (Intermediate)
       * **Consider jumping to another company at the end of Level 1 or at the start of Level 2 unless you are already at one of your dream companies. Even then, at least consider jumping to another dream company. Jumping will give you the opportunity to a higher TC. There is even a strategy called Boomerang where you jump to another company for about 1~2 years and jump back to your current company which will result in a higher TC. (The more experience you have, the harder the interviews will be. So jump NOW if you are not at your dream company so you can move while the interview is relatively easier.)**
       * Talk with your lead about how to grow
       * Now start thinking about HLD (system design / architecture)
       * Take on a Co-op/intern to mentor/manage if there is an opportunity
       * Start making an impact on the team.
           * Code reviews
           * Documenting stuff
           * Helping Level 1s and Co-ops/interns
           * Initiating something
           * Do interviews
       * Start thinking about KPIs/metrics.
       * Start reading tech blogs whenever you have free time.
       * Books
           * DDIA (Designing Data-Internsive Applications)
   * Level 3 (Senior)
       * This is the level most engineers stop at. Companies won’t force you to level up anymore. You will only level up only if you push yourself hard.
       * Books
	       * Staff Engineer: Leadership beyond the management track
		       * You are reading "Staff Engineer" when you are a senior engineer so you can become a staff engineer. Similar for the books mentioned for level 1 & 2.
   * Level 4 (Staff / Principal depending on the company)
       * TBD
   * Level 5+
       * I don’t know. How do you get there?

## Case Study
   * [An inspiring story of the author who wrote "Ten Rules for Negotiating a Job Offer" on how he cracked the top tier tech interviews without a CS degree](https://haseebq.com/farewell-app-academy-hello-airbnb-part-i/) 
   * [Story of an engineer getting 10 offers in 100 days](https://dev.to/stopachka/10-offers-100-days-lessons-behind-the-scenes-of-an-l6-jobsearch-535j) 
   * [How to use your personal projects to get job offers](https://www.reddit.com/r/cscareerquestions/comments/vxd8zs/i_posted_my_project_on_reddit_and_received_9_job/) 

## Additional Materials
   * [Job Search Guideline for Senior Levels](https://www.jobsearch.dev/)
   * [Big O CheatSheet](https://www.bigocheatsheet.com/)
   * [Cooldown periods for applications](https://leetcode.com/discuss/career/771157/cool-down-period-for-all-faangs-number-of-tries-and-different-job-posts) 


