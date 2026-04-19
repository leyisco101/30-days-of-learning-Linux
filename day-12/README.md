# Day 12 - [Users and Groups]

## Objective

What was the goal for today?

The goal for today was to understand how Linux manages users and groups, and how permissions are controlled to ensure system security.


## What I Learned

I learnt how to create new user and also add new user 

I learnt how to switch users

I learnt how to create and add groups

I learnt how to set or change a user password

I learnt how to list groups also display current user

Linux is a multi-user system where multiple users can access the system at the same time.

A user represents a person or a service account (e.g., root, ubuntu, airflow).

A group is a collection of users with shared permissions.

The root user has full administrative privileges.

Users and groups help control access and maintain system security


## What I Built / Practiced

Checking current user:

whoami

Viewing user and group information:

id

Creating a new user:

sudo useradd analyst

Setting a password:

sudo passwd analyst

Switching users:

su analyst

Adding a user to a group:

sudo usermod -aG data-team analyst

Checking groups:

groups



## Challenges Faced

Understanding the difference between useradd and adduser.

Knowing when to use sudo for administrative tasks.

Trying to type a passwoard unknowing that its hidden like invisible

Mixing passwords for different users together.



## Key Takeaways

Linux uses users and groups to manage access and permissions.

The root user has full control over the system.

sudo allows temporary administrative access.

Group management is essential for controlling shared access.


## Resources

https://github.com/Najeeb-Sulaiman/linux-and-bash-scripting-guide/blob/main/03-linux-user-management/01-users-and-groups.md



## Output


   whoami
   id
   id adeleye
   id adepoju
   adduser adeleye11
   adduser adeleye
   sudo useradd analyst
   analyst
   id analyst
   sudo usermod -aG data-team analyst
   sudo groupadd data-team
   sudo usermod -aG data-team analyst
   id analyst
   groups analyst
   su analyst
  sudo passwd analyst
  su analyst
  su analyst
  whoami
  history
