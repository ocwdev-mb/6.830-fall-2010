---
content_type: page
description: Readings and discussion questions for a lecture on query optimization.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 9: Query Optimization'
uid: 75e1c741-b298-9e11-b22a-dd3535db6620
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

In this lecture, we will discuss the problem of query optimization, focusing on the algorithms proposed in the classic "Selinger" paper.

Read the following papers:

*   Selinger, Patricia, M. Astrahan, D. Chamberlin, Raymond Lorie, and T. Price. "Access Path Selection in a Relational Database Management System." _Proceedings of ACM SIGMOD_ (1979): 23-34.
*   _Optionally_, you may also wish to look at: Mannino, Michael, Paichen Chu, and Thomas Sager. "Statistical Profile Estimation in Database Systems." _ACM Computing Surveys_ 20, no. 3 (1988): 191-221. This paper discusses many of the techniques that used to make query optimization and cost estimation practical in modern database systems. We will cover some of the ideas at a high level in class.

As you read, think about and come to class prepared to answer the following questions:

*   The Selinger paper claims to be 'optimal'. Under what assumptions is this optimality true? Can you think of a situation in which Selinger will definitely be non-optimal?
*   Query optimization is highly dependent on the effectiveness of cost estimation. The cost metrics that Selinger proposes are very simple; how would you make them more sophisticated? What is the impact of more sophisticated cost metrics on the performance of a database system?