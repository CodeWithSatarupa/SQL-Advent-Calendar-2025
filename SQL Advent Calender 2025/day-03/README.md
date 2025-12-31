# SQL Advent Calendar – Day 3 🎄

## The Grinch's Best Pranks Per Target 😈🎁

**Difficulty:** Hard 💀

**Question:**  
The Grinch has brainstormed a ton of pranks for Whoville, but he only wants to keep the **top prank per target**, with the **highest evilness score**.  
If two pranks have the same evilness, the more recently brainstormed prank wins. Return the most evil prank for each target.

**Table:** `grinch_prank_ideas`

| Column            | Type      |
|------------------|-----------|
| prank_id          | INTEGER   |
| target_name       | VARCHAR   |
| prank_description | VARCHAR   |
| evilness_score    | INTEGER   |
| created_at        | TIMESTAMP |
