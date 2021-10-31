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


**To create a new user in ubuntu linux distro issue the below command:**  
*sudo adduser \<username\>*  

**Examples:**  
*sudo adduser ubuntu_ksh*  
*sudo adduser ubuntu_bash*  
