# 6-Week Learning Plan: Data Testing

Week 1 — Environment & Python basics
- Install Python 3.10+, create a virtualenv, install: jupyter, pytest, pandas, sqlalchemy, sqlite3 (or psycopg2).
- Learn Python syntax, data types, control flow, functions.
- Deliverable: Jupyter notebook with a sample CSV cleaning script.

Week 2 — Python practice & testing fundamentals
- Modules, file I/O, exceptions, basic OOP.
- Learn pytest and write unit tests for data-cleaning functions.
- Deliverable: test-driven data-cleaning function + 5 pytest tests.

Week 3 — SQL fundamentals & DB practice
- SELECT, JOINs, GROUP BY, window functions, DDL/DML.
- Practice in SQLite or Postgres; write validation queries (uniqueness, nulls, ranges).
- Deliverable: SQL notebook with validation queries.

Week 4 — Pandas deep dive & data validation patterns
- DataFrame/Series, indexing, merging, groupby, reshaping, missing data handling.
- Implement validation checks (schema, ranges, uniqueness).
- Deliverable: notebooks with validation functions and tests.

Week 5 — Data testing tools
- Great Expectations expectation suites, dbt tests (optional), pytest integration with SQL/pandas.
- Deliverable: expectation suite for a dataset and CI-friendly test run.

Week 6 — Projects, CI integration & capstone
- Build pipeline: ingest CSV → transform → load (SQLite/Postgres).
- Add automated tests (unit + expectations + dbt tests) and GitHub Actions workflow.
- Deliverable: repo with pipeline, tests, and CI workflow.

Resources & pacing: 6 weeks, 6–10 hours/week. Key resources: Python docs, pandas docs, Mode SQL, Great Expectations tutorials, dbt Learn, pytest docs.
