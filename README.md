# bakr-plymouth
Plymouth boot splash for Linux forked from KUBUNTU-6.10-BOOT-SPLASH-PORT ver. 1.0.0

Checkout the original work on the [KDE Store](https://store.kde.org/p/1511317/)

![Screenshot](bakr-plymouth-theme/screenshot2.png "Screenshot preview!")

# Usage
After running the `INSTALL.sh` script, you should edit the `bakr-plymouth-theme.script` to customize the text message like the description below:
* Go to the following path: `/usr/share/plymouth/themes/bakr-plymouth-theme`
* Open the file named `bakr-plymouth-theme.script` with sudo priviledges to be able to save it. In Kde Plasma `Kate` could able to save after asking for root password.
* Look for a line starts with, `// Edit the following two variables`, *at the few initial lines of the file*
* At the next two lines edit the textual values of the two variables `distroStr` & `waitStr` with any text you want.
* Save the file
* from the command line run the following line: 
`sudo update-alternatives --config default.plymouth && sudo update-initramfs -u`
* Make sure to choose `bakr-plymouth-theme` if it is not the default one by entering its number and hit enter.

![Screenshot](bakr-plymouth-theme/screenshot3.png "Screenshot preview!")

