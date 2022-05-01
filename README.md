# Laserhub_JMeter
JMeter automation project

JMeter(.jmx) script which is used to login to Laserhub application and assert whether the valid user is logged in. 

INSTALL
--------
1. Check whether Java is installed in your system. In command prompt type,
	java -version
    to check the same. 
2. If Java is not installed, download and install Java SE Development Kit 8u331 for the respective OS from the below link.
  https://www.oracle.com/java/technologies/downloads/
3. Download and install JMeter latest version from the Binaries section (.zip file) using the below link.
     https://jmeter.apache.org/download_jmeter.cgi

OPEN TEST SCRIPT
----------------
1. Open bin folder in Apache JMeter and run jmeter.bat file. This opens the JMeter in GUI mode.
2. Click File-> Open-> Select the .jmx test script ‘Laserhub_LoginTest.jmx’


RUN TEST SCRIPT
----------------
1.Click the green arrow play button to run the script.
2.Results can be viewed in the View Results Tree listener option.
3.Email and password are parameterized in the User defined variables option.
4.Assert call is made for the request after login which ensures the valid email used for signing in is present.
