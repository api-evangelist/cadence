---
title: "Forum Post: dbGetTrueOverlaps with diagonals"
url: "https://community.cadence.com/cadence_technology_forums/f/custom-ic-design/74693/dbgettrueoverlaps-with-diagonals"
date: "2026-10-08"
author: "RC202602061219"
feed_url: "https://community.cadence.com/rss"
---
I am trying debug a skill script which involves finding abutting shapes. lpp = selectedObj~>lpp bbox = selectedObj~>bBox overlaps = dbGetTrueOverlaps(cv bbox lpp 0) I found that shapes with diagonals don't work well. With object 'A' selected it returns 'B' as overlapping but not the other way round.
