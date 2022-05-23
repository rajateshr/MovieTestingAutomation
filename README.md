# MovieTestingAutomation
Steps to Run the Automation Test Scripts through Framework -
1. Download the Movie.zip project folder from this github repository.
2. Unzip or extract the automation project folder.
3. After extracting the automation project folder, save in the local folder.
4. Open Eclipse and Under Eclipse, select 'Import', then Expand 'Maven'>'Existing Maven'>Select the saved local folder->'Movie' folder as root directory.
5. After successfully importing Maven Project, to run the TestSuite in Automation Project, Right Click on pom.xml, Select 'Run as'->'Run Configurations'
6. Under Run Configurations,for Maven build 'MovieTest', Enter Goals:clean install, Add Parameter name 'browser':'Chrome'.
7. Then add one more parameter 'xmlFiles':'testng.xml' and Click on Run
8. After completing the execution of the test suite, to check the Test Reports, Goto Reports>Then right on 'ExtentReportResults.html', select Open with web browser
9.Note that Excel sheet-'MovieTestData_Test.xlsx' is required to give following inputs for scripts to run:
-ImdbUrl: Imdb Home url
-WikiUrl: Wikipedia Home url
-SearchKeyword-- Movie Search keyword for both sites.For example 'Pushpa The Rise Part 1' can just be searched by typing 'Pushpa' in search tab
-MovieName in IMDB--Movie Name as displayed in IMDB.For example 'Pushpa The Rise Part 1'
-MovieName in Wiki--Movie name as displayed in Wikipedia..For example 'Pushpa: The Rise'
