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

March 29 changed the ip

wget https://gist.githubusercontent.com/anujdevopslearn/8395705058c9cd4f4f5c3fec5591b246/raw/ca103bfd5a8791c805aaed30efc9c2cb192e7e72/apache.yml

ansible-playbook apache.yml

service apache2 status



wget https://gist.githubusercontent.com/anujdevopslearn/98a73c0ef7f72a70fc11759f8b2b9c25/raw/344bd206c7dbadfd56f32dc755c06e450c9b0d0f/mysql.yml

ansible-playbook mysql.yml


service mysql status
