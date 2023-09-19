---
content_type: page
description: Readings and discussion questions for a lecture on indexing and access
  methods.
learning_resource_types:
- Readings
ocw_type: CourseSection
parent_title: Readings
parent_type: CourseSection
parent_uid: 607e580d-09fd-cfa0-0f08-a87ae0de6ad6
title: 'Lecture 6: Indexing and Access Methods'
uid: f59bf6ba-c7ab-4607-ed75-486674863cd9
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

This lecture will cover various issues related to the physical storage of relations on disk, as well as index data structures we might use to efficient access those stored relations. Read the following (short) papers and book sections:

*   In _Database Management Systems_, read:
    *   Pages 273-289. If you are using another book, this is the introduction to the section on Storage and Indexing which discusses different access methods and their relative performance.
    *   Pages 344-358. This is an in-depth discussion of the B+Tree data structure and its implementation. Most database books, as well as any algorithms text (such as CLR or Knuth) will provide an equivalent discussion of B+Trees.
*   "The R\*-Tree: An Efficient and Robust Access Method for Points and Rectangles." Beckmann et al, in the Red Book.

As you read, think about and come to class prepared to answer the following questions:

*   Under what circumstances is a secondary index superior to a sequential (in-order) scan of a heap file? Under what circumstances would the secondary index scan be preferable?
*   What is the purpose of the neighbor pointers in a B+Tree? When are they useful?
*   Why are B+Trees insufficient for storing and indexing the types of data stored by R\*-Trees?