# LibreOffice 7.5.3.2 Installation Guide

1. Download the DEB package from the official LibreOffice site. 

   "**wget https://downloadarchive.documentfoundation.org/libreoffice/old/7.5.3.2/deb/x86_64/LibreOffice_7.5.3.2_Linux_x86-64_deb.tar.gz**"

3. Extract the downloaded archive:
   
   "**tar -xvf LibreOffice_7.5.3.2_Linux_x86-64_deb.tar.gz**"
   

4. Navigate to the extracted directory and install all DEB packages:
   
   cd LibreOffice_7.5.3.2_Linux_x86-64_deb/DEBS
   sudo dpkg -i *.deb


6. After the installation is complete, check the installed version of LibreOffice by typing "**libreoffice --version**".

   If you see the message '**libreoffice: command not found**', verify the installation by checking the application menu

   or by typing "**dpkg -l | grep libreoffice**" in the terminal to list the installed packages.
