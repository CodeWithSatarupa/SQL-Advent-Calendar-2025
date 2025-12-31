# SQL Advent Calendar – Day 5 🎄

## Elf Vacation Status 🧝‍♂️🏖️

**Difficulty:** Medium ⚡

**Question:**  
Some elves took time off after the holiday rush, but not everyone has returned to work. List all elves by **name**, showing their **return date**.  
If an elf has not returned from vacation, display the return date as **"Still resting"**.

**Tables:**

**elves**

| Column    | Type    |
|-----------|---------|
| elf_id    | INT     |
| elf_name  | VARCHAR |

**vacations**

| Column       | Type    |
|--------------|---------|
| elf_id       | INT     |
| start_date   | DATE    |
| return_date  | DATE    |
