# Database Design and Normalization

## Goal

A database should be designed so it is structured, consistent, and easy to maintain.

## Normalization

Normalization reduces duplication and improves data quality.

The main levels are:

- 1NF: atomic values and unique rows
- 2NF: no partial dependence on a composite key
- 3NF: no transitive dependency

## Example

Instead of storing all member and booking data in one table, split the system into related tables such as:

- Members
- Trainers
- Classes
- Bookings

This improves consistency and reduces repeated data.

## Why it matters

It helps ensure referential integrity and easier maintenance.
