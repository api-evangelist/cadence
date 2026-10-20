---
title: "Forum Post: RE: Bulk hierarchy path editing of 50 deepprobes, is it possible at all within Virtuoso?"
url: "https://community.cadence.com/cadence_technology_forums/f/custom-ic-design/74710/bulk-hierarchy-path-editing-of-50-deepprobes-is-it-possible-at-all-within-virtuoso/1434950"
date: "2026-10-15"
author: "rod1"
feed_url: "https://community.cadence.com/rss"
---
This procedure worked for me in the end. t_find and t_replace are strings. procedure(sge_replaceProbeNode(t_find t_replace) prog((cv win selObjs probes updated cdf p oldVal newVal) ; Validate that both arguments are strings unless(stringp(t_find) error("sge_replaceProbeNode: argument 'find' must be a string, got: %L" t_find) ) unless(stringp(t_replace) error("sge_replaceProbeNode: argument 'replace' must be a string, got: %L" t_replace) ) probes = list() updated = list() win = hiGetCurrentWindow() unless(win error("sge_replaceProbeNode: No active schematic window found.") ) cv = geGetEditCellV
