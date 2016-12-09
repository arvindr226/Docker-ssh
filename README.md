
## Openssh server enabled in the Ubuntu 14.04 images on Docker.


Git clone the repository
<pre>
$ git clone https://github.com/arvindr226/ssh
</pre>
Get in the repository and make docker image build.
<pre>
$ cd ssh 
$ docker build -t arvindr226/ubunutu14.04-ssh .
</pre>
Docker run using below command. 
<pre>
$ docker -d --name ssh -p 2222:22 arvindr226/ubunutu14.04-ssh
</pre>
To Check the ssh login like below
<pre>
$ ssh root@localhost -p 2222
</pre>
Default password-: screencast
