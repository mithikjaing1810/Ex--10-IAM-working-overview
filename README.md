## Ex--10-IAM-working-overview

## Aim:
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

## Procedure
1. Start the AWS Lab and open the AWS Management Console.

2. Open IAM → Users and verify user-1, user-2, and user-3.

3. Open User groups and verify the groups S3-Support, EC2-Support, and EC2-Admin and their attached policies.

4. Add:

     user-1 → S3-Support

     user-2 → EC2-Support

     user-3 → EC2-Admin

5. Open the IAM Sign-in URL and sign in as each user using the given lab credentials.

6. Test user-1: verify S3 access and confirm EC2 access is denied.

7. Test user-2: verify EC2 read-only access and confirm that stopping an EC2 instance is denied; verify S3 access is denied.

8. Test user-3: open EC2, select LabHost, and stop the instance successfully.

9. Submit the lab and check the Grades/Submission Report.

10. End the lab after completing all tasks.

## Output:

<img width="1343" height="683" alt="image" src="https://github.com/user-attachments/assets/4180f708-053b-4ab5-92d9-91181ef34550" />
<img width="1337" height="677" alt="image" src="https://github.com/user-attachments/assets/68e7b753-fb4f-4951-840a-cd2dc2f063aa" />
<img width="1337" height="682" alt="image" src="https://github.com/user-attachments/assets/7e94042c-3157-4d3e-80b1-4b1d4dd008eb" />
<img width="1323" height="560" alt="image" src="https://github.com/user-attachments/assets/2304bd64-ebc2-47c8-948e-9457689f1ec9" />
<img width="1512" height="771" alt="image" src="https://github.com/user-attachments/assets/a9c99cb4-5713-48c5-8458-9501ddb965cc" />
<img width="1191" height="743" alt="image" src="https://github.com/user-attachments/assets/61a89078-e377-4861-85c1-03cefb256f05" />


## Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.



