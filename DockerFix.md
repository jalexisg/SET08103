**Starting Docker on the University Machines in D2**

The windows subsystem for Linux is not properly installed on the University Machines in D2. 

This stops Docker starting.

To correct this please follow the following instructions.

Start Docker, accept the terms and conditions. You will then get the following error.

![Graphical user interface, text, application Description automatically
generated](media/image1.png)

**Click Cancel rather than restart**

In the Docker Window that remains open go to settings (highlighted below)

![](media/image2.png)

In the settings turn Off WSL2

![](media/image3.png)

Then Click Apply and Restart.

Once restarted docker should work correctly.

You can test this from the command prompt by typing

*docker run hello-world*

You should get the following output

![Text Description automatically
generated](media/image4.png)
