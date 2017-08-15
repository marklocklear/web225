J. Mark Locklear
Web225
15Aug17

# General
The rules apply to all the languages below and have broad application regardless of the programming language or frameworking used.

*Database queries*-Avoid touching the database directly. Database abstraction (using functions instead of queries) helps keep your code forward-compatible and, in cases where results are cached in memory, it can be many times faster. The use of ORM’s is recommended when possible. This makes your database functions agnostic which has the advantage of giving developers and sysadmins more flexibility in using a database they prefer and also allowing for a change in a database as an application grows and changes.

PHP
Naming conventions-For general functions or methods use lowercase letters in variable, action/filter, and function names (never camelCase). Separate words via underscores. Don’t abbreviate variable names unnecessarily; let the code be unambiguous and self-documenting.

HTML5

CSS3

JavaScript.
