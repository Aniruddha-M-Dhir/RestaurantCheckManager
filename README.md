# Restaurant Check Manager (Java)

Console program to record restaurant checks and **pool tips**, then allocate them across roles.  
Built for **CSC101**; uses simple input, loops, conditionals, and arithmetic.

---

## What it does
1. Repeats for each check:
   - Ask: total check amount, tip amount, total amount.
   - Auto-fixes missing values (e.g., if tip is `0` but total > check, it computes the tip).
   - Accumulates **total sales** and **total pooled tips**.
2. When you stop, it allocates pooled tips:
   - **Servers:** 40% (split evenly across `server` count)
   - **Kitchen:** 40% total, split as:
     - Chef: 50% of kitchen share
     - Sous Chef: 35%
     - Kitchen Aid: 15%
   - **Host:** 10% of total tips
   - **Busser:** 10% of total tips

---
