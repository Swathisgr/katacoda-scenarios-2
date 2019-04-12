In this step we will extract the contents of the .bin file.
For this execute the following command.<br>
`./bdcatalog-centos7-bluedata-spark221-1.0.bin --payload`{{execute}}
<br>

This will create two files in the directory. (to view the files execute the following command)<br>
`ls`{{execute}}

Untar the payload.tar file by executing the following command
<br>`tar xvf payload.tar`{{execute}}

This will create new directories. (to view the files execute the following command)<br>
`ls`{{execute}}

Remove the bin and tar file to save space on the device
<br>`rm -rf bdcatalog-centos7-bluedata-spark221-1.0.bin`{{execute}}
<br>`rm -rf bdcatalog-centos7-bluedata-spark221-1.0.bin.tar`{{execute}}

Navigate to the new directory, and untar the file by executing the following command
<br>`cd bdcatalog-centos7-bluedata-spark221-1.0`{{execute}}
<br>`tar xvf bdcatalog-centos7-bluedata-spark221-1.0-src.tgz`{{execute}}

Now navigate to the directory created after the above step
<br>`cd bdcatalog-centos7-bluedata-spark221-1.0-src`{{execute}}
<br><br>
Copy the content of this directory to the directory you created initially<br>
`cp -R * ~/Source/Spark`{{execute}}
