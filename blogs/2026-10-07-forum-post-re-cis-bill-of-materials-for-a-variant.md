---
title: "Forum Post: RE: CIS Bill of Materials for a variant"
url: "https://community.cadence.com/cadence_technology_forums/pcb-design/f/allegro-x-capture-cis/74691/cis-bill-of-materials-for-a-variant/1434898"
date: "2026-10-07"
author: "TechnoBobby"
feed_url: "https://community.cadence.com/rss"
---
Hi VKravets , By default, CIS replaces the properties of Do Not Stuff (DNS) components with "Do Not Stuff" and sets the quantity to 0. To display the Part Number for DNS components in the BOM, run the following command in the Capture Command Window: SetOptionString CisBomDisplayPartNumberForDNS TRUE For more details, refer to following article on ASK portal: Title: How can I see the part number of parts that are not present in a variant in CIS BOM? URL: https://ask.cadence.com/ASK/article-viewer?id=a1Od0000000t3flEAA&pageName=article-viewer Hope this helps!
