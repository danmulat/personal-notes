# SQL

**Summary**: Notes on SQL, query engines and database tools, including spatial SQL in DuckDB and PostGIS.
**Last updated**: 2026-11-07

---

- [PostGIS spatial joins, translated to DuckDB](https://www.geomermaids.com/cookbook/duckdb-spatial/): A Geomermaids cookbook page that translates common PostGIS spatial join patterns into DuckDB and compares query plans on FEMA flood data. It explains where DuckDB needs manual help, such as R-tree indexes that only help lookups against a fixed geometry, one spatial predicate per join, metric CRSs for distance joins, and inlined geometries for clipping. *Keywords: DuckDB spatial, PostGIS, spatial joins, query optimization, R-tree index, cloud-native geospatial*
