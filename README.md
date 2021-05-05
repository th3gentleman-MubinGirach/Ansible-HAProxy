# Ansible-HAProxy
Configure HAProxy on AWS instances dynamically using Ansible </br>
<h2>This repository contains 2 main playbooks </h2>
 <i>1)setup.yaml </br>
    2)configure.yaml </i> 
<h2>And in all 4 roles </h2>
 <i>1)provision-node: to provision the nodes instance </br>
 2)provision-lb: to provision the load balancer instance </br>
 3)httpd - to install httpd and copy index.html into node instances </br>
 4)HAProxy - to install haproxy in load balancer install and copy config file of the same into the load balancer instance </br>
 </i> </br>

<h3>Instructions</h3> </br>
 <ol> 
  Give proper path of your key in the ansible config file </br>
  Give permission to the keyfile using chmod 0400 filename </br>
  Change the name in the yaml file of var directory as well </br>
  </ol>
  
