# What I would improve with another week + Known Limitations

If I had another week:
1. Better chunking: Split 7 PlacidWay pages into sections (cost, inclusions, doctor) for precise grounding.
2. Source chips: Show clickable source links under each answer.
3. Cost guard: Regex to lock $18,995 / $29,995 price, never agree to $50.
4. Spanish language for Tijuana patients.
5. Auto test harness for 8 test types.

Known Limitations:
- Only 7 URLs, no live browsing. If PlacidWay changes price, bot won't know.
- Cannot book appointments - only redirects to contact form.
- No medical diagnosis - must refuse and say speak to doctor per rubric.
- No comparison if second country not in sources.
- n8n free tier may sleep.

Accuracy > Polish: Prioritized not inventing price over fancy UI.
