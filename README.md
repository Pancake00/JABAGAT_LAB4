## LAB ACT 4: Extending Authentication API with SQL JOIN Reports

### JOINs
- Inner Join returns rows where both tables have matching values.
- Left Join returns all rows from the left table plus matches from the right.
- Right Join keeps all rows from the right table.
- Full Outer Join keeps everything from both sides, missing values with NULL.
- Cross Join for generating all combinations.
- Self Join to joined to itself.

### Endpoints
- /reports/users-with-roles show users who have at least one role.
- /reports/users-with-profiles shows all users with their profile info if available.
- /reports/roles-right-join shows all roles even if no users are assigned.
- /reports/profiles-full-outer it combine the users and profiles, keeping unmatched rows from both.
- /reports/user-role-combos it generate every possible user–role pair.
- /reports/referrals shows referral relationships between users.
- /reports/latest-login shows each user with their most recent login.
