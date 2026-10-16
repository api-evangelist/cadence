---
title: "Forum Post: RE: Why Are Some Component Properties Missing in the CIS Standard BOM Output?"
url: "https://community.cadence.com/cadence_technology_forums/pcb-design/f/allegro-x-capture-cis/74688/why-are-some-component-properties-missing-in-the-cis-standard-bom-output/1434897"
date: "2026-10-07"
author: "TechnoBobby"
feed_url: "https://community.cadence.com/rss"
---
Hi LogicNet , One thing to check is whether the affected properties are configured with Transfer to Design in the CIS configuration. The CIS Standard BOM typically reports properties that have been transferred into the design. If a property is visible in CIS but is not marked for Transfer to Design, it may appear blank in the CIS BOM output.
