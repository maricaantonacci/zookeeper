# zookeeper
Dockerfile to build Zookeeper Docker image

<pre>
docker run -d -e MYID=<myid> -e SERVERS=<node1,node2,node3> --name=zookeeper --restart=always --net=host <docker-image>
</pre>
