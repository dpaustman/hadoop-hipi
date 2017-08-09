This is the first program of HIPI that compute the average pixel color.
To run this program in your system do as directed:
Prerequisites:
1. Installed:
-Java
-Hadoop
-HIPI
-Gradle

Steps:
1. Download the zip file attached in the repository.
2. Copy this in /hipi/examples folder where your hipi is installed.
3. Create a folder in your hadoop user(Mine is hduser) with 4 images and name it sampleimages.
4. Create a hib using hibImport as per given in the official wesite: http://hipi.cs.virginia.edu/gettingstarted.html
5. Run the following command :
hadoop jar hipi-demo-1.0-SNAPSHOT.jar HelloWorld sampleimages.hib sampleimages_average
