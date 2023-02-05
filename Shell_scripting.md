# How to onboard users to server

`mkdir Shell`[^3]

[^3]: We will first create a folder for the project(Shell) and cd into the folder (Shell)

`touch names.csv` [^5]

[^5]:This file is created to store the names of users into

`vim names.csv` [^11]

[^11]: Copy the names of users into the names.csv folder

`sudo groupadd developers`

`touch onboard.sh` [^17]

[^17]: this is done to create a file to input the shell script we have written

`vim onboard.sh` [^21]

[^21]: This is where the shell sript will be copied into

`cd .ssh`

`touch id_rsa.pub` [^27]

[^27]: We will create a file to copy our public key into

`vi id_rsa.pub`

`touch id_rsa` [^33]

[^33]: Create a file to copy in the private key

`chmod +x onboard.sh` [^35]

[^35]: This is done to give permission for our users to be onboarded to the server



`sudo su` [^43] ![Shell_scripting](./Images/change%20to%20root%20user.png)

[^43]: This is done to change our key to the root user

`./onboard.sh`![list of users](./Images/Screen%20Shot%202023-02-04%20at%2015.28.51.png)

[^47]: This is to sync into our users


