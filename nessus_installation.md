# Nessus installation -->

# Step #1



Goto https://www.tenable.com/products/nessus/nessus-essentials and register an account.

You will need to do this for an activation code.

![image](https://user-images.githubusercontent.com/66565192/121795856-5fa6cf80-cc36-11eb-8a40-2ba37c04652e.png)


# Step #2
![2](https://user-images.githubusercontent.com/66565192/121795984-5ff39a80-cc37-11eb-9a6a-7e3b2e5b6ab6.PNG)



We will then download the Nessus-#.##.#-debian6_amd64.deb file

Save it to your /Downloads/ folder



# Step #3

In the terminal we will navigate to that folder and run the following command:

sudo dpkg -i package_file.deb

Remember to replace package_file.deb with the file name you downloaded.

![3](https://user-images.githubusercontent.com/66565192/121795960-17d47800-cc37-11eb-85e7-c4d3fb92e51c.PNG)


# Step #4

We will now start the Nessus Service with the command:
sudo /bin/systemctl start nessusd.service

![4](https://user-images.githubusercontent.com/66565192/121796020-a21cdc00-cc37-11eb-9808-5bd3951b9591.PNG)



# Step #5

Open up Firefox and goto the following URL:

https://localhost:8834/ 

You may be prompted with a security risk alert.

Click Advanced... -> Accept the Risk and Continue

![5](https://user-images.githubusercontent.com/66565192/121796027-b660d900-cc37-11eb-8359-38611a63fcb8.PNG)


# Step #6
Next, we will set up the scanner.
Select the option Nessus Essentials

Clicking the Skip button will bring us to a page, which we will input that code we got in the email from Nessus. 

![6](https://user-images.githubusercontent.com/66565192/121796041-d1cbe400-cc37-11eb-9c0e-f09629690dd9.PNG)

# Step #7
Fill out the Username and Password fields. Make sure to use a strong password!



# Step #8

Nessus will now install the plugins required for it to function.


This will take some time, which will depend on your internet connection and the hardware attached to your VM.

If the progress bar appears to be not moving, it means you do not have enough space on the VM to install.  


![7](https://user-images.githubusercontent.com/66565192/121796060-05a70980-cc38-11eb-83cc-7502c069bc06.PNG)



# Step #9
Log in with the account credentials you made earlier. 


# Step #10
You have now successfully installed Nessus!

![10](https://user-images.githubusercontent.com/66565192/121796092-46068780-cc38-11eb-9c31-07408f868490.PNG)


[+] Thanks
