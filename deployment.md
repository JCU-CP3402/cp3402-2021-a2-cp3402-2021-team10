The deployment workflow of the project is as follows:

First, you need to be invited as a collaborator of the local environment and theme repository on Github.

Run the website in the local environment and load the theme into the local environment.

Export site backup file

Configure the server in vultr, use Xshell, XFTR is used to view the server, and intuitive control
 
Install LEMP environment

Upload the backup file to the staging server

Assign administrators to group members on the staging server running WP, and invite them to edit together

Check the changes to the staging server and whether there are any errors in the staging server

If everything is normal, the leader will export the staging server backup file and upload it to the production server

Apply for a free domain name and resolve it, configure the domain name on the server
