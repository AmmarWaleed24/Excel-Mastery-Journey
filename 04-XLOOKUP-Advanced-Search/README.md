# 🔍 Lesson 04: XLOOKUP - The Ultimate Search Function

## 🎯 Objectives
Mastering the **XLOOKUP** function to replace legacy functions like VLOOKUP and HLOOKUP, ensuring more robust and flexible data retrieval.

---

## 🛠 Skills Applied
- **Vertical & Horizontal Search:** Searching for data in any direction (left or right).
- **If Not Found:** Using the built-in error handling to display custom messages instead of `#N/A`.
- **Match Mode:** Understanding exact matches and wildcards without the need for sorted data.
- **Search Mode:** Learning how to search from the first-to-last or last-to-first (very useful for finding the latest transaction).

## 📊 Practical Application
In the file `04-XLOOKUP-Practice.xlsx`, I created:
1. A **Data Source** table containing Product IDs and Prices.
2. A **Search Interface** where the user enters an ID, and the price is retrieved automatically.
3. Added a custom message "Product Not Found" for invalid IDs.

### Formula Example:
`=XLOOKUP(A2, Products!A:A, Products!B:B, "Not Found")`

---
*Next Step: Summarizing thousands of rows using Pivot Tables.*
