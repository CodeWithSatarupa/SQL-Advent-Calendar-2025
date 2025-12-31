# SQL Advent Calendar – Day 12 🎄

## North Pole Network Most Active Users 🧑‍💻❄️

**Difficulty:** Hard 💀

**Question:**  
The North Pole Network wants to see **who's the most active in the holiday chat each day**.  
Write a query to **count how many messages each user sent**, then find the **most active user(s) each day**.  
If multiple users tie for first place, return **all of them**.

**Tables:**

**npn_users**

| Column    | Type    |
|-----------|---------|
| user_id   | INT     |
| user_name | VARCHAR |

**npn_messages**

| Column      | Type      |
|------------|-----------|
| message_id  | INT       |
| sender_id   | INT       |
| sent_at     | TIMESTAMP |
