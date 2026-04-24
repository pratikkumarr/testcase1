Test Case 1 — Linux System Audit & User Management
Scenario: You are a Linux system administrator onboarding new employees at a tech company. Complete the following tasks on your system.

Tasks
Check the identity of the currently logged-in user and display the username of the current session.

Check which users are currently logged into the system and what they are doing.

View the login history of the system.

Display complete system information, the hostname, and how long the system has been running.

Create two groups: developers and qa. Verify both groups were successfully created and display the complete list of groups on the system.

Create the following users and assign each to their respective group:

Employee	Department
aman	developers
ritu	developers
karan	qa
Employee ritu has resigned. Ensure she has no active sessions, delete her account along with her home directory, and verify she no longer exists on the system.

Expected Outcome
System audit commands display current user, active sessions, login history, hostname, and uptime without errors.
Groups developers and qa appear in the system group list.
Users aman and karan are created and assigned to the correct groups (verified via id command).
After deletion, any attempt to look up ritu returns: "no such user".