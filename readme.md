TO make sure ansible work with ssh

1. Make a ssh-keys and send it using ssh-copy-id
2. Configure ssh permission in the clients
3. execute ansible using the private key parameter

To automate
1. make a cronjob
2. cronjob call script
3. script execute ansible

Maybe add notification to inform backup have been created

ansible-playbook -i host/list/dir playbook/dir is the way to go

