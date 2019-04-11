Please review the link before proceeding: [Link](http://docs.bluedata.com/awb34_bdwb-shell-commands)

Retrieve the BlueData base image for CentOS 7 using bdwb command

`bdwb --baseimg centos7`{{execute}}

A CentOS 7 directory will be created in the current directory. Navigate to it.

`cd centos7`{{execute}}

To list the contents inside centos7 directory execute the below command

`ls -a`{{execute}}

Make sure the folllwing files and directories are present:

<li>Build.sh</li>
<li>Makefile</li>
<li>Template</li> 



<b><li>Build.sh:</li></b>It is a file that contains a build script to build the centos7 image<br>
<br>
<b><li>Makefile:</li></b> It is a program building tool which runs on Unix or Linux<br>
<br>
<b><li>Template:</li></b> It is a directory that houses the Dockerfile.template and limits-90-nproc.conf files<br>
