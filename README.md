# LibreOffice-Installation-Guide
A step by step guide on how to install LibreOffice 3.5.3.2 directly from the offical website:

1. Download the DEB package from the official LibreOffice site. 
   wget https://downloadarchive.documentfoundation.org/libreoffice/old/7.5.3.2/deb/x86_64/LibreOffice_7.5.3.2_Linux_x86-64_deb.tar.gz

2. Extract the downloaded archive:
   tar -xvf LibreOffice_7.5.3.2_Linux_x86-64_deb.tar.gz

3. Navigate to the extracted directory and install all DEB packages:
   cd LibreOffice_7.5.3.2_Linux_x86-64_deb/DEBS
   sudo dpkg -i *.deb

4. After the installation is complete, check the installed version of LibreOffice by opening a terminal and typing "libreoffice --version".
   If you see the message 'libreoffice: command not found', you can verify the installation by checking the application menu
   or by typing "dpkg -l | grep libreoffice" in the terminal to list the installed packages.
