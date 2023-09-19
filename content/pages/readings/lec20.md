---
content_type: page
description: Readings and discussion questions for a lecture on DryadLINQ, a programming
  language for manipulating structured data in a distributed setting.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 20: ORM, DryadLINQ'
uid: cb945a4c-bc66-de19-5f56-67d51ac78666
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Read:

Yu, Yuan, et al. "DryadLINQ: A System for General-Purpose Distributed Data-Parallel Computing Using a High-Level Language." OSDI, 2008. ([PDF](http://research.microsoft.com/en-us/projects/dryadlinq/dryadlinq.pdf))

DryadLINQ is a programming language for manipulating structured data in a distributed setting. It provides a collection of SQL-like constructs that are well-integrated into C# (with a common type and object system), and compiles down to a graph of operators spread across a distributed network of machines in a way similar to how distributed databases work.

As you read the paper, consider the following questions:

1.  What are the advantages of a query language that is integrated into the programming language? Are there disadvantages?
2.  Dryad execution plans look a lot like database query plans, but are different in some ways — in particular, operators can have multiple outputs; what are the implications of this from a query execution perspective?