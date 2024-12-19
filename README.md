# OpenVAS-installation-configuration-setup


## First we have to update machine 
- We have to update machine using `sudo apt update`
- Then we have to perform dist upgrade `sudo apt dist-upgrade` (This command handles changes in package dependencies with new versions of packages and installs necessary new packages while removing any outdated packages.)


![Screenshot (55)](https://github.com/user-attachments/assets/6857d7e9-2d74-49e2-8b92-5f32b31e9978)
![Screenshot (56)](https://github.com/user-attachments/assets/a4012121-b827-4c61-86ec-4cb780e7094e)
![Screenshot (57)](https://github.com/user-attachments/assets/d27ac486-22b0-4027-8e92-d7c061defa2c)
- *Maybe it takes longer time*


## Installing OpenVAS
- Now we have to install openVAS using `sudo apt install openvas`
![Screenshot (58)](https://github.com/user-attachments/assets/f87a0999-413c-48ce-86e6-cff950b55d4a)

### *Then we have to setup _gvm_ (Greenbone Vulnerability Manager)*
- But in this case i face some error , and this you also face this type of error you can simply change
  go to _/etc/postgresql/16/main/postgresql.conf_ file and open _postgresql.conf_ file and find port then simply change the port number
- Then simply restart the setup process `sudo gvm-setup` and start process , It may take long time
  
![Screenshot (59)](https://github.com/user-attachments/assets/1ff02bcf-5fad-4868-ae08-3c2291d1ac6b)
![Screenshot (60)](https://github.com/user-attachments/assets/d7117971-d4a6-469e-91a4-6a2853376ec9)
![Screenshot (61)](https://github.com/user-attachments/assets/733e2a52-453f-439c-949f-54029f31600d)

*we can check if setup is sucessful or not `sudo gvm-check-setup`*

![Screenshot (63)](https://github.com/user-attachments/assets/c498606f-7bf7-420e-9912-ae14903f0398)
![Screenshot (65)](https://github.com/user-attachments/assets/cd6982d5-b338-45f6-b73e-f7a067b257c5)

### This is the login page of OpenVAS client
you can login with default credential
![Screenshot (66)](https://github.com/user-attachments/assets/de78d0a5-bdbb-4c7c-8c16-629a094cff4d)
![Screenshot (67)](https://github.com/user-attachments/assets/9113f49e-5bf4-495f-a18d-17beaadf42d6)
![Screenshot (68)](https://github.com/user-attachments/assets/a5846486-6746-408c-b33b-43d047a9ae9f)
![Screenshot (471)](https://github.com/user-attachments/assets/12720d95-cb33-41d8-bf93-1b453e76c250)
![Screenshot (482)](https://github.com/user-attachments/assets/0f89868c-dd25-4de8-99c9-04edf4115525)
![Screenshot (490)](https://github.com/user-attachments/assets/428fb8ff-2599-4e6d-87dc-699ee7ca2a44)




