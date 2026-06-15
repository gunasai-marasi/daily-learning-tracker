# Day 02 - Database and OOP Fundamentals

## Database Concepts

### Primary Key
Unique identifier for a record.

Example:
emp_id

### Foreign Key
Used to connect tables.

Example:
dept_id in Employee table references Department table.

## Relationships

### One-to-One
Employee -> Badge

### One-to-Many
Employee -> Leave Requests

### Many-to-One
Many Employees -> One Department

### Many-to-Many
Students -> Courses

## OOP Concepts

### Class
Blueprint or template.

Examples:
Employee
Department
LeaveRequest

### Object
Actual instance created from a class.

Examples:
Guna
Ram
Alvin

### __init__()
Used to initialize object data during creation.

Example:
Employee(101, "Guna", "IT")

### self
Represents the current object.

## Key Understanding

Database Table ≈ Python Class

Database Row ≈ Object

## Outcome

Understood:
- Primary Key
- Foreign Key
- Relationships
- Class
- Object
- __init__()
- self