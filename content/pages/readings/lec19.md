---
content_type: page
description: Readings and discussion questions for a lecture on Bigtable, a storage
  system for structured data.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 19: NOSQL'
uid: 6868c6cc-27a2-1403-813c-fceeed1d1ca8
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Read:

Chang, Fay, et al. "Bigtable: A Distributed Storage System for Structured Data." OSDI, 2006. ([PDF](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf))

Bigtable is a storage system for structured data; it is essentially a compressed, horizontally partitioned, column-oriented database with some interesting properties that allow it to reach "web scale".

As you read the paper, consider the following questions:

1.  In what ways does Bigtable replicate the behavior of a relational database? How is it different?
2.  Could Google have built Bigtable using a relational system? Would that have been a good idea? Why or why not?
3.  What consistency guarantees does Bigtable provide in the face of failures?
4.  What is a distributed lock service?