# zookeeper
Dockerfile to build Zookeeper Docker image

<pre>
docker run -d -e MYID=$myid -e SERVERS=$server --name=zookeeper --restart=always --net=host <docker-image>
</pre>

Example:
<pre>
docker run -d -e MYID=1 -e SERVERS=node1,node2,node3 --name=zookeeper --restart=always --net=host <docker-image>
</pre>
