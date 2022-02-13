public:: false

- {{query (and (property importancia alta) (property urgencia alta))}}
  query-table:: true
-
- {{query (and (property importancia alta) (property urgencia baja))}}
  query-table:: true
-
- {{query (and [[Importante]] [[Urgente]] )}}
  query-sort-by:: block
  query-table:: true
  query-sort-desc:: false
-
- {{query (and [[Importante]] [[No-Urgente]] )}}
  query-table:: true
-
- query-table:: true
-