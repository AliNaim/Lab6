# Lab6Introduction

In this lab, students will upgrade the spider (also known as crawler) application capable of indexing the local file system, made in lab 4. Version 2 of the local spider will crawl and index the file system, utilizing several threads, while the user queries will be accepted in atleast 2 different threads. The spider will also use checkpoints and a persistent storage mechanism to keep the index available across several different executions. While crawling through the file system, the spider can also pick up metadata information about the files and folders. This includes, size of the file, permissions of the file or directory, number of contents in a folder. The user will still be able to search the index using a keyword but with version 2, you can share more details of each matching value. 

How to run

Open the project in Netbeans
Github Link

https://github.com/AliNaim/Lab6
Analysis

After this lab we would understand
•	Threads
•	Check-Pointing and persistent storage(Database or Files)
•	Concurrency
•	Synchronization 

Objectives

Your task will be to implement the following:
1.	Creating a Multi-threaded local file system crawler with atleast the following independent features:
a.	Crawling Service(with atleast 3 threads)
b.	Indexing Service(with atleast 3 threads)
c.	Searching Service(with atleast 2 threads)
2.	Use a persistent datastore to allow for the following:
a.	Save your index periodically.
b.	Retrieving the index on startup. (Optional)
c.	Avoid researching old, already indexed files.(Optional)
3.	For each file and/or folder keep record of the following:
a.	Keywords in names
b.	Keywords in paths(separated by / or \)
c.	Readable contents of files
d.	File size/Number of sub items in folders  (Optional)
e.	Created Time/Modified Time  (Optional)
f.	Ownership and permission details  (Optional)
4.	Unit tests to evaluate your code.
5.	Using a Version Control System (VCS) to manage your solutions.

