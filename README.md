## Ex--10-IAM-working-overviewAim
## NAME: Priyan V
## REG NO: 212224230211
To explore and configure AWS Identity and Access Management (IAM) users, groups, and policies, and to verify permissions for accessing Amazon S3 and Amazon EC2 resources.

### Aim

To explore and configure **AWS Identity and Access Management (IAM)** users, groups, and policies, and to verify permissions for accessing **Amazon S3** and **Amazon EC2** resources.

### Algorithm

1. Sign in to the **AWS Management Console** and open the **IAM** service.
2. Create an **IAM user** with the required login credentials.
3. Create an **IAM group** for managing users with similar permissions.
4. Create or attach appropriate **IAM policies** to the group.
5. Add the IAM user to the created group.
6. Assign permissions for accessing **Amazon S3** and **Amazon EC2** resources.
7. Sign in using the IAM user's credentials.
8. Try to access the permitted S3 and EC2 resources.
9. Verify that the user can perform only the actions allowed by the attached policies.
10. Record the results and confirm that IAM permissions are working correctly.

### Output
<img width="1787" height="912" alt="image" src="https://github.com/user-attachments/assets/563afd90-869e-4639-a592-e8c70f29a76a" />
<img width="1906" height="901" alt="image" src="https://github.com/user-attachments/assets/8cd0fa8a-3b4b-4e2e-8546-56fa383f7883" />
<img width="1678" height="830" alt="image" src="https://github.com/user-attachments/assets/961cf737-f673-4cb5-8417-7e99ce13b4ee" />
<img width="1783" height="942" alt="image" src="https://github.com/user-attachments/assets/e067e3d2-ddf8-4c09-8e17-8568119296e9" />
<img width="1912" height="761" alt="image" src="https://github.com/user-attachments/assets/1a1b6bb8-395d-43fb-9f93-85b17746e2eb" />
<img width="1917" height="1012" alt="image" src="https://github.com/user-attachments/assets/10442d0a-d652-4052-a51d-47132a7ecd81" />
### Result
The IAM users were successfully assigned to their respective groups, and the required permissions were verified. user-1 received S3 read-only access, user-2 received EC2 read-only access, and user-3 received EC2 administrative access to start/stop instances. Thus, IAM users, groups, policies, and permissions were successfully explored and tested.
