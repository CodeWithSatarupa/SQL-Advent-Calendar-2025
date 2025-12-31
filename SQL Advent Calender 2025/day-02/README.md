# SQL Advent Calendar – Day 2 🎄

## Toys Delivered - Find Which Toys Made It 🎁🧸

**Difficulty:** Medium ⚡

**Question:**  
Santa wants to analyze which toys produced in his workshop have already been delivered to children. You are given two tables — can you return the **toy_id** and **toy_name** of the toys that have been delivered?

**Tables:**

**toy_production**

| Column          | Type    |
|-----------------|---------|
| toy_id          | INTEGER |
| toy_name        | VARCHAR |
| production_date | DATE    |

**toy_delivery**

| Column         | Type    |
|----------------|---------|
| toy_id         | INTEGER |
| child_name     | VARCHAR |
| delivery_date  | DATE    |
