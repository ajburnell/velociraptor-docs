---
title: hunt_flows
index: true
noTitle: true
no_edit: true
---



<div class="vql_item"></div>


## hunt_flows
<span class='vql_type pull-right page-header'>Plugin</span>



<div class="vqlargs"></div>

Arg | Description | Type
----|-------------|-----
hunt_id|The hunt id to inspect.|string (required)
start_row|The first row to show (used for paging).|int64
limit|Number of rows to show (used for paging).|int64

### Description

Retrieve the flows launched by a hunt.

A Velociraptor hunt is just a collection of related flows. This
plugin simply enumerates all the flows as part of this hunt.

You can use this to figure out if all the collections were
successful by looking at the result of each flow object.


