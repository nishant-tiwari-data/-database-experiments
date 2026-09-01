# Database Performance & Internals Lab

Documented experiments measuring query plan behavior, storage internals, and indexing performance in PostgreSQL.

### 🧪 Experiments
1. **Index vs. Sequential Scan:** Cost and buffer comparison on 500k+ row datasets using `EXPLAIN (ANALYZE, BUFFERS)`.
2. **Transaction Isolation & Locks:** Testing dirty reads, non-repeatable reads, and deadlock resolution.
3. **Slowly Changing Dimensions (SCD Type 2):** Point-in-time historical merge logic.
