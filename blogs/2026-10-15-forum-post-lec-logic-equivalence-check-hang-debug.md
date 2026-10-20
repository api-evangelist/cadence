---
title: "Forum Post: LEC (Logic Equivalence Check) hang debug"
url: "https://community.cadence.com/cadence_technology_forums/f/logic-design/74711/lec-logic-equivalence-check-hang-debug"
date: "2026-10-15"
author: "SimhanAnalog"
feed_url: "https://community.cadence.com/rss"
---
For my small register bank design( with 50 flops and some address decoder logic) after synthesis when I try to run lec the rtl2fvmap lec hangs at the step write_hier_compare_dofile hier_tmp2.lec.do -verbose -noexact_pin_match -constraint -usage \ -replace -balanced_extraction -input_output_pin_equivalence \ -prepend_string "report_design_data; report_unmapped_points -summary; report_unmapped_points -notmapped; analyze_datapath -module -verbose; eval analyze_datapath $DATAPATH_SOLVER_OPTION -verbose" the below is the terminal. It is stuck at this state for several hours. -----------------------
