## Install Hadoop 3.3.0 on Windows 10 using WSL

**enable WSL by running the following PowerShell code as Administrator**  
*Enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux*  

**And then install Ubuntu from Microsoft Store.**

**Once download is completed, click Launch ubuntu button to launch the application.**  

**During the installation, you need to input a username and password. Once it is done, you are ready to use the Ubuntu terminal:**  
username : *ubuntu*  
password : *ubuntu*  

  
  
**Update installed packages with linux package manager.**  
*sudo apt update*  

**check installed java version.**  
java -version  

**If you get an error like below that means since this is a new user, java is not installed:**  
java --version  
Unrecognized option: --version  
Error: Could not create the Java Virtual Machine.  
Error: A fatal exception has occurred. Program will exit.  

**To install java use any of the below commands:**  
*sudo apt install default-jre*  
*sudo apt install openjdk-11-jre-headless*  
*sudo apt install openjdk-8-jre-headless*  

**To create a new user in ubuntu linux distro issue the below command:**  
*sudo adduser \<username\>*  

**Examples:**  
*sudo adduser ubuntu_ksh*  
*sudo adduser ubuntu_bash*  

**Running linux ubuntru distro with different user rather than default:**  
*wsl.exe -d Ubuntu -u \<username\>*  