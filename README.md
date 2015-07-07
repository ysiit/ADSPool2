LINK FOR WORKING DESIGN POOL URL IS AS FOLLOWS:
http://adspool2.yakshna.com

AGILE DELIVERY SERVICES FOR DESIGN POOL-1 BY
YAKSHNA SOLUTIONS, INC. (YSI)
07/06/2015

I. DEVELOPMENT APPROACH FOR DEVELOPMENT POOL PROTOTYPE

YSI identified the Technical Architect who is cerified scrum master to lead on Agile delivery services.He was pulled from  current working project to lead on ADS prototype.  Technical Architect was responsible for budgeting and allocation of the resources. He initiated 30 minutes stand up meeting.He identified the team with labor category DevOps Engineer and Front end web developer to work on development pool prototype. Team has expertise in open source technologies like HTML,CSS,jQuery,AJAX and Bootstrap. Team discussed the RFQ and the other documents .Team did review of Q&A response documents provided by the agency and did brainstorming session. Team Identified the needs of patients and the Healthcare provider needs. After couple of discussions,team came up with High Level Requirement document.Refer document for requirements YSI_ADS_System_Requirement_Specification_Development_Pool_2 in the Repository. And team identified the data set Drug to be shown on user interface which is taken from www.open.fda.gov website.Data elements are discussed in the meeting which need to be displayed on interface from Drug dataset.

Design Phase:Team started putting up the high level design document to prepare the Development pool prototype.Open source Technologies were identified HTML5, CSS 3, Jquery, Bootstrap for responsive design.HTML page had been designed by Visual designer to display the Drug details on the static user interface and responsive design was made to support multiple devices like mobile devices,desktops,laptops etc.

Development Phase: After the completion of static design team started the developement of the pool with search functionality of drug.unit test was written by the team for positive and negative scenarios to test the functionality.Refer the document YSI_ADS_Unit_Test_Development_Pool_2 in the repository for unit test of development pool.

Tortoise SVN tool was used for configuration management and maintaining the iterations of the code. Technical Architect reviewed the design and gave the review comments which were followed by team. couple of iterations was made to the development after incorporation of review comments and bug fixes of unit test.

Testing Phase : After the completion of development, testing phase was initiated by the team. Execution of test cases was maintained in Jira. Test Automation was completed in Selenium. Test cases was written and test cycle executed and defect log were generated. Refer test documents in the repository for more details Test Plan,Test case report,Defect Report : 
YSI_ADS_System TestCase Report_Development_Pool_2
YSI_ADS_System_Defect_Report_Development_Pool_2
YSI_ADS_System_Requirement_Specification_Development_Pool_2
YSI_ADS_System_Test_Plan_Development_Pool_2
YSI_ADS_System_Test_Report_Development_Pool_2
YSI_ADS_Test_Automation_Run_Report_Development_Pool_2
YSI_ADS_Test_Automation_Run_Report_Development_Pool_2_Iteration1
YSI_ADS_Test_Automation_Run_Report_Development_Pool_2_Iteration2
YSI_ADS_Test_Automation_Run_Report_Development_Pool_2_Iteration3

II.  HOW TO INSTALL DEVELOPMENT POOL PROTOTYPE ON WINDOWS PLATFORM

1. Create an application pool in the IIS interface from application pools section
2. In the add application pool dialog box give any name and select any .net framework since the source code will work in any framework
3. Select integrated pipeline mode and click ok to create the application pool
4. Give permission to the IIS identity which is running the application pool to the source code folder
5. Create a website in IIS interface by right clicking in the sites node
6. In the add website dialog box provide site name, root path to the source files, host header names if any
7. Select the application pool name from the step 3
8. Select the newly created website name and from the right pane select Default Document
9. In the default document list check and make sure index.html is present
10. Access the domain and check and make sure the website is giving the index.html as the response.

III. HOW TO INSTALL DEVELOPMENT POOL PROTOTYPE ON LINUX PLATFORM
Refer document in the repository : YSI_ADS_Installation_Guide_Development_Pool_2

IV. MINIMUM SYSTEM REQUIREMENTS 

¥ Windows or Linux OS, Internet Connectivity
¥ Minimum 64 MB of RAM
¥ Internet Explorer 9.0 or above, Chrome 38 or above and Firefox 35 or above, Safari 5 or above

V. KNOWN RISKS

Data will be shown to user fetched from open.fda.gov API.If the API fails then user interface will not show up the data. Prototype has dependency on the dataset returned from open.fda.gov API. Also the system is not developed for Section 508 compliance due to the time constraint.
