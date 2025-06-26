![image](https://github.com/user-attachments/assets/09fb938b-03bf-4fb0-aca2-99b2b21024b0)

# Linux: Manage Users
This project focuses on managing user accounts and permissions in a Linux environment using command-line tools. Tasks include creating, modifying, and deleting user accounts.


# Environments and Technologies Used</h2>
- Google Cloud Virtual Machines.
- Various Linux commands.

# Operating Systems Used </h2>
- Linux.

# Actions and observations
In this scenario, a new employee with the username researcher9 joins an organization. We have to add them to the system and continue to manage their access during their time with the organization.

![image](https://github.com/user-attachments/assets/129aa005-7f21-426c-992a-95825f5bcff1)

- Adding User(researcher 9) using superuser do useradd.

![image](https://github.com/user-attachments/assets/eee194e4-9ae9-4d8f-913d-283405b45979)

- Adding  User(researcher 9) to the research_team using sudo -g command.

![image](https://github.com/user-attachments/assets/ca3ee28f-69b0-4fba-8d1c-4c7b4521d12b)

- Giving User(researcher 9) ownership project_R.txt located in /home/researcher2/projects with the chown command.

   A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.

 ![image](https://github.com/user-attachments/assets/75a756d7-958c-4bf0-a749-00c7eb961343)

 - Using sudo usermod -a -G to add User(researcher 9) to the sales_team.

     A year later, User(researcher 9) decided to leave the company. In this task, you must remove them from the system.

![image](https://github.com/user-attachments/assets/a93c2788-5478-49ba-84d5-8632f1beb7ea)

 - Trying to delete User(researcher 9) using usedel, but we can't because we have to delete his group.
  
![image](https://github.com/user-attachments/assets/a1edf06e-0906-4b85-bcfb-25647e2d8387)

Using sudo groupdel researcher9 to properly get rid of the user(researcher 9). After removing users, it is good practice to clean up any such empty groups that may remain behind.

   Thanks for making to the end of this lab.🎉
  
   

