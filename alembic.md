# Database Migration Assignment: Add User Roles
 ## Assignment Overview
Objective: Learn how to use Alembic to modify your database schema by adding a new column to the users table.

## What You'll Learn:

How to modify existing database tables using migrations
How to add new columns with default values
How to apply and rollback migrations
The difference between changing code and changing database schema


# The Task
Your marketplace app currently has two user categories: buyer and farmer. However, we need to add administrator functionality.
Your task is to add a role column to the users table that will track whether a user is a regular user or an admin.
Requirements:

- Add a role column to the User model
- The role should be an ENUM with these values:
  - user (regular user - should be the default)
  - admin (administrator)

- Note:
The column should NOT be nullable
Use Alembic migrations (NOT manual SQL or dropping tables!)
Test that you can rollback and reapply your migration
