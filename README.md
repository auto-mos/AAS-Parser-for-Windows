# 1. Introduction  
This program is used to convert the AAS files into a suitable format for AAS-based cloud data acquisition and storage system, and was developed to be used in Windows 10 (and 11) environment to provide the user convenience. 

# 2. Installation
### Step 0
* Put the downloaded files in C drive.

### Step 1
* Run the 00.PackageChecker.exe. In this progress, This executable checks the installed Python version and packages.
* If the Python is not installed, Opens the Python download window. Available Python versions are 3.8.2~3.8.xx.

![h2p2](https://user-images.githubusercontent.com/114371609/214745542-bcc38336-b8ab-4709-939f-e44833ef7db6.png)


### Step 2
* After downloading all the packages through the Package Checker program, run the 01.Start_AAS_Parser_WS.exe executable file.
*  

![h2p3](https://user-images.githubusercontent.com/114371609/214744435-70c04c39-61ab-4cd7-97b6-a35dceeb0c46.png)

# 3. Running on Windows

 ### Step 0
 * Click '01.Start_AAS_Parser_WS.exe' to run the server.
 * [Note] To use this program, an XML file created by AASX Package Explorer is required. 

 ### Step 1
 * You have to put the extension(.xml) into the AAS directory(C:\AAS_Parser_V20230105\aas). 
 * Upload the XML file using the two buttons below.
 
 ### Step 2
 * After uploading the XML file, click the button 'Converting your AAS model' on the left table
 * Wait for a while until the 3 files(nodeset.xml, engineering.csv, syscfg.json) are created. 

 ### Step 3
 * In the progress, you can see the creation process of the 3 converted files through your command prompt screen. 
 * You can also check it through the output log button on the left table.

 ### Step 4
 * Now you can download the 3 files created. Click the Download button on the left table.
  
![h2p](https://user-images.githubusercontent.com/114371609/214742281-e6ceb7a2-358f-435c-8ea9-94a73b717d0d.png)

 ### Step 5
 * Edit the downloaded files and upload them to the AAS server and Edge Gateway server.
  
# 4. How to implement an AAS Model for AAS Solution.
 * Now.

