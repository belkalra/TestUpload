Setup for the build infrastructure:
	1. Install Visual Studio and follow the Configuration document for setting up a python development build
	2. Add Python to your Path environment variable(make sure you use add it to your system PATH and not your user path; we’ve had issues where it was not 				detected if python was too far down the path variable)
	3. Download the Automation Project from Git
	4. In the Apollo Folder, make a folder called TestResults
	5. Download the TestResults Repository (URL here) and associate it with that folder
	6. Download the MasterTester.py from that repository
	7. Copy MasterTester.py into the Apollo Folder
	8. Schedule task to run as the user that installed Visual Studio and Git 
