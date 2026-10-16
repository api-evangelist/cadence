---
title: "Forum Post: RE: Question on Skill Code for Cadence Official MOS PCell"
url: "https://community.cadence.com/cadence_technology_forums/f/custom-ic-skill/70345/question-on-skill-code-for-cadence-official-mos-pcell/1434901"
date: "2026-10-08"
author: "SZ20260803361"
feed_url: "https://community.cadence.com/rss"
---
Hi Andrew, I came across a new problem when going over the code and hope to get your input. Code segment with questions (from Cadence official): ;; Route poly if needed when(routePoly && routePoly != "FALSE" && numberOfFingers > 1 strap_width = ((numberOfFingers - 1) * gatePitch) + transistor_length strap_offset = gate_Extension - diffusionGateSpace polyfig = rodCreatePath( ?cvId cellViewId ?layer gateLayer ?width minPolyWidth ?pts list(0:0 strap_width:0) ?termName "G" ?pin t ?termIOType "input" ) cond( ( routePolydir == "Top" rodAlign( ?alignObj polyfig ?alignHandle "lowerRight" ?refObj topPi
