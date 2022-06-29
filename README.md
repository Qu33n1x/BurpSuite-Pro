# Burp-Loader
##################################** Prequisites **#############################################

	**Download .jar file for Burp Suite Pro from**
		--> https://portswigger.net/burp/releases/
	**Download Burp Loader files. Then Follow Below Steps for Activation**
		--> https://github.com/Qu33n1x/BurpSuite-Pro/
	**If using in Windows 10, Download and Install Java and JDK**
		**For Java** --> https://javadl.oracle.com/webapps/download/AutoDL?BundleId=244068_89d678f2be164786b292527658ca1605
		**For JDK**  --> https://www.oracle.com/in/java/technologies/javase-jdk15-downloads.html

################################** Execution and Activation **################################
	
	**1. Place all files in the same path
		java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:loader.jar -noverify -jar burpsuite_pro_v2022.5.jar &
	----------------------------------------------
	**2. Use keygen.jar to generate the License key**
		java -jar keygen.jar
	----------------------------------------------
	**3. Activate Burp Suite Pro**
		1. Modify License String like "license to Queenix"
		2. Copy License key from keygen.jar and paste in Burp Suite Pro and click Next.
		3. Select Manual Activation Option on your bottom Right in Burp Suite Pro.
		4. Copy License Request from BurpSuite_Pro and paste in keygen.jar
		5. Copy license response from keygen.jar and paste in BurpSuite_Pro, and next and Done
