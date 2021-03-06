# SSH
Click on the link to the operating system you are using

[SSH on Linux](#sshlinux)

[SSH on Mac](#sshmac)

[SSH on Windows](#sshwindows)

# SSH on Linux<a name="sshlinux"></a>


**Note:** Instructions are provided for Ubuntu, but if you are running a different flavour of linux, the only thing that should be different is how to open the terminal. From step 3 onwards, everything should be identical.


1) On Ubuntu, click on the icon in the top left of the screen


2) Type *Terminal*  and open the terminal application

![](images/linux_find_terminal.png)


3) Into the Linux terminal that appears, type
   ``ssh username@servername``
   replacing username and servername with the username and server name that you have been emailed

   ``ssh james@james.genomicscourse.com``


4) You will see a message the first time you log in, saying:

   ``The authenticity of host 'james.genomicscourse.com (192.135.232.24)' can't be established.
   ECDSA key fingerprint is SHA256:xmvrB9Ke/bXNtpu5PXF6IbUS8wxCtF6SNqZ7VV+IRoU.
   Are you sure you want to continue connecting (yes/no)? ``

   and asking if you wish to continue connecting. This message is normal when you log in to a new server. Agreeing will store the server's fingerprint, and the message will not appear again.

5) Type yes into the Linux terminal and hit return


6) You will then be asked for a password.

   ``james@james.genomicscourse.com's password:``

   Type in the password that you've been emailed, and hit return. Nothing will appear while you type. If you know you have made a mistake, you can hold down backspace, and retype the password.


7) Congratulations! You are now logged in!


# SSH on Mac<a name="sshmac"></a>

1) Press Cmd-Space to open Spotlight and type *Terminal* in it. Press Enter to open Terminal

2) Into the Mac terminal that appears, type
    ``ssh username@servername``
    replacing username and servername with the username and server name that you have been emailed

    ``ssh james@james.genomicscourse.com``


3) You will see a message the first time you log in, saying:

    ``The authenticity of host 'james.genomicscourse.com (192.135.232.24)' can't be established.
    ECDSA key fingerprint is SHA256:xmvrB9Ke/bXNtpu5PXF6IbUS8wxCtF6SNqZ7VV+IRoU.
    Are you sure you want to continue connecting (yes/no)? ``

    and asking if you wish to continue connecting. This message is normal when you log in to a new server. Agreeing will store the server's fingerprint, and the message will not appear again.

4) Type yes into the Mac terminal and hit return


5) You will then be asked for a password.

   ``james@james.genomicscourse.com's password:``

   Type in the password that you've been emailed, and hit return. Nothing will appear while you type. If you know you have made a mistake, you can hold down backspace, and retype the password.

6) Congratulations! You are now logged in!

# SSH on Windows<a name="sshwindows"></a>

## Installing MobaXTerm
There are a number of SSH clients you can use, but for the purposes of this practical, we would recommend MobaXTerm.


1) Download MobaXTerm from:
<https://mobaxterm.mobatek.net/download-home-edition.html> - select installer version

2) Unzip the folder you downloaded


3) Run the file ending in .msi - you'll get a windows prompt to install this, which it is safe to agree to. Install MobaXTerm in the default location, and you're then ready to log in

## Logging in through MobaXTerm
1) Open MobaXTerm from the Windows start menu (if you can't find it, use the search bar)


2) Click on Session in the upper left of MobaXTerm ![](images/mobasession.PNG)


3) Select SSH in the window that opens


4) In the next window, enter in the name of the server, into the Server Name box. If you have been given the server name in the form *yourname@yourname.genomicscourse.com*, you just need the part after the @ (so, *yourname.genomicscourse.com*)
![](images/ssh_login.png)

5) Tick the *specify username* box, and add your username (included in the email that we sent you with log in details)


6) Tick OK, at the bottom of the box


7) You may see a message the first time you log in, saying that "the authenticity of the host can not be established", and asking if you wish to continue connecting. This message is normal when you log in to a new server. Agreeing will store the server's fingerprint, and the message will not appear again.
![](images/warning.png)


8) Type yes and hit return, if the message appears



9) You will then be asked for a password.

    ``james@james.genomicscourse.com's password:``

    Type in the password that you've been emailed, and hit return. Nothing will appear while you type. If you know you have made a mistake, you can hold down backspace, and retype the password.

10) Congratulations! You are now logged in!
