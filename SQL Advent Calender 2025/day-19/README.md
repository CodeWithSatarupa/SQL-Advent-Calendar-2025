# SQL Advent Calendar – Day 19 🎄

## Gift Wrap Paper Usage 🎁📏

**Difficulty:** Easy ✅

**Question:**  
Clara is reviewing holiday orders to uncover hidden patterns.  
Return the **total amount of wrapping paper used** for orders that were both **gift-wrapped** and **successfully delivered**.

**Table:** `holiday_orders`

| Column            | Type      |
|------------------|-----------|
| order_id          | INT       |
| customer_name     | VARCHAR   |
| gift_wrap         | BOOLEAN   |
| paper_used_meters | DECIMAL   |
| delivery_status   | VARCHAR   |
| order_date        | DATE      |
