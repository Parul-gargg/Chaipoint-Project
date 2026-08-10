# ChaiPoint Express — Task Notes

## The Project

ChaiPoint Express runs 3 tea cafés in Delhi NCR — Connaught Place, Karol Bagh, and Noida Sec 18. The owner, Sharma ji, has 6 months of billing data (Jan–Jun 2026) and three gut feelings he wants checked:

1. "Mornings are our goldmine on weekdays, evenings on weekends — but I'm staffing everyone the same all day."
2. "I feel we'd make more money if people bought a samosa with their chai. Should I launch a combo?"
3. "Something is off at the Noida outlet but I can't tell what."

**Goal:** answer his three questions with numbers, and give him one page of advice.

Reference list for `Chaiwala.ipynb`. Each task below matches a section in the notebook.

**T1 — Clean.** Find and fix: duplicates, item-name casing, negative quantities, missing `payment_mode`. Count each problem before fixing it. Compare item-name count before vs after cleaning.

**T2 — Join & money columns.** Merge `sales` with `menu` to get `category` and `cost`. Compute `revenue` and `margin` per row. Watch the `price` column collision on merge.

**T3 — Headline.** Total revenue, total margin, margin %. Which category earns the highest margin %?

**T4 — The rush hours.** For weekdays and weekends separately, find which hours bring the most revenue. Make one chart Sharma ji can read in 10 seconds.

**T5 — The combo question.** What % of chai bills have no snack? If a third of those bills added one ₹25 samosa, how much extra margin per month is that?

**T6 — The Noida mystery.** Compare each outlet's average daily revenue on weekdays vs weekends. What is different about Noida?

**T7 — Summer check.** How does the Cold Beverage share of revenue change from Jan–Mar to Apr–Jun? What should Sharma ji do about the menu board in summer?

**T8 — One-page advice.** Three recommendations, each with its number.
