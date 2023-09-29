---
content_type: page
description: Readings and discussion questions for a lecture on degrees of consistency.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 14: Degrees of Consistency'
uid: 08e7d76a-03d5-dddb-0d61-b0f5d06eecc5
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Read:

Gray, Jim, et al. "Granularity of Locking and Degrees of Consistency in a Shared Data Base." From _Modeling in Data Base Management Systems_. Edited by G. M. Nijssen. 1976. In the Red Book.

This paper presents two distinct ideas: first, the notion that there is a "hierarchy of locking" — e.g., that databases can lock pages, tables, tuples, or fields, and that there is a tradeoff between these various degrees of locking. Second, the paper presents that idea that there are different degrees of consistency which transactions can require, and those different degrees imply different locking disciplines with different performance characteristics.

As you read the paper, consider the following questions:

1.  What is the tradeoff between coarse granularity (e.g., table-level) and fine granularity (e.g., tuple-level) locks in a database system?
2.  How does hierarchical locking help address the phantom problem (hint: see page 374 and the discussion of index-interval locks.)
3.  What are the performance tradeoffs between the different degrees of locking?
4.  How does degree-0 locking ensure compatibility with all other locking modes?