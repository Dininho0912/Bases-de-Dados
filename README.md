# Databases (BD)

SQL schemas, datasets, and NoSQL query exercises from the Databases course.

## Contents

- **`sqlite/`** — Relational database schemas, data dumps, and SQL scripts (`carRepairShop.sql`, `districts.sql`, `elections.sql`, `helloworld.sql`).
- **`Aula11`** — MongoDB / NoSQL shell query exercises.

## Usage

Load any `.sql` script into a local SQLite database:

```bash
sqlite3 database.db < sqlite/carRepairShop.sql