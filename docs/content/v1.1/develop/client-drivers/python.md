---
title: Python
linkTitle: Python
description: Develop Python Apps
block_indexing: true
menu:
  v1.1:
    identifier: client-drivers-python
    parent: client-drivers
    weight: 556
---

<ul class="nav nav-tabs nav-tabs-yb">
  <li>
    <a href="#cql" class="nav-link active" id="cql-tab" data-toggle="tab" role="tab" aria-controls="cql" aria-selected="true">
      <i class="icon-cassandra" aria-hidden="true"></i>
      YCQL
    </a>
  </li>
  <li>
    <a href="#redis" class="nav-link" id="redis-tab" data-toggle="tab" role="tab" aria-controls="redis" aria-selected="false">
      <i class="icon-redis" aria-hidden="true"></i>
      YEDIS
    </a>
  </li>
  <li>
    <a href="#ysql" class="nav-link" id="ysql-tab" data-toggle="tab" role="tab" aria-controls="ysql" aria-selected="false">
      <i class="icon-ysql" aria-hidden="true"></i>
      YSQL
    </a>
  </li>
</ul>

<div class="tab-content">
  <div id="cql" class="tab-pane fade show active" role="tabpanel" aria-labelledby="cql-tab">
    {{% includeMarkdown "cassandra/python.md" /%}}
  </div>
  <div id="redis" class="tab-pane fade" role="tabpanel" aria-labelledby="redis-tab">
    {{% includeMarkdown "redis/python.md" /%}}
  </div>
  <div id="ysql" class="tab-pane fade" role="tabpanel" aria-labelledby="ysql-tab">
    {{% includeMarkdown "ysql/python.md" /%}}
  </div>
</div>
