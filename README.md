# 🌳 BST Student Record Manager

Manage student records using Binary Search Tree

Total Students**0**

Root Node**–**

Minimum ID**–**

Maximum ID**–**

Tree Height**0**

## Current tree

## Student records

| Student ID | Name | Age | Course | Department | Email | CGPA | Actions |
| --- | --- | --- | --- | --- | --- | --- | --- |

## Add a student

Student ID / Roll Number

Student Name

Age

Course

Department

Email

CGPA

## Tree after insert

## Search by Student ID

Student ID

## Search path

VisitedFound

## Delete by Student ID

Student ID

Handles all three cases: **leaf**, **one child**, **two children** (replaced by inorder successor).

## Tree after delete

## Tree visualization

NormalNewly insertedSearch pathSearchedDeleted

## Traversals

**Inorder** (left, root, right) gives Student IDs in sorted order. **Preorder** visits the root before its children. **Postorder** visits children before the root. **Level order** visits nodes level by level.

## What is a Binary Search Tree?

A tree where each node has at most two children, and:

• Values **smaller** than a node go on the **left**.\
• Values **greater** go on the **right**.\
• Each **Student ID** is the key that organizes records.

## Algorithm complexity

| Operation | Average | Worst |
| --- | --- | --- |
| Search | O(log n) | O(n) |
| Insert | O(log n) | O(n) |
| Delete | O(log n) | O(n) |

The worst case happens when the tree becomes unbalanced. Inserting IDs in sorted order (1, 2, 3, …) turns the tree into a linked list. Try it with the Add tab.