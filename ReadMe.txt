Supported HX Versions
    2.6
    3.0
    3.5
    4.0

Supported HX Clusters
    Hyperflex Standard Cluster
    Hyperflex Edge Cluster (3N and 4N ROBO)
    Only supported on Hyperflex cluster on VMWare ESXi


When to use?
    Before an Hyperflex upgrade
    Health Check before and after Maintenance Windows
    When working with TAC and/or Opening a TAC case
    Recommended that you provide the output from the tool while opening a TAC case


How to use the tool?
Pre-requisite:  Script needs HX and ESXI root password information to check all conditions

Steps:
1) Download the tool(HXTool.tar) and upload to the controller VM.
2) Untar the file using below command:
     tar -xvf HXTool.tar
3) Now run the python script file with below command:
   a) For Test summary report:
      python HXTool.py
   b) For Test detail report:
      python HXTool.py detail
4) Enter the HX root password.
6) Script will display the result on the console and also creates each node report(HX Report 10.197.252.79.txt) and main report txt file(HX Tool Main Report.txt) in the HX_Report_<timestamp> folder.

Test Details:
Detail info of the test are available in the file(TestInfo.txt).
