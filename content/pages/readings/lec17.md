---
content_type: page
description: Readings and discussion questions for a lecture on parallel databases.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 17: Parallel Databases'
uid: 9dfb284b-d00a-502f-99f9-a78bd61390ea
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Read:

Dewitt, David, and Jim Gray. "Parallel Database Systems: The Future of High Performance Database Processing." _Communications of the ACM_ 35, no. 6 (1992): 85-98. In the Red Book.

The Dewitt and Gray paper is a high level summary of database architectures for parallelism, illustrating some of the techniques that can be used to exploit the availability of multiple processors in a database system.

Questions to consider:

1.  What's the difference between a parallel and a distributed database? What issues are different in one architecture versus the other? In what ways are the two architectures alike?
2.  Why do Dewitt and Gray advocate a shared nothing architecture?
3.  In what ways must existing database architectures be modified to support multi-processor environments? What new data layout issues are introduced? What new query processing challenges must be addressed?