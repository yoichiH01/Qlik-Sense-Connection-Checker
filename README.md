# Qlik Sense Connection Checker
- The app to scan the script logs and find out 'Store' and 'LIB CONNECT TO' type of connections

# Requirement
- The app works on both Qlik Sense Desktop and Qlik Sense Server
- More logs volume, more machine resource consumed. If resource shortage occurs, plsease either reduce the logs volume or increase machine resource
- Please create C:\yheTemp\Script\ folder and place the script logs into the folder

# Instruction
1. Download "QlikSenseConnectionChecker.qvf" onto yuor Windows Machine where installed Qlik Sense Desktop, or import it into your Qlik Sense Server from QMC.
2. Collect the Qlik Sense Script logs and copy them into C:\yheTemp\Script\
3. Open the app QlikSenseConnectionChecker from Qlik Sense Desktop Hub or Qlik Sense Server Hub
4. Reload the app
5. Go to "Connection Check" sheet and see the data

# Disclaimer
The application is not supported by Qlik. Please use it on your own risk. 

# License
This project is provided "AS IS", without any warranty, under the MIT License - see the LICENSE file for details
