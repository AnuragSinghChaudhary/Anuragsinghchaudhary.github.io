# Legacy Blog Migration Plan

This file captures the first migration batch from the old WordPress export at:

`/Users/anurag/Documents/datasciencepedia_export/`

## Summary

- Exported WordPress posts found: `215`
- Long-form posts worth serious consideration: about `23`
- Medium-length notes worth rewriting: about `21`
- Short bookmark-style posts: about `152`
- Empty or near-empty drafts: about `19`

The export should not be migrated wholesale. Most entries are saved links, half-drafts, or idea stubs rather than finished articles.

## First Batch To Migrate

These six posts best match the current portfolio direction in 2026:

1. `Impact of Air Pollution on Economy`
   - Why it fits: directly supports the air quality and sustainability thread in the portfolio.
   - Action: rewrite and publish first.

2. `Storytelling, Data and the Dashboards`
   - Why it fits: connects analytics, BI, and communication.
   - Action: expand substantially before publishing.

3. `What is GTFS by the way ?`
   - Why it fits: relevant to geospatial, transit data, and applied data products.
   - Action: modernize structure and remove missing images.

4. `Bias & Variance in laymen Terms`
   - Why it fits: evergreen explanatory content.
   - Action: tighten terminology and add a clearer example.

5. `7 Steps of Machine Learning`
   - Why it fits: beginner-friendly evergreen foundation piece.
   - Action: rewrite with clearer language and modern framing.

6. `Public Datasets for doing Data Analysis`
   - Why it fits: useful resource post if curated carefully.
   - Action: republish only after heavy cleanup and link validation.

## Rewrite Pattern

Each migrated legacy post should follow this pattern:

1. Keep the original publication year in the front matter.
2. Add a short editor's note explaining that the piece was refreshed from an older blog.
3. Remove raw bookmark content, dead embeds, and broken image placeholders.
4. Rewrite titles, summaries, and section flow to match the current portfolio tone.
5. Avoid unsupported "latest" claims unless re-verified.

## Do Not Migrate As Individual Posts

These should remain archived unless rewritten into new essays:

- one-line tool links
- saved bookmarks to company engineering blogs
- empty drafts
- posts that are mostly URLs
- broken iframe demos
- outdated setup notes with no commentary

## Status

- First rewritten legacy post added: `content/blog/impact-of-air-pollution-on-economy.md`
- Next recommended rewrite: `Storytelling, Data and the Dashboards`
