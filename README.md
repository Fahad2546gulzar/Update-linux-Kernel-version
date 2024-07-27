# Update-linux-Kernel-version
Linux kernel version sometimes causes many problems.Its updation is required for installation of device drivers and for many other things on linux os.Here are some steps for updating kernel version.Feel free if you have any issue with the method.
# Update and Upgrade dependencies
1. `sudo apt upgrade`
2. `sudo apt upgrade`
# Add the Mainline Kernel PPA
First you need to add mainline kernel PPA:
1. `sudo add-apt-repository ppa:cappelikan/ppa`
2. `sudo apt update`
# Install the Mainline Kernel Installer
Now you need to install Mainline kernel installer as:
1. `sudo apt install mainline`
# Launch the Mainline Kernel Installer
Launch the kernel mainline installer as:
1. `mainline`
2. OR By graphically
# Select and install kernel version
1. In kernel Mainline GUI select the desired version for your system.
2. click on "Install"Button on right side of the window.
# Install kernel Header
`sudo apt install linux-headers-$(uname -r)`
# Done
Now your system kernel version is updated and you can easily install any driver easily.
In the case of any problem and for some other cause feel free to contact me on "g3388610@gmail.com"
