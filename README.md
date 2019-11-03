# AnsiblePlaybook_User_Management_Debian
Ansible Playbooks to manage users on Debian Linux based devices

-- create_users_list_playbook.yml
Is a playbook that contains the users with a variable list, creates the users with the password "password", creates a group and adds the users to the group.

-- create_users_from_users_file_playbook.yml
Reads the user variables from the file "users.yml", creates the users with the password "password", creates a group and adds the users to the group.

--  users.yml
Used with "create_users_from_users_file_playbook.yml". Contains a list of usernames to create.


