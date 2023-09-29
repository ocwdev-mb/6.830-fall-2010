---
content_type: page
description: Readings and discussion questions for a lecture on parallel and distributed
  query processing.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 16: Distributed Transactions'
uid: 66567cf1-bcf6-6bb7-3302-5efcf677f715
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

We will continue our discussion of parallel and distributed query processing. You should read:

Mohan, C., B. Lindsay, and R. Obermarck. "Transaction Management in the R\* Distributed Database Management Systems." _ACM Transactions on Database Systems_ 11, no. 4 (1986): 378-396. In the Red Book.

This paper discusses distributed transactions, addressing the problem of providing ACID-style semantics in a shared nothing environment.

As you read the paper, consider the following questions:

1.  In the "R\*" paper, how does the two phase commit (2PC) protocol work? What problem does it solve? What are the costs of using it?
2.  What is the significance of the Presumed Abort/Presumed Commit variants of 2PC? How do they reduce the overhead of 2PC? When should you choose one over the other?