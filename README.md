HelloWorld Servlet example with corresponding Dockerfile

Use Maven Build first to create war file in Target folder.

mvn clean package

Artifact will be created in target folder.

docker build -t mavenbuild .

Once this is done u will be see image using docker images

Use below command to run the container

docker run -d -p 8080:8080 --name mavenbuild mavenbuild

Forked from Anuj's repository and testing PollSCM

Trying Jenkins build to execute shell command  March 22 2020
Invoke top-level Maven targets - clean install
GitHub - Jenkins WebHook
Doing the change again for webhook config is working or not
WebHook try3 
Try4 with newKey
5th  Try


5th Try was successful .. tyring again 6th time

publish java xml report
webhook try
