<h1>Linux Systems Administration</h1>

 ### [Project Write-Up](https://docs.google.com/document/d/1E1Q7zHJkWDuvbriCAAf92yQPzCrfM_BHq9UOIW5AUEo/edit)

<h2>Description</h2>
Project consists of acting as a system administrator in order to troubleshoot a malfunctioning Linux server. Completed everal steps to prepare another server to replace the malfunctioning server.
<br />


<h2>Steps Taken</h2>

- <b>Step 1: Ensure Permissions on Sensitive Files
The /etc/ directory is where system configuration files exist. Start by navigating to this directory with cd /etc/.

Inspect the file permissions of each of the following files. You should have already done this during an in-class activity, but double check them now. If any file's permissions do not match the descriptions listed here, update the file's permissions.

1. Permissions on /etc/shadow should allow only root read and write access.

2. Permissions on /etc/gshadow should allow only root read and write access.

3. Permissions on /etc/group should allow root read and write access, and allow everyone else read access only.

4. Permissions on /etc/passwd should allow root read and write access, and allow everyone else read access only.</b>

- <b>Step 2: Create User Accounts
In this step, you'll set up various users in the system. For this exercise, use the useradd command. Research this command to determine how to best use this tool to create the user accounts. The necessary commands do not require that you work from a specific directory.

1. Add user accounts for sam, joe, amy, sara, and admin1.
2. Make sure that only the admin1 user has general sudo group access. This requires a command that will allow user modifications. </b>

- <b>Step 3: Create User Group and Collaborative Folder
Now, you'll run the commands to fully set up a group on your system.

This requires you to create a group, add users to it, create a shared group folder, and set the group folder owners for this shared folder.

1. Add the group engineers to the system.

2. Add users sam, joe, amy, and sara to the managed group. The process is similar to the one you used to add admin1 to the sudo group in the previous step.

3. Create a shared folder for this group: /home/engineers.

4. Change ownership on the new engineers' shared folder to the engineers group. </b>

- <b>Step 4: Lynis Auditing
The final step on your administrator's list involves running an audit against the system in order to harden it. You'll use the system and security auditing tool Lynis to do so.

1. Install the Lynis package to your system if it is not already installed.

2. Check the Lynis documentation for instructions on how to run a system audit.

3. Run a Lynis system audit with sudo.

4. Provide a report from the Lynis output with recommendations for how to harden the system.

<h2>Environments Used </h2>

- <b>Azure Web Lab, Windows 10</b>

<h2>Instructor Comments:</h2>

- <b>Comments:
Hello Sean, Thank you for your submission. By completing this assignment, you've begun to develop and demonstrate valuable Linux system admin skills in the process of repairing a malfunctioning server. After reviewing your deliverable, we provide the following comments and feedback: • You correctly double-checked permissions on the four assigned files. • You correctly implemented the commands to check and set /etc/shadow permissions, /etc/gshadow permissions, /etc/group permissions and /etc/passwd permissions. • You successfully created user accounts by executing the correct five commands to add users and the admin user as well. • You executed the correct commands to add an engineers group to the system, add users to that respective collaborative group, and create a shared folder for this data. • You execute the appropriate commands to install and run Lynis, view documentation, and run the audit. You also provided a screenshot of the hardening suggestions output. In summary, you did a fantastic job with this assignment</b>
