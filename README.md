# AP-Project
This is a repository for our AP project based on designing a FMS system.
    
    Contributors: Rupal Jain(2015081) and Gargi Gupta(2015029)
    Following is the description of what and how we plan to go about it.

    Use Cases:
    1. User choice
    2. GM Check
    3. Login
    4. Registration
    5. Add
    6. Delete by GM
    7. View by GM
    8. Check
    9. Approve
    10. Assign
    11. Add by supervisor
    12. View by supervisor
    13. Delete by supervisor
    14. Logistics
    15. New logistics
    16. Update status
    17. Leave by staff
    18. Task report
    19. View task
    20. Assign by supervisor
    21. Supervisor check
    22. Logout
    23. Leave by supervisor

-->Design analysis of the project (Brief description of our FMS system and it’s use cases):

1. Due to obvious reasons, we have considered that GM/admin already exist because without
them the system can’t exist. So to initiate the system, admin needs to be present at the least.

2. In the diagram we have taken admin(already existing), supervisor and staff. And rest is the
system having various use cases(i.e. the specific functionalities). And they can balog to any of
the 5 departments.

3. At the very first step, user is asked to enter his choice(as to which department he belong/will
belong to.

4. Then as per the department he chooses, he is again prompted to enter another choice for sign
up/login.

5. Sign-up: In this case, admin puts a check whether he allows the user to be added to the
system or not. If yes, he is be added to the respective database(based on the department), else
rejected and returns back to the user choice page.

*Login: In this case, the functionalities channel for him opens(based on his post and department).

6. ADMIN: he can perform various functionalities(use cases) like:
1. Delete: he can delete a staff member/supervisor. Then it is being removed from Database.
2. View: Same as above.
3. Assign: He can assign a particular task to any staff member or supervisor. This will be taken an input string and added to the database.
4. Approve/reject: He holds the right to approve/reject any kind of request from supervisor or staff member.


7. SUPERVISOR: he can perform various functionalities(use cases) like:
1. Add: he can add the staff member. If so, his entry will be added to the database.
2. Delete: same as above
3. View: he can choose to view the details/working of his staff member and give his feedback to the staff members.(this feedback use case will be extended from the View use case since this is completely optional for the supervisor.
4. Assign: Can assign task to the staff members and the details of the task will be accordingly added to the database of the staff.
