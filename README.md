# Lahman Databricks Project

This project loads the Lahman Baseball dataset into Delta tables
on Azure Databricks, and builds a gold table for Team OPS by season.

## Notebooks
- `lahman_setup`: creates the `lahman` database and ingests CSV data.
- `lahman_gold_ops`: builds the Team OPS gold table.

## How to Use
1. Run `lahman_setup` first to create and load the data.
2. Run `lahman_gold_ops` to create the gold OPS table and leaderboard view.