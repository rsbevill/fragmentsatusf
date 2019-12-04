---
layout: page
title: Reuse the Collection
permalink: /reuse/
collection: fragments
---

Sites made with Wax follow [FAIR data principles](https://journal.code4lib.org/articles/13427), and as such strive to make its collections findable, accessible, interoperable and reusable.

The demo site comes with a specific `_include` called `interactive_metadata_table` to help you make pages like this one complete with interactive [DataTables](https://datatables.net/) and downloadable CSVs of collection metadata.

{% include interactive_metadata_table.html collection=page.collection %}
