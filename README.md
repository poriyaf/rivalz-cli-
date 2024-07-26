# rivalz-cli-
Learning how to set up node from scratch
First, you need to buy an Ubuntu server with IPv4.
Then you need to install Termius, which is the interface between the computer and the server.
Now you need to enter the server details in Termios and connect .
![rivalz](https://github.com/user-attachments/assets/8179e763-6929-4bf3-9aec-fd96f8701976)
Click on connect
![rivalz2](https://github.com/user-attachments/assets/972b0f1c-7e35-4255-82b9-979988dce9e8)
.
Maybe there is no server, we start with the following codes
First of all, update your server:
<pre> apt update && apt upgrade -y </pre>
We copy the command and paste it in Termius with control + shift + v. We place all the commands in the same way
<pre>Now we install the curl function:</pre>
<pre>apt install curl </pre>
We copy the command and paste it in Termius with control + shift + v
Rivals requires version 20 of Node.js, so we install it from the repository:
<pre>curl -fsSL https://deb.nodesource.com/setup_20.x <span class="pl-k">|</span> sudo -E bash -</pre>
Then we install the Node.js package:
<pre> nodejs -v </pre>
Now it's time to install Rivalz itself:
<pre> npm i -g rivalz-node-cli </pre>
Now enter this code:
<pre> rivalz run </pre>
and then enter all information as shown in the image below:
<pre>1-Your wallet address</pre>
<pre>2-CPU core</pre>
<pre>3-RAM</pre>
<pre>4-Select disk type</pre>
<pre>5-Select disk serial number</pre>
<pre>6-Enter disk size, you want to allow the client use</pre>
![rivalz2](https://github.com/user-attachments/assets/d9d8db09-2c83-43a8-acf6-d5b41e032f76)

If your configuration is valid, the terminal will display as shown in the image below :
![rivalz](https://github.com/user-attachments/assets/37ce3dd4-d251-4faf-98af-cdd2ef5cdd65)

And it repeats every moment:

![rivalz2](https://github.com/user-attachments/assets/f194fa12-df9f-495d-9b03-06c4db62b3e7)



