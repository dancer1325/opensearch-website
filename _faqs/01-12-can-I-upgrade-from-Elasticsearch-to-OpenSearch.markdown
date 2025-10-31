---
question: Can I upgrade from Elasticsearch to OpenSearch?
category: General
---

* ways to upgrade FROM Elasticsearch -- to -- OpenSearch
  * | Elasticsearch [v7.0, v7.10],
    * via rolling upgrade (== upgrade 1 node / time) 
  * | Elasticsearch v6.x,
    * cluster restart upgrade
  * | Elasticsearch v6.0- OR v7.10+,
    * ❌NOT straightforward❌
    * steps
      * reindex | compatible Elasticsearch versions
      * upgrade -- to -- OpenSearch