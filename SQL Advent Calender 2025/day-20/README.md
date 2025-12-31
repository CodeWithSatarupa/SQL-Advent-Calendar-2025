# SQL Advent Calendar – Day 20 🎄

## Hot Cocoa Break Logs ☕❄️

**Difficulty:** Medium ⚡

**Question:**  
Jack Frost wants to review all the **cocoa breaks** he actually took — including the **cocoa type** and the **location** he drank it in.  
Combine the necessary tables to show each logged break with its matching **cocoa details** and **location**.

**Tables:**

**cocoa_logs**

| Column   | Type |
|----------|------|
| log_id   | INT  |
| break_id | INT  |
| cocoa_id | INT  |

**break_schedule**

| Column      | Type |
|-------------|------|
| break_id    | INT  |
| location_id | INT  |

**cocoa_types**

| Column     | Type    |
|------------|---------|
| cocoa_id   | INT     |
| cocoa_name | VARCHAR |

**locations**

| Column       | Type    |
|--------------|---------|
| location_id  | INT     |
| location_name| VARCHAR |
