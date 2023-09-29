---
content_type: page
description: Readings and discussion questions for a lecture on concurrency control
  and optimistic concurrency control.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 11: Optimistic Concurrency Control'
uid: ff78b687-f1a3-e5e0-58c2-ac171ff64a6d
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

In this lecture, we will continue our discussion of concurrency control and study another approach for isolating transactions called "Optimistic Concurrency Control." Read:

Kung, H. T., and John T. Robinson. "On Optimistic Methods for Concurrency Control." _ACM Transactions on Database Systems_ 6, no. 2 (1981): 213-226. In the Red Book.

As you read, note any terms you are unfamiliar with and come to class prepared to answer the following questions:

*   When would you expect that optimistic concurrency control would outperform locking-based concurrency control?
*   Can optimistic concurrency control result in deadlock?
*   How would you implement optimistic concurrency control in SimpleDB?