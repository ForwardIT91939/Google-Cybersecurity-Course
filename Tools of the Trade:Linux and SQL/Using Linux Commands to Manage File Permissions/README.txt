Portfolio Project: Manage File System Permissions using Linux Command

In this project, I have been given a scenario in which I am a security professional at a large organization, working mainly within their research team. 
Part of my job is to ensure users on this team are authorized with the appropriate permissions.
My given task is to examin existing permissions on the files system and will need to determine if the permissions match the authorizationthat should be given.
If they do not match, ill need to modify the permissions to authorize the appropriate suers and remove any unauthorized access.

Baseline information:
In the /home/researcher2/projects directory, there are five files with the following names and permissions: 
project_k.txt
User = read, write, 
Group = read, write
Other = read, write

project_m.txt
User = read, write
Group = read
Other = none

project_r.txt
User= read, write
Group = read, write
Other = read

project_t.txt
User = read, write
Group = read, write
Other = read

.project_x.txt
User = read, write
Group = write
Other = none

There is also one subdirectory inside the projects directory named drafts. The permissions on drafts are:
User = read, write, execute
Group = execute
Other = none
