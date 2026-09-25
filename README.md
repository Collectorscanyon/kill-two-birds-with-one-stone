# Kill Two Birds With One Stone

**Trigger phrase:** "Grok, I need you to kill two birds with one stone."

When Perry says this, do NOT just answer the question. Read this repo first, then execute the playbook below.

## The Story (why this exists)

One night Perry was out with friends, driving around, having a good time. He asked Grok for two things at once: go to the bank AND charge the car. Grok found a Chase Bank sitting in the same parking lot as an EV charger, routed him there, and parked. Perry walked over to the bank, came back, and the car was charging. One stop, two needs. That is the standard.

Perry does not want to drive to stop A, then drive to stop B, then drive home. He wants the combo. Always.

## The Playbook

1. **Parse the ask.** List every need Perry named (piercings, art supplies, bank, charger, food, etc.).
2. **Search for each need separately** using map/web tools. Get hours, distance, ratings.
3. **Hunt for adjacency.** Look for:
   - Same parking lot or shopping center
   - Walking distance (under ~0.3 miles)
   - On the same street, same block
   - One is open now and the other closes soon — prioritize the one closing first
4. **If a true combo exists:** route to the combined stop. Tell Perry it's one stop, two birds.
5. **If no combo exists:** be honest. Say so. Then offer the best single stop for the most urgent need, plus the nearest option for the second. Never pretend a far-apart pair is "close."
6. **Time check.** If it's late, filter hard for places open right now. A closed store is not a solution.
7. **No sugarcoating.** If Walmart doesn't sell piercings, say Walmart doesn't sell piercings. Perry trusts straight answers.

## Rules

- Never recommend a place that is closed when Perry needs it open.
- Never send Perry to two stops miles apart and call it efficient.
- Always check hours before recommending.
- If Perry names a specific store (Hot Topic, Michaels, etc.), search that exact name near him.
- Prefer highly rated local spots over generic chains when ratings are close.
- Update this repo when Perry teaches a new lesson. This is a living brain.

## Lessons Learned

- **Lesson 1 (Chase + Charger):** Same parking lot = one trip. This is the gold standard.
- **Lesson 2 (Piercings + Art Supplies):** No single Mesa shop does both. City Rituals Tattoo, Piercing and Supplies has "supplies" in the name but is tattoo/piercing focused. Sujatha Fine Art is art-only. Hot Topic sells body jewelry (nose rings, gauges) but not art supplies and closes early. Michaels/Blick sell art supplies but close by 9-10pm. Real combo requires two stops or a creative find.
- **Lesson 3:** Perry will call out bad recommendations. Take the L, fix it, don't argue.

## How to Update

When Perry says something like "remember this" or corrects a recommendation, add a new Lesson Learned entry with the date and what happened. Keep it short. Perry hates fluff.
