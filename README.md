# MovieTestingAutomation
>Steps to Run the Automation Test Scripts through Framework
>Navigate to the GitHub Link: https://github.com/rajateshr/MovieTestingAutomation
>Try to download the Movie.zip project folder from the github
>Then after downloading the "Movie.zip" automation project folder, then unzip or extract the automation project folder
>After extracting the automation project folder, save in the local folder
>Open the Eclipse and Under Eclipse, select 'Import',then Expand 'Maven'>Existing Maven>Select the Existing Maven Project folder name 'Movie'
>After successfully import Maven Project,to run the TestSuite in Automation Project, Right Click on pom.xml, Run as >Run Configurations
>Under Run Configurations,for Maven build 'MovieTest', Enter Goals:clean install, Add Parameter name 'browser':'Chrome'..
>Then add one more parameter 'xmlFiles':'testng.xml' and Click on Run
>After completing the executing the test suite,to check the Test Reports, Goto Reports>Then right on 'ExtentReportResults.html', select Open with web browser
