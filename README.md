1.	Import data from twitter using flume.
2.	Download that data to local file system.
3.	Rename it as you wish
4.	Create input folder in hdfs
5.	Upload the rename twitter file to hdfs input folder
6.	Create java project in eclipse
7.	Write down all required classes.
8.	Import all Hadoop libraries to java project.

9.	Create jar file

(       right click on project 
        go to export
        select java then JAR File then click next
        select 2nd, 3rd and 4th chick box 
        then  select the export destination: select path where u want to store jar file
        then click on next abain click on next
        go to select the class of the application entry point:
        click on Browse select main class of your application
        then click on finish
        your jar file create on yr distination lacation
)

10.	Copy that jar file to virtual machine using filezilla or any other tools

11.	Run the jar on Hadoop.
      command:  hadoop jar jarfile.jar /input /output

12.	See the output of the file which is created automatic on hdfs system in output folder.
