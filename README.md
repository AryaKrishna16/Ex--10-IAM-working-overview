# Ex--10-IAM-working-overview

Aim:
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

Procedure
Start the AWS Lab and open the AWS Management Console.

Open IAM → Users and verify user-1, user-2, and user-3.

Open User groups and verify the groups S3-Support, EC2-Support, and EC2-Admin and their attached policies.

Add:

user-1 → S3-Support

user-2 → EC2-Support

user-3 → EC2-Admin

Open the IAM Sign-in URL and sign in as each user using the given lab credentials.

Test user-1: verify S3 access and confirm EC2 access is denied.

Test user-2: verify EC2 read-only access and confirm that stopping an EC2 instance is denied; verify S3 access is denied.

Test user-3: open EC2, select LabHost, and stop the instance successfully.

Submit the lab and check the Grades/Submission Report.

End the lab after completing all tasks.

```
E ARYA KRISHNA
212225240014
```

<img width="1876" height="851" alt="Screenshot 2026-08-06 210312" src="https://github.com/user-attachments/assets/3ab881ef-b17e-44e7-853c-62fbd6f3e6cc" />

<img width="1912" height="782" alt="Screenshot 2026-08-06 210618" src="https://github.com/user-attachments/assets/51a2c69e-d4f4-477d-af66-bdaf131cc4cc" />

<img width="1538" height="737" alt="Screenshot 2026-08-06 210912" src="https://github.com/user-attachments/assets/f2b15eba-1a07-4e13-b357-d8304be7c5ed" />

<img width="1907" height="728" alt="Screenshot 2026-08-06 211118" src="https://github.com/user-attachments/assets/35e7e3b7-12b6-4130-842a-94a3366e4444" />

<img width="1817" height="802" alt="Screenshot 2026-08-06 211515" src="https://github.com/user-attachments/assets/0829e5c0-9c7b-438b-a4f2-e9325e890883" />

<img width="1907" height="672" alt="Screenshot 2026-08-06 211922" src="https://github.com/user-attachments/assets/2fe0dd10-d232-4296-9d9e-411eb52779ef" />


Result

The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
