# gcp
google cloud Data Platform 
Serverless Machine Learning - Lab 1 : Create ML datasets v1.3
Task 1. Launch Cloud Datalab
To launch Cloud Datalab:

In Cloud Shell, type:

datalab create dataengvm --zone us-central1-a

Datalab setup will prompt you to continue. Enter 'Y'.
Example

Connecting to dataengvm.
This will create an SSH tunnel and may prompt you to create an rsa key pair. To manage these keys, see https://cloud.google.com/compute/docs/in
stances/adding-removing-ssh-keys
Waiting for Datalab to be reachable at http://localhost:8081/
This tool needs to create the directory
[/home/yourprojectid_student/.ssh] before being able to generate SSH
 keys.
Do you want to continue (Y/n)?  Y

Datalab setup will ask you for a passphrase. You can press Enter twice.
Example

Enter passphrase (empty for no passphrase):
Enter same passphrase again:

Datalab will take about five minutes to start. Datalab is ready when you see a message prompting you to do a "Web Preview".
Example

The connection to Datalab is now open and will remain until this command is killed.
Click on the *Web Preview* (square button at top-right), select *Change port > Port 8081*, and start using Datalab.
