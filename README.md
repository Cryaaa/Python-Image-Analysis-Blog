# Intorduction to Using Python for Image Analysis
To get started using python the first step is the installation and there are several ways you can do it. To make it easier for your future self it's a good idea to set up a virtual environment. You can think of this as a virtual installation folder where you install all your python libraries (basically just functions that other people have written).
One way to manage these environments is [anaconda](https://www.anaconda.com/products/individual)
This will not only install anaconda, the software to manage your environments but also a lot of libraries commonly needed for scientific python programs. 

Once installed you can manage your environments via the command line. Every operating system has one and they differ slightly.
I'm using Windows and to open it you just need to search for 'cmd' and will find it.
The basic functionality and use of conda in it can be found in this [great explanation of command line and conda](https://youtu.be/MOEPe9TGBK0?t=1161), created by my supervisor.
Another nice explanation of the command line can be found by Sreeni [here](https://www.youtube.com/watch?v=AzuajQnRuGI&list=PLZsOBAyNTZwbIjGnolFydAN33gyyGP7lT&index=5&ab_channel=DigitalSreeni) and he also explains what an integrated development environment (in short IDE) is and why it is needed for coding [here](https://www.youtube.com/watch?v=BxebisJKWBg&list=PLZsOBAyNTZwbIjGnolFydAN33gyyGP7lT&index=7&ab_channel=DigitalSreeniDigitalSreeni).

To get Started with your first programs in python I would suggest you follow the tutorial on setting up an environment after installing anaconda. I can offer a bonus tip for creating conda environments and that is to install a specific python version (some libraries won't work with the newest python version but you may find that out yourself) and how to install all the essential scientific libraries included in anaconda. To do this you need to initialise a conda environment as follows:

'''shell
C:\Users\yourusername> conda create -n your_environment_name python=3.8 anaconda 
'''

You have to replace 'your_environment_name' with a name of your choosing and can choose any python version that works with your libraries. For now you can omit the line 'python=3.8' but if you run into problems you can go and add it again!
