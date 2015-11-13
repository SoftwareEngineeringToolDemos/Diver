# Steps to create the VM using Vagrant (after installing Vagrant and VirtualBox)

1. Copy the file "Vagrantfile", "InstallChocolatey.bat" and "InstallJava.bat" to some folder in your local machine.
2. Open the default shell in your local machine and navigate to the folder where the "Vagrantfile" was copied to.
3. Type the following in the shell: "vagrant up" (without quotes)
4. The vagrant file will begin executing an at some point the VM will start up on VirtualBox and then Chocolatey and Java get installed.
5. Use these credentials to login to the guest OS:</br>
Username: vagrant</br>
Password: vagrant</br>

# Acknowledgments
* Used vagrant virtual box image of [Windows 7 64-bit by datacastle](https://atlas.hashicorp.com/datacastle/boxes/windows7).

#References
* https://docs.vagrantup.com/v2/getting-started/index.html
* https://docs.vagrantup.com/v2/provisioning/shell.html 
* https://docs.vagrantup.com/v2/virtualbox/configuration.html
* https://github.com/SoftwareEngineeringToolDemos/ICSE-2013-YODA/tree/master/build-vm
